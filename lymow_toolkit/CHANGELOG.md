Lymow Toolkit v2.1.8-beta

**Beta on its own download channel** — recommended for now to people running two or more mowers. It installs
over your current Toolkit (sign-in, maps, settings and history are kept). To go back, install the latest stable release from the
stable releases page: https://github.com/AppGuy77/lymow-toolkit-downloads/releases/latest


- Fixed: the WiFi camera "via Toolkit" (away link, Nabu Casa, iPhone, Home Assistant) failed with "No usable temporary directory found" when the Toolkit computer's disk was full. The relay keeps its configuration in the Toolkit's data folder now, or runs with no file at all, and says why when it cannot start.
- Fixed: iPhone showed "Tap to start the live picture" on every retry when the relay had not started. The phone now asks the Toolkit first and shows its reason; the tap prompt is only for a real autoplay block.
- Fixed: away from home every camera-grid tile waited about 30 seconds on a direct link that cannot exist there. Tiles now go straight to the relay.
- Fixed: Windows on a plain http page (Home Assistant on the LAN, http://<address>:8787) refused the WiFi picture with "Windows can't show the WiFi picture over plain http". It should now play over WebRTC through the Toolkit computer's port 8788; the Windows installer opens it, Docker Desktop users add the 8788 mappings.
- Fixed: turning the blades on in remote control (and other parameter changes) failed with "OSError: Read-only file system" when the Toolkit computer's disk could not be written, because a configuration backup was saved first. The command now goes out and says that no backup could be kept; the Toolkit computer panel shows a read-only data drive and what to do.


This beta channel updates independently of the stable Toolkit; report anything odd on the beta repo's Issues page.
