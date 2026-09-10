Lymow Toolkit v2.2.4-beta

**Beta on its own download channel** — recommended for now to people running two or more mowers. It installs
over your current Toolkit (sign-in, maps, settings and history are kept). To go back, install the latest stable release from the
stable releases page: https://github.com/AppGuy77/lymow-toolkit-downloads/releases/latest


- Changed: fault recovery is now an exclusion list. After a stop the Toolkit clears the fault and resumes the mow for every fault the mower can report — including codes that were never shown before — up to your Attempts, unless you switch that fault off. Before, only a short recommended set recovered and everything else was off by default. The safety-critical faults (lifted, tilted, unsafe drop, out of bounds) are shown locked and are never restarted.
- Changed: RTK and positioning faults recover on their own now. The separate "Clear and resume on RTK faults" switch on the Map tab is gone; those faults are ordinary rows in the fault list, recovered unless you exclude them, still waiting for the fix to come back and stay back before each attempt.
- The fault list under Settings → Warnings & errors now shows every code the mower can report, grouped by category, each with its own on/off and its own optional attempt count.


This beta channel updates independently of the stable Toolkit; report anything odd on the beta repo's Issues page.
