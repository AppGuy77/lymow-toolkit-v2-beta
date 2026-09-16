Lymow Toolkit v2.4.3-beta

**Beta on its own download channel** — recommended for now to people running two or more mowers. It installs
over your current Toolkit (sign-in, maps, settings and history are kept). To go back, install the latest stable release from the
stable releases page: https://github.com/AppGuy77/lymow-toolkit-downloads/releases/latest


- **Away-from-home access now works in Home Assistant and Docker too.** The v2.4.2 switch to the new away-link infrastructure needs the built-in ssh client, which the Home Assistant and Docker containers did not include — so away access there showed "No address yet". The containers (and minimal Linux installs) now ship it, so your permanent link connects on every platform. Nothing to set up — sign in and it reconnects on its own.


This beta channel updates independently of the stable Toolkit; report anything odd on the beta repo's Issues page.
