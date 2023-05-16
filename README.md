# Octorich

**Short description**: this mod changes all enemy entities (except friendly NPCs) to reward ten times more experience, job points, leaves (money) and *Collect* outcomes.

**Long description**: this is an easy-mode mod made to enable single-session roguelite playthroughs and to reduce the amount of grinding required for any challenge runs.

## Support

To get help, discuss the mod or just to say thanks, join my Discord server at https://discord.com/invite/5sXXcwPCSP !

## Installing

1. Download the latest release from https://github.com/tukkek/octorich/releases .
2. Place the file on your game's installation `Paks` folder:
 * Default location on Windows: `...\Documents\My Games\Octopath_Traveler\...\SaveGames\`
 * Default location on Proton: `.../steamapps/common/OCTOPATH TRAVELER/Octopath_Traveler/Content/Paks/`

### Compatibility

* Intended for use with the Steam version of the game.
* Does not require a new save game.
* Compatible with all mods that don't also modify `EnemyDB` files.

## Rationale

Octopath Traveller is a JRPG with unparalelled replay-value and combat depth (comparable only to Saga and Bravely games) but these qualities are diametrically opposed to the incredible amount of artificial padding put into the campaign. As one reviewer puts it:

> I know that grinding up the level ladder is, to an extent, part and parcel of the JRPG's DNA but Octopath Traveller suffers from such a debilitating mid-to-late game slump that, even if I did have the time to put in another 30-40-odd hours to even stand a chance against that last boss, the foundations that hold up its core levelling system just simply don't run deep enough to support it for that length of time.
> 
>  I love Octopath Traveller's battle system. I really do. Just not enough to do what it's clearly asking of me.
>  
>  https://www.rockpapershotgun.com/octopath-traveler-pc-review

NPCs were not altered simply because of how many of them there are, with no obvious major benefit to improving their rewards.

### Analysis of the vanilla economy

I spent a couple hours testing with the game open and crushing numbers, which informed my decision to create this mod: 

1. Gear is huge in OT (you can go from 10 to 100 damage with one decent weapon upgrade). The math showed me it would take me 20-30 hours grinding level +0 to +10 encounters to buy all major upgrades for a party of 4 (not 8) - and by "major upgrades" I mean not going for all best-in-slot items but a more reasonable, cost-efficient approach.
2. If not to grind gear upgrades, grinding 10 levels worth of experience, again from +0 to +10 areas, would have taken me 7 hours (calculated between -5 and +5 to account for mid-grind power gain).
3. Even if I were to grind a factor of that time, the most time-effective area to do it had exactly 1 variety to enemy formation (hardly content suited to hours of play)...
4. Going to a level +10 area resulted in about a 20% increase in experience rewards, while fights took twice as long - and roughly 0% benefit to money rewards in most cases.

Note that these were based on a decently-advantageous area for farming rewards - perhaps not the best possible one but far from poor as a grinding spot. While having even one Merchant in your party would bring those times-down three-fold, any such bonuses were disconsidered in favor of challenge-friendly base numbers. (Not to mention 10 hours of farming may be much less than 30 but it's still a lot)...

Another reviewer has this to say about the pacing and progression in OT and, with these hard-numbers to rely on, I'm inclined to agree:

> It feels like an artificial lengthening of the campaign and becomes irritating after many hours https://gamecritics.com/jeff-ortloff/octopath-traveler-pc-review/

Many players will disagree that the game requires any grinding at all but that is besides the point, since my main concern is with the possibility of leveraging the game's replay-value and great depth to do interesting one-shot challenges, randomized play-througs... without needing the time-investment, dedication and planning of a competitive speedrunner. Hopefully this mod could enable many casual players to try new things that they would otherwise consider too difficult or time-consuming to even begin to try!

### A public apology to the Octopath community

I would like to apologize to absolutely everyone on Earth (and the International Space Station) for not making this a x8 increase globally but just adding a 0 to hundreds of fields was simply easier to achieve. If anyone wants to help remake the mod with a JSON-based pipeline this time around let me know so that The Right Thing™ can be done.

## Credits

* Squeenix and Acquire for creating the game https://store.steampowered.com/app/921570/OCTOPATH_TRAVELER/
* Ben for the Octomod Editor https://github.com/ItsBenOnceAgain/OctomodEditor/
* UnrealPak https://github.com/allcoolthingsatoneplace/UnrealPakTool
 * Note that newer version don't work well with Ocotpath, try an older one instead such as https://github.com/allcoolthingsatoneplace/UnrealPakTool/issues/10#issuecomment-1001258117 .
