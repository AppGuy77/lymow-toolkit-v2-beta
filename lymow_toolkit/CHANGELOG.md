Lymow Toolkit v2.0.3-beta

**Beta on its own download channel** — recommended for now to people running two or more mowers. It installs
over your current Toolkit (sign-in, maps, settings and history are kept). To go back, install v1.54.2 from the
stable releases page: https://github.com/AppGuy77/lymow-toolkit-downloads/releases/latest


- Fixed: the camera grid's WiFi picture on Windows works again the way v1 did — each grid camera now connects directly to its mower over WiFi first (no relay, no cellular), and only falls back to the relay and then 4G if that link cannot form. This removes the "Windows can't show the WiFi picture over plain http" wall on Home Assistant, VPN and LAN.
- Includes the 2.0.2 fix: the grid no longer races the video helper's startup (connection-refused on every camera but the first).
- Everything from v2.0.0-beta: Fleet Mode, Locations, per-mower tabs, the fleet Calendar, the camera grid and broadcast cutting parameters.


This beta channel updates independently of the stable Toolkit; report anything odd on the beta repo's Issues page.
