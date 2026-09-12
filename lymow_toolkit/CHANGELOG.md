Lymow Toolkit v2.4.0-beta

**Beta on its own download channel** — recommended for now to people running two or more mowers. It installs
over your current Toolkit (sign-in, maps, settings and history are kept). To go back, install the latest stable release from the
stable releases page: https://github.com/AppGuy77/lymow-toolkit-downloads/releases/latest


- New: **Plot on Error** — a map overlay that drops a colored, tappable marker wherever a mower hits an error or warning code you choose, so you can find the exact trouble spot on your lawn. Turn it on next to the other overlays on the Map tab, then pick your codes and the marker color in the ⚙️. It works across the whole fleet: the codes and color apply to every mower, each mower's faults plot on the one shared map (labeled with the mower), live. Only faults after you switch it on are plotted; if a mower has no live satellite fix right then it uses its last known position and marks the pin approximate. Every plotted fault is also written to the Event log with its latitude and longitude.
- The map's overlay switches (Mowed, Precision heat, Link heat, Freshness, and now Plot on Error) now sit together on one row under the map controls.


This beta channel updates independently of the stable Toolkit; report anything odd on the beta repo's Issues page.
