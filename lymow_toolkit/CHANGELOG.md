Lymow Toolkit v2.1.7-beta

**Beta on its own download channel** — recommended for now to people running two or more mowers. It installs
over your current Toolkit (sign-in, maps, settings and history are kept). To go back, install the latest stable release from the
stable releases page: https://github.com/AppGuy77/lymow-toolkit-downloads/releases/latest


- Fixed: the Home Assistant add-on filled the disk. Each update built the add-on on your machine from an image it pulled and never removed, about half a gigabyte per version; the disk ran out, Home Assistant stopped offering add-on updates and its database failed with "disk I/O error". The add-on now pulls the ready-made image and Home Assistant deletes the previous version on every update. Free the old images once with `docker image prune -a` from the Home Assistant console.
- New: Advanced Data shows the Toolkit computer's data drive, live, with a red warning under 2 GB and what that stops.


This beta channel updates independently of the stable Toolkit; report anything odd on the beta repo's Issues page.
