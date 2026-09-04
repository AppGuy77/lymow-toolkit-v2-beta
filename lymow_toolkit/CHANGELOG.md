Lymow Toolkit v2.1.2-beta

**Beta on its own download channel** — recommended for now to people running two or more mowers. It installs
over your current Toolkit (sign-in, maps, settings and history are kept). To go back, install v1.54.2 from the
stable releases page: https://github.com/AppGuy77/lymow-toolkit-downloads/releases/latest


- Fixed: Pause on Float and Pause on No fix now work — the fix-quality numbers were wrong since the guard shipped (a Float read as "RTK fixed"); every screen, the heat map, the Home Assistant RTK sensor and the guard now use the mower's real values.
- Fixed: a guard that is on works on its own — no Settings master needed, and Cancel Task no longer disarms the guards until the next Resume.
- Fixed: nothing switches on without what it needs — dependent options are greyed on the same screen, name the switch they need, and the Toolkit refuses to store them otherwise. Auto-resume now sits in the precision window too.
- Fixed: guards act on every position report (within a second), confirm each pause by read-back, report an unconfirmed pause, log a withheld pause by gate and a failed guard by name; the precision window shows live what the guard sees. Skip near the dock capped at 15 m.


This beta channel updates independently of the stable Toolkit; report anything odd on the beta repo's Issues page.
