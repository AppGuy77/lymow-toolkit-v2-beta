Lymow Toolkit v2.5.2-beta

**Beta on its own download channel** — recommended for now to people running two or more mowers. It installs
over your current Toolkit (sign-in, maps, settings and history are kept). To go back, install the latest stable release from the
stable releases page: https://github.com/AppGuy77/lymow-toolkit-downloads/releases/latest

Everything below is a change from v2.5.1-beta.


- **Away access heals a dropped key on its own.** If the relay stops accepting this Toolkit's key while the mark beside the switch says **Address in use by another Toolkit on this account**, the Toolkit now registers its key again at once, and then every 15 minutes for as long as that lasts, so the away link should come back by itself.
- **The camera grid should no longer get stuck after a location change** (rotation ignored, cameras silently stopped, Close doing nothing).


## Away access heals a dropped key on its own

The relay now lets a key hold only the address it is registered for. That closes a gap where one
registered Toolkit could have requested another user's address. It also means a Toolkit whose own key has
dropped off its address, which can happen when more than eight devices have been registered on one Lymow
account, is refused with the same message as a genuine second device: **Address in use by another Toolkit
on this account**.

The Toolkit cannot tell those two apart, so it now handles both the same way: on the first refusal it
registers its key again at once, and then at most every 15 minutes for as long as the refusals continue.
For a dropped key that brings the away link back within seconds. For a real second device on the account
it changes nothing, and the mark keeps saying which Toolkit holds the address.

## The camera grid should no longer get stuck after a location change

When you change location while the camera grid is open, the grid closes and reopens for the new
location's mowers. If the old grid finished closing after the new one had already opened, the new grid lost
its state: it ignored phone rotation, its cameras stopped without saying so, and its own Close button did
nothing. The old grid now cleans up only its own cameras and leaves the new grid alone.
