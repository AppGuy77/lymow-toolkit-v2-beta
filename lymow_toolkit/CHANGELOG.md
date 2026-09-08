Lymow Toolkit v2.2.2-beta

**Beta on its own download channel** — recommended for now to people running two or more mowers. It installs
over your current Toolkit (sign-in, maps, settings and history are kept). To go back, install the latest stable release from the
stable releases page: https://github.com/AppGuy77/lymow-toolkit-downloads/releases/latest


- Fixed: the precision guard paused the mower seconds after it left the dock for "No fix" and never resumed, while the RTK receiver was Fixed and the official app looked fine. The mower's positioning flag reads "GPS only" for 5 to 30 seconds after every departure; the guard judged that flag alone. The fix verdict now comes from both the flag and the receiver's own fresh reading, everywhere the fix is shown (pin, card, diagnostics, RTK log's new Fix column, Home Assistant sensor). The precision limit still pauses a real degradation.
- Fixed: phone notifications said "RTK base link dropped / restored" for the Toolkit's cloud connection to the mower. They now say "Cloud link to the mower dropped / restored".


This beta channel updates independently of the stable Toolkit; report anything odd on the beta repo's Issues page.
