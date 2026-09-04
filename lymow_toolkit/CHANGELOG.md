Lymow Toolkit v2.1.4-beta

**Beta on its own download channel** — recommended for now to people running two or more mowers. It installs
over your current Toolkit (sign-in, maps, settings and history are kept). To go back, install v1.54.2 from the
stable releases page: https://github.com/AppGuy77/lymow-toolkit-downloads/releases/latest


- Fixed: on a fresh start, the camera grid brought up one mower and showed "same network / multicast" for the rest until it was closed and reopened. The Toolkit was using the cloud's stale address for any mower that had not yet reported its own; it now asks the mower and waits for its answer first, and a refused picture says exactly why, by mower name.
- Fixed: the Auto / WiFi / 4G camera link is now one setting per mower, shared by the Remote tab, the Overview camera and the grid, saved on the server for every device you sign in from. It always shows which one is selected and always comes back to your last choice; a mower never set uses Auto. The Remote and the grid used to keep separate settings that could overwrite each other, leaving the Remote with no selection.


This beta channel updates independently of the stable Toolkit; report anything odd on the beta repo's Issues page.
