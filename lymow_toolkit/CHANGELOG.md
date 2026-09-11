Lymow Toolkit v2.3.0-beta

**Beta on its own download channel** — recommended for now to people running two or more mowers. It installs
over your current Toolkit (sign-in, maps, settings and history are kept). To go back, install the latest stable release from the
stable releases page: https://github.com/AppGuy77/lymow-toolkit-downloads/releases/latest


- New: Adjust cut angle offset. Turn it on (next to Multi-pass on the Map tab) and the mower shifts its cut angle a little after every completed mow, so it never lays the same stripes twice — evening the finish and helping stop ruts. It works per zone, like your other cut settings: select zones on the map to set it for just those zones, or select nothing to set the default for every other zone. Optimized zones rotate from the direction the mower would pick; Chess Board and Adaptive Zigzag zones are left alone. You choose how many degrees to shift each mow (1–179°). Reset returns each zone to its original angle. It runs instead of a Multi-pass catch-up, not alongside it.
- New: scheduled mows can rotate the cut angle by an amount you choose. "Rotate the cut angle each run" used to be a fixed 30°; now there is a "Rotation per run" slider (1–179°).
- Removed: "Download all to this PC" on the Maps page. A map saved to a PC cannot be restored to a mower, so it was dead weight — cloud restore points remain the way to back up and restore a map.
- Removed: the "Merge zones — Coming soon" placeholder, which needs Bluetooth the Toolkit cannot use and was never going to arrive.


This beta channel updates independently of the stable Toolkit; report anything odd on the beta repo's Issues page.
