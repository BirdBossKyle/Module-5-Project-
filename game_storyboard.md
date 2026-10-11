# Wasteland Run — Project One Storyboard

## Theme and Storyline
**Theme:** Post-apocalyptic survival. After a disaster leaves the region without power and supplies, the player searches nearby ruins for seven supplies. The Raider Leader is hiding in the Command Bunker. Entering the bunker with all seven items wins the game; entering without all seven loses.

## Rooms
1. Survivor Shelter — start room
2. Abandoned Store
3. Clinic
4. Radio Tower
5. Gas Station
6. Ruined School
7. Water Plant
8. Highway Checkpoint
9. Command Bunker — villain room

## Items
- Abandoned Store: Canned Food
- Clinic: Medical Kit
- Radio Tower: Radio Battery
- Gas Station: Fuel Can
- Ruined School: Map
- Water Plant: Water Filter
- Highway Checkpoint: Protective Gear

The Survivor Shelter has no item. The Command Bunker contains the villain and has no item.

## Room Connections
All connections are two-way and match the map and movement pseudocode.
- Survivor Shelter: north to Abandoned Store; east to Clinic.
- Abandoned Store: south to Survivor Shelter; east to Radio Tower.
- Clinic: west to Survivor Shelter; east to Gas Station.
- Radio Tower: west to Abandoned Store; east to Ruined School.
- Gas Station: west to Clinic; east to Water Plant.
- Ruined School: west to Radio Tower; east to Highway Checkpoint.
- Water Plant: west to Gas Station; east to Command Bunker.
- Highway Checkpoint: west to Ruined School.
- Command Bunker: west to Water Plant.

## Ending Conditions
- Win: enter the Command Bunker with all seven items.
- Loss: enter the Command Bunker with fewer than seven items.
- Quit: enter `quit` at the movement prompt.
