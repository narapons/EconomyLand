## Poggit

https://poggit.pmmp.io/ci/narapons/EconomyLand/~


## EconomyLand

EconomyLand provides your players a land protection system. If the player buys land, the land will protected for the bought player.

### Commands

List of commands :

`/land <list | here | move | invite | invitee | give | buy | whose>`

`/landsell <here | land number>`

Instructions for /land command :

`/startp` : Sets the start position.

`/endp` : Sets the end position.

`/land list [page]` : Shows the list of land.

`/land here` : Shows the land where you are standing on.

`/land move <land id>` : Move to land.

`/land invite <land id> <invitee>` : Invites player to your land.

`/land invitee <land id>` : Shows the list of invitee in land.

`/land give <land id> <player>` : Give the land to other player.

`/land buy` : Buys land.

`/land whose <keyword>` : Queries the list of land-bought players.

`/landsell here` : Sells land where you're standing on.

`/landsell <land id>` : Sells land by land ID.


If you use `/startp` and `/endp` commands you'll set the position where you'll buy. Then, you can use `/land buy` command to buy the land.

The `land id` is the land ID that shows in `/land list` command.

EconomyLand will ignore Y axis. It will protect all of Y axis which is in area.


### Permissions

```
economyland.*
economyland.land.*
economyland.land.modify.others
economyland.land.modify.whiteland
economyland.land.modify.others
economyland.landsell.*
economyland.landsell.others
economyland.command.*
economyland.command.startp
economyland.command.endp
economyland.command.land.buy
economyland.command.land.move
economyland.command.land.list
economyland.command.land.whose
economyland.command.land.give
economyland.command.land.here
economyland.command.landsell
economyland.command.landsell.here
economyland.command.landsell.number
```
