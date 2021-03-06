# It's A Trap!

###### Required Scripts
* [Token Collisions](https://github.com/Roll20/roll20-api-scripts/tree/master/Token%20Collisions)
* [Vector Math](https://github.com/Roll20/roll20-api-scripts/tree/master/Vector%20Math)

This is a script that allows GMs to quickly and very easily set up traps on
the GM layer, and detect when tokens on the objects layer move over them. This
trap detection even works for tokens moving by waypoints.

### To set up traps:

Place the token for your trap on the GM layer. Give it the cobweb status marker.

By default, traps will only affect characters on the ground (ones that don't
have a wing or angel status marker). To have a trap also affect flying
characters, give it the wing or angel status marker.

By default, trap tokens won't appear when they are activated. If you would
like the trap to become visible to the players when it is activated, give it
the bleeding eye status marker.

### To set off traps:

If a token moves across a trap at ANY point during its movement, the trap will
be activated!
