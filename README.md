=======
THIS CODE IS 'UNRESTRICTED PUBLIC DOMAIN' LICENCED.


GPSToggler
==========

GPS toggle widget for Android rooted devices. It wrks well even for those ROMs and kernels, other software failed.
It requires the 'su' privilegies only during the very first run (reboot is still required). 


Versions:

0.40
----

1. 4.3+ ROMs especially for Note 2 and similar devices aren't honest toward SU. 
   The workaround is known (see CWM Superuser open-source project). 
   To simplify the things the original SU used instead of the local one for all the relevant activities.

2. Fixed bug when Waze/Mapps switched off anf the screen turned off immediately.


0.19
----

The log is simplified.
THe main service is self-repairing after Android killed it.
Optional notification and icon added.


0.16
----

Improved (up to some level) the recognition of running GPS software and especially the finishing of the run.
Little log improvement for above process.


0.15
----

Added two passive activities: 'OnActivity' and 'OffActivity'.
Those two used to automate GPS on/off from 3rd party applications.

Added 'GPSActivityTest' application as an example of above.


0.14
----

Implemented fully automatic uninstall for the system module. 

'SU' utilization is minimized. The application asks for the 'SU' permission only once during the first run.

Implemented the 'SU' bypass algorithm (own local 'SU') to minimize the user bothering. 


0.13
----

Implemented semi-automatic uninstall for the system module.


Before 0.13
-----------

Early public releases.

>>>>>>> refs/heads/master
