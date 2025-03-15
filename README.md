# **Description**
This mod (included in the post) does two things using look-up tables for each ammo type:

- Enemies will have their ammo types adjusted to better fit their rank and difficulty (avoiding AP ammo from NPCs of early ranks)
- **Ammo changes are made when any NPC comes online (within player's online radius)**
- Companions **and important NPCs** are skipped to avoid overwriting your ammo choice for them
- Sin and UNISG have additions that make them more prone to using AP for difficulty purposes (UNISG being near guaranteed)
- **[NEW]** When doing Radar/Brain Scorcher and the Brain Scorcher has NOT been turned off, all non-Master/non-Legend Monolith in Radar and the Scorcher will use FMJ ammo
  - The script will return to normal logic for Monolith in these areas after the Scorcher is disabled
- **[NEW]** When doing Brain Lab and the Miracle Machine has NOT been turned off, the Sin that spawn protecting the Miracle Machine will be forced to use FMJ ammo as it is an early-game dungeon
  - The script will return to normal logic for Sin in the Brain Lab (for those who defend it in "Mortal Sin") after the Miracle Machine is disabled
- **[NEW]** After the Brain Scorcher and Miracle Machine are turned off, all Southern areas will have their negative rank modifiers decreased by 1 to help simulate more experienced Stalkers entering the Zone now that the North has been opend
- **[NEW]** Certain factions will ignore negative rank modifiers from the level they are in if their faction has a major base in said level (i.e. Duty in Rostok/Freedom in Army Warehouses)
- Credit to Arti for the similar function in ArtiBalls


# **Reasoning**


GAMMA is pretty reliant on the progression out of hobo phase - earning your armor and loot as you play in order to progress. One of the pain points that comes with GAMMA is that there is rarely an in-between phase between "hobo" and "armed to the teeth". And, with how players tend to "overgear" for Brain Scorcher, the sense of progression outside of doing questlines ends pretty quickly after Brain Scorcher.

When it comes to doing Brain Scorcher, there is one issue that rears its ugly head - Monolith is heavily geared towards/always use AP ammo. For difficulty reasons, this is understandable. However, for Mono to be using AP ammo this early in the questline is not great for players. With them using ammo that penetrates nearly all armor until Heavy or Exo, players feel the need to "over-prepare" for something that is technically early mid-game. And since you don't have access to the North, your artefact selection is rather thin unless you spend hours farming artefacts and mutants for parts. Essentially, most of your progression journey is done before you even reach the halfway point.

With this mod, this will allow mid-game progression to not feel way too tough, as well as allow the BR stat on Medium and Heavy armors to matter for a bit longer until early late-game with Sin and UNISG.
