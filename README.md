# Updates: 03/14/24

- NPC actors can be generated and inserted into maps
- NPC actors can have random walk behavior and equipped items have effect in the world (lighting)
- NPC actors can have dialogue interaction with player responses and state-determined branching
- NPC actor behavior can specify random selection of dialogue from a state-determined category
- Dialogue UI panel with text printing effect and user input wired up
- Actors can have 1 of 6 hair styles in 1 of 5 colors with 1 of 3 body skin tones
- Added a random body function to generate random NPC styles
- Added 2 dresses (my daughters insisted) and 1 additional set of clothes
- Added a beard option (simple way to increase variety)
- Reorganized all graphics source files into separate categories with better templates

### Screenshot: Multiple NPCs with Misc Clothes
<img width="1116" alt="Multiple NPCs with Misc Clothes" src="https://github.com/jonmcgill/nochd-progress/assets/13082333/f8767ee8-1cf8-4eed-9d85-4a41d3e1e58b">

### Video: Randomized Actor Styles (Hair/Color/Body)
https://github.com/jonmcgill/nochd-progress/assets/13082333/f3e4558b-2923-4626-8642-bfcc2abf16e3

### Video: Dialogue Panel with Text Printing and User Responses
https://github.com/jonmcgill/nochd-progress/assets/13082333/77d73385-1e20-45db-90f0-467095156b45

### Tasks Completed

- [x] (MS01-NPC) npc can have categories of random dialogue which are decided on interaction
- [x] (MS01-NPC) on turn, process npc item/stat calculations just like player
- [x] (MS01-NPC) more body/hair graphics
- [x] (MS01-NPC) random npc body/hair/beard function
- [x] (MS01-NPC) more basic clothes options
- [x] (Chore) try out some different fonts
- [x] (MS01-NPC) dialogues have a printing effect
- [x] (MS01-NPC) if no npc dialogue, show message that they don't want to talk
- [x] (MS01-NPC) space key to each dialogue panel takes one turn
- [x] (MS01-NPC) Escape key will cancel dialogue
- [x] (MS01-NPC) npc will turn to face player if needed
- [x] (MSO1-NPC) npc dialogue can have init function to determine branch
- [x] (MS01-NPC) npc dialogue branch can have player responses that change branches
- [x] (Chore) reorganize graphics source files into separate categories

# Updates: 03/09/2024

- Added environment tile animation frames (water and campfire)
- Added actor tile animation frames (body + equipment)
- Added ability to dynamically change tilesize (like when going in small rooms)
- Updated UI panels style and layout (just a little bit)
- Fixed light source collection (storing with map chunk data now)
- Started work on NPC actors (create/render/items/dialogue)

### Showcase

`Night near the house. NPC walking around with a torch. Tiles change size when going indoors.`

https://github.com/jonmcgill/nochd-progress/assets/13082333/1c8cceea-89dd-4d75-917a-65b9beab0619

`Morning light. Walk by the shore. Water animation.`

https://github.com/jonmcgill/nochd-progress/assets/13082333/47365cc8-d00e-494a-b65f-28d4f05c3ae3

