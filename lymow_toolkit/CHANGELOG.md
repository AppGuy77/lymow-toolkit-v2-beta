Lymow Toolkit v2.1.1-beta

**Beta on its own download channel** — recommended for now to people running two or more mowers. It installs
over your current Toolkit (sign-in, maps, settings and history are kept). To go back, install v1.54.2 from the
stable releases page: https://github.com/AppGuy77/lymow-toolkit-downloads/releases/latest


- Fixed: with two or more zones and a cross-cut pass, the second zone painted both colors at once — the crossing color now ends exactly where a zone ends (any number of zones, single-mower and Fleet Mode).
- Fixed: the camera reconnects by itself in every link mode — WiFi only waits for the mower's WiFi signal (at least -70 dBm), 4G only retries every 5 seconds; Remote, Overview and grid cameras alike.
- New: Home Assistant push notifications for every move the mower makes and every action the Toolkit takes, with Pause / Resume / Dock / Cancel / Clear error buttons on the notification — on automatically with Publish to Home Assistant (Settings → Home Assistant → Phone notifications). Each event is also a Home Assistant event entity.


This beta channel updates independently of the stable Toolkit; report anything odd on the beta repo's Issues page.
