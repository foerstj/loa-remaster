# LoA remaster

The original Legends of Aranna map, remastered.

## What I did

This map is re-buildable and editable. I opened & saved every region in Siege Editor v1.7. The dsmap file can be rebuilt using the batch scripts, provided you have the folder structure of Dungeon Siege, TankCreator and gaspy.
- SE saves the "required_level" attributes for multiplayer start positions with an "i" in front, which however breaks the level requirement.\
  This is fixed during build by a gaspy script.
- Renamed the map so there are no conflicts with the original map.\
  The internal name is *world/maps/legends-of-aranna*.\
  The generated file name is *Dungeon Siege/DSLOA/Legends of Aranna.dsmap*.\
  The ingame name is *Legends of Aranna (remastered)*.

## What I did (revisit)

The "revisited" map variant is based on the remaster, with these changes applied:
- Brushed up plants that had default scaling / orientation
- Renamed map ingame to *Legends of Aranna (revisited)*.

## How to build

GasPy repo: https://github.com/foerstj/gaspy

- Put TankCreator and gaspy on the same folder level as your Dungeon Siege installation. Basically in the upper folder, you should have a "Dungeon Siege" folder, a "TankCreator" folder, and a "gaspy" folder.
- Put this repo as "Bits" into your personal Dungeon Siege LoA folder (where the savegames & screenshots are).
- Go into your Dungeon Siege installation folder and open CMD there.
- %USERPROFILE%\Documents\Dungeon Siege LoA\Bits\build.bat

## Attribution

This map was created by Gas-Powered Games, not me. I'm just doing minor changes here.
