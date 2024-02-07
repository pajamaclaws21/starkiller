# starkiller
JSON data files for Starkiller.

The goal of this project is to make a gacha game completely based on JSON data that is easily accessible and modifiable. Anyone can display the data, however they want! 

## Battle Note
Blissful has advantage over Melancholic, Melancholic over Indignant, and Indignant over Blissful.
Anodyne has no advantage.

Action Types:
ATTACK - A (Fields: Advantage, Attack Type, Target Number)
BUFF - B (Fields: Target Number) - Can only target Allies
DEBUFF - Db (Fields: Target Number) - Can only target Enemies
CHARGE - C - Increases Acumen
APTITUDE - Ap (Depends on type) - Only usable when Acumen is full

Attack Type:
MELEE - M
RANGED - R 

Advantage:
NEUTRAL - Neu - Doesn't deal Advantage damage
EMOTIONAL - Emo - Does deal Advantage damage

Target Number:
RANDOM - R1 or R2 - Targets random enemies
TARGET - T1-3 - Allows caster to select enemies

## Modding
To add a character, add their JSON to characters.json. Images should be 1024x1024.

## AI Ethics Stuff
This project uses Bing's Image Creator to generate images for characters. Therefore, they cannot and should not be used commercially. This is a side project.