# DBFZ CE 1.6 (Goku SS4 DAIMA Update)
As the game continues to receive updates, it's important that I ensure the mod **continues** to behave as intended. 

Just like with Labcoat, Goku SS4 DAIMA never existed in 3.5, therefore him being a playable character in CE is totally out of the question.

In order to render him unplayable, it was necessary for me to update the mod again. 

With the release of 1.6, CE has also received a few new changes, some more significant than others. I ask that you please read the patch notes below.
## System
- **Removed S macro**

The inclusion of this feature has always been the most conflicting decision I've had to make for the mod, and I've now decided to take a final step back from it.

Although it's something you can be for or against, high level CE proved beyond any reasonable doubt that it had a significant impact on the way neutral, offense and defense were played, which creates too large of a gap between the mod and the original 3.5.
I won't disagree that its removal makes playing both versions at once more difficult, but as DBFZ (unfortunately) continues to stray further away from the game it once was, I find it even more urgent to **preserve this gameplay aspect** of older seasons.

However, I made sure resources concerning the application of manual moon jump are shared on the **[Dustloop wiki](https://www.dustloop.com/w/User:Pato/DBFZCE/Universal_Strategy#Moon_jump)** for everybody to learn.

## Characters
Even though I strive for the mod to be as accurate to 3.5 as possible, I've taken the liberty to give characters a few bug fixes, small improvements and QOL changes to round up their identities and slightly enhance their overall feel.

I tried to be very careful when letting these in as I did not wish to go with changes that could make characters feel too different from how they once played.

These are also mostly changes that were already present in retail DBFZ and came into existence just shortly after 1.27

###  SS Goku
- Expanded 2S hitbox downwards

###  SSB Vegeta
- Fixed the bug that rendered him unable to 2H after deflected ki-blasts (5S and 2S)

###  Frieza
- Made 2H strike property

###  Bardock
- Can now perform j.L twice in a combo

###  Android 16
- Increased attack level for 5L

###  Hit
- Can now gatling 5L into itself

###  Jiren
- Fixed the bug that let 214S beat throws and DR

###  Base Goku
- Can now perform 214S with 22S

- System text will show up for his spirit bomb levels

- Pressing any attack button will perform a Kaioken finisher if no more follow-up options remain

###  Fused Zamasu
- Expanded 5S hitbox downwards


# FAQ

## What is this?

**Dragon Ball FighterZ CE (Community Edition)** is a modification of the current DBFZ build that attempts to retrofit the last season 3.5 patch (v1.27) into it, featuring some of the overall QOL changes that you'd expect from newer versions and **rollback netcode**.  
Although it'd be disingenuous to call this an exact replica, there have been no intended changes with the idea of "rebalancing" the original 3.5 game. The purpose of this project is to be as faithful to the core identity of that version as possible, within what's reasonable and/or best suited for the gameplay experience.

## Why does this exist?

Throughout its history, DBFZ has seen drastic gameplay changes in between what the community at large call "seasons". From the very beginning up until 3.5, although many of the dev team's decisions to fine-tune the game proved to be controversial, these were usually changes that still respected its unique core identity and fell into the category of what most players would call sensible.

This, however, shifted drastically with the massive balance overhaul that came with [v1.28](https://www.youtube.com/live/f0BuIZYUgLg?feature=shared), which marked the beginning of season 4. On paper, although some of the rework ideas had potential, the fundamental basis of many aspects of previous versions of DBFZ (routing, defense, movement, neutral, etc.) changed very significantly, turning it into a much more volatile and homogenized game.

To make matters worse, this new design philosophy adopted all of a sudden by the devs would serve as the basis for [**every new patch**](https://dustloop.com/wiki/index.php?title=DBFZ/Version_History) following v1.28, doubling down on the majority of its ideas and making the game with each update more and more unrecognizable from what it was before. It's no surprise that a lot of seasoned DBFZ players have appropriately used monikers like "YOLO design" or "party game" to describe all of the patches that have released ever since that fateful day.

The release of **Lab Coat Android 21** shortly after the beginning of season 4, arguably one of the most unbalanced characters in modern fighting game history, did not do any favors to [the look of the game](https://x.com/CEOGaming/status/1532010498702680067?t=KNzObCTlkAMPp-8qRelgcA), embodying some of the absolute worst aspects of the direction the developers decided to take from that point onwards.

Because of the aforementioned reasons and more, **[DBFZCE](https://dustloop.com/wiki/index.php?title=DBFZCE)** was created. To preserve the identity of what DBFZ once was, its significance to long time players and also having it serve as a gateway for new people interested in the game who didn't have the chance to properly experience how it played before.

On top of everything else, due to global circumstances at the time, season 3 as a whole was more undeveloped than previous versions, so the current implementation of rollback netcode to it could prove to breathe new life into the game, incentivizing brand new metas and competition to develop.

## How can I install this?

### Standard installation (Thumbnail links to video tutorial)

[![Install Tutorial](https://img.youtube.com/vi/yCNLSOCb9Es/maxresdefault.jpg)](https://www.youtube.com/watch?v=yCNLSOCb9Es)

Click **[here](https://github.com/VA11Pato/DBFZCE/releases/tag/1.6)** to download the .msi installer! 

### Manual installation

1. Click [here](https://github.com/VA11Pato/DBFZCE/releases/tag/files) to download the individual mod files.
2. Go to your game directory (usually found at `Program Files (x86)\Steam\steamapps\common\DRAGON BALL FighterZ`), then navigate to `RED > Content > Paks`.
3. Create a new folder named exactly `~mods` (don't forget the tilde `~`!).
4. Extract the contents of the DBFZ CE 1.5 folder into the `~mods` folder you just created.
5. Go back to the main game directory and then go to `RED > Binaries > Win64`.
6. Find `RED-Win64-Shipping.exe` (with the DBFZ icon). Right click it and make a copy.
7. Rename the copy to `RED-Win64-Shipping-eac-nop-loaded.exe`.

> This disables Easy Anti-Cheat (EAC) when launching the game with this shortcut.

8. Create a new shortcut to that file so you can easily launch the game.

An easy way to check if you're on the mod is seeing if there's any purple theming present in the UI. 

### ⚠️ WARNING: Do NOT use Unverum to install the mod

As it stands right now, some of the files Unverum patches on top of the original game can cause UE4 Fatal Error issues for players, being specially prominent during online play. It's best advised you just follow the instructions above in order to play.

If you're still **running into Fatal Error issues** even after having installed manually, make sure the UE4 Prerequesites are properly installed.:

1. Go to: `Steam\steamapps\common\DRAGON BALL FighterZ\Engine\Extras\Redist\en-us`
2. Run `UE4PrereqSetup_x64.exe`
3. Install any needed prerequisites and restart your PC.

## Why 3.5? Why not season 1, season 2 or early season 3?

The decision to choose 3.5 to be the "community edition" was done due to the following reasons:

- It features every playable character in DBFZ outside of Labcoat 21.

- It has the most well defined roster and concepts behind how it wants the characters to play.

- It has (arguably) the best character balance out of any version.

- It has the best system balance between offense and defense (although some of the ways that it achieves this may be put into question).

- Compared to season 1 or 2, it's significantly easier to retrofit into the current base of the game. 

- It was made right before the start of S4, so it's still relatively fresh in a lot of players memories.


## What did you do with Labcoat, then?

### ❌ Labcoat does not exist in Season 3.5

Attempting to pick her results in a dummied-out character.

### Why not keep her?

- She's universally agreed to be ridiculously overpowered to the point of being one of the only characters in a modern fighting game to be banned from a major.
- Even the Season 5/5.5 version of her which is considerably nerfed would still be by far the best character in the game as those seasons were balanced around her (and S4 Vegito).
- This mod wishes to be as faithful as possible to DBFZ S3.5, faults and all. Labcoat being a later addition means she would have to be retrofitted to this version's balance and become a "community created" character.

## What's different from CE compared to 3.5?

Below is a list of the changes that are retained from Season 4 onward, for various reasons: 

- Every move that puts you in an airborne state will attain float properties, without the need to superjump install it. 

- While on Sparking and Limit Break, the Sparking timer won't ever run out in the middle of a combo, ensuring it remains active until the end of it.  

- Vanish is invincible from the beginning of the move if the opponent is performing a Vanish. This change is mostly insignificant to this version as Vanish Guard Cancel is not present in it.

- Reduced damage scaling for attacks performed after Super Attacks. This slightly buffs Double Super sequences. 

- Minor QOL fixes or changes from S4 that are largely undocumented

More importantly, many or most of the **S4 hitboxes/hurtboxes** are still being used in the main version of the mod. This is due to altered collision files causing instabilities in the game's rollback implementation. All of these changes were done in v1.28, and they tend to just amount to j.M or C assist hitbox/hurtbox adjustments.

## Why aren't these patched out?

Largely due to DBFZCE's limitations as a "BBscript only" mod, theoretically it would be possible to edit the game's .exe to remove these extra changes, though their overall impact on the game in Season 3.5 is largely negligible, combined with the effort required to remove them and the extra effort it would put into installing and maintaining DBFZCE should the game ever update again, the developer of DBFZCE considered it not worth bothering with. Moreover, some of these more minor changes can overall be considered QOL improvements on top of the base 3.5 game. 

CE's main goal is making 3.5 DBFZ as accessible for all players as feasibly possible, which means retaining the core identity of its roster and system while also easing the process of just booting up and playing.
