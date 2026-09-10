Lymow Toolkit v2.2.3-beta

**Beta on its own download channel** — recommended for now to people running two or more mowers. It installs
over your current Toolkit (sign-in, maps, settings and history are kept). To go back, install the latest stable release from the
stable releases page: https://github.com/AppGuy77/lymow-toolkit-downloads/releases/latest


- Fixed: random pauses with both RTK guards off. "Stuck — escaping" is the mower's own maneuver and "Stop the mower when it hits resistance" paused it the instant that state appeared; with Auto-resume off the mower then sat Paused with no fault code and no app notification. The rule now gives the mower 30 seconds to work itself free first, the way the official app does, and pauses only if it is still stuck after that; a blade-stall code is still acted on at once.
- Every "Mowing paused" line in the event log now says who paused the mower — the Toolkit (which button, rule or guard) or "not commanded by the Toolkit".
- Leaving remote control pauses only a mower that was actually under remote control; Home Assistant's stop, dock and cancel no longer pause a mower that was simply mowing.


This beta channel updates independently of the stable Toolkit; report anything odd on the beta repo's Issues page.
