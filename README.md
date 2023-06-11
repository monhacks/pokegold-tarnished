# Pokémon Tarnished Gold and Silver

This challenge ROM hack is a modification of the vanilla Pokémon Gold and Silver where instead of gaining experience points from battle, Pokémon will *lose* experience and levels.

The challenge was debuted with version `0.3.8` on [Raz][raz-twitch] and [Naircat's][nair-twitch] **Weekly Wednesdays** variety stream where they successfully attempted to reach and defeat the Elite Four! Can you make it to the Elite Four as your Pokémon get weaker every battle? Are you willing to challenge Red on Mt.Silver?

<p align="center">
<img src="https://media.discordapp.net/attachments/796754499649667083/1117567403279253614/Screenshot_2023-06-11_143225.png?width=270&height=243"/>
<img src="https://media.discordapp.net/attachments/796754499649667083/1117567403551899778/Screenshot_2023-06-11_143145.png?width=270&height=243"/>
</p>

## Changelist

- Pokémon lose EXP whenever they participate in battle.
    - This **includes** if they have fainted. A fainted Pokémon is considered part of the active battle set to lose experience points after defeating an opponent Pokémon.

- When a Pokémon's experience points reach the lower threshold of their current level, they will level *down*.
    - A sad "fanfare" will play indicating the loss of a level during battle.
    - Leveling down reduces stats of your Pokémon. If your current HP happens to be higher than the new max HP for your lowered level, it will remain unchanged until the Pokémon has enough damage inflicted on it, or is healed at a Pokémon center.
    - Leveling down is limited to `Level 2` similar to how the vanilla games limit you to `Level 100`.

- Pokémon do not learn moves from leveling down.

- Pokémon do not evolve (or de-evolve) from leveling down.

- EXP boosting items or conditions now contribute to experience *loss* instead of gain.

- RareCandy *lowers* a Pokémon's level by 1. (Nice Try)

- The DayCare couple is now absolutely terrible at their job, causing Pokémon to lose experience per step instead of gaining it. (Go visit them to see how they feel about this!)

- Pokémon stats screen now shows experience points remaining to next lowered level.

- Toggle Background Music in the `OPTIONS` screen by using the `MUSIC` option.

- Version is displayed on 'New Game/Continue' screen

## Known Issues

- Sad fanfare is played when a new move is learned.

- Gfx Bug when Pokémon's HP is temporarily above the MaxHP due to level down.

## Contributors

### Raz [*Twitch Channel*][raz-twitch] | [*Github Page*][raz-gh]
- Game Logic
- Initial Playtester

### Naircat [*Twitch Channel*][nair-twitch] | [*Twitter Page*][nair-twitter]
- Title Art
- Initial Playtester

##

This ROM hack was built using the hard work from the [**Pokémon Gold and Silver Decompilation Project**][pokegold]!<br>
To set up the repository for yourself, see [INSTALL.md](INSTALL.md).

[pokegold]: https://github.com/pret/pokegold
[raz-gh]: https://github.com/raz-a
[raz-twitch]: https://www.twitch.tv/razstrats

[nair-twitch]: https://www.twitch.tv/naircat
[nair-twitter]: http://twitter.com/naircatt