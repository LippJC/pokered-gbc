# Pokémon Red and Blue [![Build Status][travis-badge]][travis]

<<<<<<< Updated upstream

=======
Changelog of Bug Fixes:
- 100% Accuracy Issue: All guarantee-hit moves had a 255/256 hit rate.
- Focus Energy Glitch: This one is a doozy.  The original code had a bug so Focus Energy would
actually 1/4 the crit rate.  This fix restores that value, however, if left unchecked, several
Pokemon with high speed stats would have an effective 100% crit rate.  A cap of 50% was
instituted to prevent this.
- Dual-Type Effectiveness Misreported: Dual-Type Pokemon would have effectiveness reported
incorrectly.  This has been resolved.
- HP Drain Moves Should Cancel Substitute: It didn't, now it does.
- PP Restore Bug: For some reason, this item didn't account for extra PP from PP Ups used.
- Nidorino Sound Bug: The audio on the intro was for a Nidorina.
- Prof Oak Poke Ball Text Bug: Fixed a line of dialogue that overwrote instead of scrolling.
- Route 8 Gate Guard Bug: When stopped by the guard, the player wouldn't look at the guard.
- Game Corner Hidden Item Bug: One hidden item was supposed to have 40 coins instead of 20.
- Slot Machine Issues: The "lucky" machine was bugged and could sometimes not appear.  Also the
ability to stop the machines on a "7" or a "BAR" was bugged.  Probably by design, considering it's
gambling, but it's been changed to the same as the other machines.

Changelog of Sprites:
- Articuno Back Sprites
- Many Front Sprites were altered to pick the best version of the Red or Green version.
1 or 2 Spaceworld sprites were used, but the intention is to retain the original art style.
- Used several adjusted sprites from https://github.com/Vortyne/pureRGB.  Thanks Vortiene!

Changelog of Routes:
- Adjusted all areas to make <5% rare Pokemon have a >5% encounter rate.
- Altered all route specific version-exclusive Pokemon to be (generally) included on said routes.
- Heavily altered the Safari Zone to make the rare Pokemon specific to each area.
	Center: Pinsir
	East: Scyther
	North: Tauros
	West: Kangaskhan / Chancey


Changelog of Pokemon:
- All trade evolution Pokemon were altered to evolve around the same levels as starter Pokemon
(16-18, and 32-36).  Move levels might have been altered slighlty around that.
- All 

- NOT IMPLEMENTED YET: Design / adjust some of the worst sprites (Moltres / Poliwrath line
Machamp line / Raichu)  
- Title Screen Altered to "Dx Version" This is a placeholder.
- NOT IMPLEMENTED YET: Mew - Vermilion Truck Push (learn scripting)
- NOT IMPLEMENTED YET: Oak Fight Enable
- NOT IMPLEMENTED YET: Pokemon Dream Sequence / TPP Fight
- NOT IMPLEMENTED YET: Figure out scripting for Starters (post game)
- NOT IMPLEMENTED YET: Figure out scripting for Eevee (post game)
- NOT IMPLEMENTED YET: Figure out scripting for Fossil (post game)
- NOT IMPLEMENTED YET: Figure out scripting for Fighting Dojo Pokemon (post game)
- NOT IMPLEMENTED YET: Menu Driven Choices (Yellow Sprites / Certain RG sprites) (see PureRGB)
- NOT IMPLEMENTED YET: Battle Mechanics? (Maybe Menu Driven?)
- NOT IMPLEMENTED YET: Total retooling of Pokemon locations (Maybe Menu Driven?)








This is a disassembly of Pokémon Red and Blue.

It builds the following ROMs:

- Pokemon Red (UE) [S][!].gb `sha1: ea9bcae617fdf159b045185467ae58b2e4a48b9a`
- Pokemon Blue (UE) [S][!].gb `sha1: d7037c83e1ae5b39bde3c30787637ba1d4c48ce2`
- BLUEMONS.GB (debug build) `sha1: 5b1456177671b79b263c614ea0e7cc9ac542e9c4`

To set up the repository, see [**INSTALL.md**](INSTALL.md).


## See also

- **Discord:** [pret][discord]
- **IRC:** [freenode#pret][irc]

Other disassembly projects:

- [**Pokémon Yellow**][pokeyellow]
- [**Pokémon Gold/Silver**][pokegold]
- [**Pokémon Crystal**][pokecrystal]
- [**Pokémon Pinball**][pokepinball]
- [**Pokémon TCG**][poketcg]
- [**Pokémon Ruby**][pokeruby]
- [**Pokémon FireRed**][pokefirered]
- [**Pokémon Emerald**][pokeemerald]

[pokeyellow]: https://github.com/pret/pokeyellow
[pokegold]: https://github.com/pret/pokegold
[pokecrystal]: https://github.com/pret/pokecrystal
[pokepinball]: https://github.com/pret/pokepinball
[poketcg]: https://github.com/pret/poketcg
[pokeruby]: https://github.com/pret/pokeruby
[pokefirered]: https://github.com/pret/pokefirered
[pokeemerald]: https://github.com/pret/pokeemerald
[discord]: https://discord.gg/d5dubZ3
[irc]: https://kiwiirc.com/client/irc.freenode.net/?#pret
[travis]: https://travis-ci.org/pret/pokered
[travis-badge]: https://travis-ci.org/pret/pokered.svg?branch=master
