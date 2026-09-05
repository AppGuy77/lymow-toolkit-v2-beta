Lymow Toolkit v2.1.5-beta

**Beta on its own download channel** — recommended for now to people running two or more mowers. It installs
over your current Toolkit (sign-in, maps, settings and history are kept). To go back, install the latest stable release from the
stable releases page: https://github.com/AppGuy77/lymow-toolkit-downloads/releases/latest


- Fixed: in Fleet Mode, Settings → Maps showed the mower picked in its selector but Restore, Back up and Download all went to the Overview mower, and the Restore button kept that mower's name. The selector, "Show backups from", the restore-point list, the thumbnail and every button now move together, and the restore lands on the selected mower.
- Fixed: the Remote tab's mini-map, the Overview camera's mini-map and the mow-details thumbnail drew the Overview mower's zones under another mower's position; each now shows the map of the mower it is about.
- Fixed: Copy to other mowers now has its own Mower selector and copies from the mower chosen there.
- New: Settings → Camera. The camera's signal levels are yours to set, per mower and saved on the Toolkit for every device: the WiFi reconnect level (-95 to -65 dBm, was fixed at -70), an optional minimum 4G signal before each 4G retry, the rule Auto uses to leave WiFi for 4G (dropped frames per second or a WiFi signal level, each with its own slider) and the level at which Auto returns. The defaults are what the Toolkit did before.


This beta channel updates independently of the stable Toolkit; report anything odd on the beta repo's Issues page.
