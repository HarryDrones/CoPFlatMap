CoPFlatMap
show how circles of equal altitude morph on a map with changes in GHA/azimuth and altitude as received over USB
You need a Multiwii 2.3 IMU for the multiwii serial protocol which the msppg parser uses to communicate
with android over USB. The parser came from Professor Levin of Washington and Lee University.  The Usbserial low 
level stuff came from fehlr.com .  The matrix stuff came from navigationalalogrithms.com

So, to use it you also need an android device and probably Android Studio to compile it and upload it.
The "circles" on a flat map are more like sine waves or oblong circles depending on altitude.  On a sphere
these actually look like circles of varying size, with the big sine waves being big circles and the little egg shapes
being small circles.
