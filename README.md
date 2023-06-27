Light Interference Simulator User Manual
==============================================================

To start the GUI program, run Lis.exe

Guide for creating a setup and running a simulation:

1. Add components via the "+" button
2. Select a component by clicking on the "Components" menu
and clicking on the component (E.g. Laser 1, Mirror 2)
3. Edit parameters in the inspector tab
4. Delete a component by selecting it and pressing the
"Delete component" button in the inspector
5. Click the "Launch" button

To save or load a setup (components plus global settings),
click on the "Save" or "Load" button beneath the
"Launch" button

--------------------------------------------------------------

List of global settings:

Wavelength - As the simulator supports light of a single
wavelength, it is adjusted via this global setting

Calculation density - The number of rays into which a
scattering ray scatters onto a component exposed to the
ray, the angle between the furthest scattered rays is PI

Collision test density - The number of segments used to check
for obstacles between a component and a ray. A value of 30-50
is generally sufficient unless components vary greatly in size

Calculation thread count - Used for multithreading. Equals the
number of threads created to share the workload of calculating
points on the screen. Workload is roughly the screen
resolution devided by the thread count

Instance port - Mechanism used for preventing concurrent
calculations, generally does not need to be changed

--------------------------------------------------------------

IBDP Computer Science Internal Assessment
