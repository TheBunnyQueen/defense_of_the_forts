# Defense of the Forts
*_A Dota 2 mode that answers the question: What if TF2 was a MOBA?_*

## Introduction
As someone who has spent countless hours playing both games, I've always had the interest of combining the two to see what would happen, specifically TF2 classes, art-style and feel into Dota 2's items and mechanics.
I would not have created a GitHub repository if I did not intend this to be a community-driven, high-scale project. Realistically, not many people will work on it, but I'm counting on you to help me make this more than just a mere mod - a true homage to two great games. What I mean by this is that I intend to import character models, materials, particles, voice-lines and soundscaping from TF2's source files, making a TF2 skin for the original map, "Roboshan", and much, much more. In the end, I want this to feel like almost more like a TF2 mod than a Dota one, except for the mechanics and such.
As described above, I want this to be a very high-fidelity mod, so whenever you read the word "re-modelled" assume that is not limitted to switching models, but instead making all cosmetic changes possible in order to make whatever is being re-modelled look and feel great.

## Gameplay
In total there would be 18 heroes; one for each class of each color. Players may choose from the pool of heroes only classes that correspond to their colors (Radiant is Red and Dire is Blu), and there would not be a banning stage at the beginning of the match seeing as there would only be 9 heroes to choose from.
As any normal game of Dota, heroes are expected to farm and become strong to destroy the enemy's Ancient, which in this case would be re-modelled to be a Nuclear Silo or some such TF2-esque nonsense we all know and love. Creeps would be remodelled to be Mann-vs-Machine robots, having their high-lights recollored to match whichever side they spawned from. Melee creeps are Robo-Scouts with bats and ranged creeps are Robo-Scouts with scatterguns (creative, I know). Siege creeps would likely be re-modeled to be either tanks or payloads outfitted with a cannon, or just to be either Robo-Demoman or Robo-Soldier.
As mentioned previously, the map will also be out-fitted with a TF2 terrain, changing the Radiant to look like a Red base (with a rural look) and changing the Dire to look like a Blu base (with an industrial look).
As I have teased, I also intend to have Roshan fully re-modelled with a brand new model and soundscape as Roboshan, a huge mechanical beast in the image of Roshan, but with the MvM twist.

## Road-map
In order to power through this undertaking, we must understand what must be done. The tasks ahead of us are as follows:
+ Make each of the classes by re-modelling overriden heroes, overriding voice lines with original TF2 voice lines, and coding in their abilities.
    + Scout
    + Soldier
    + Pyro
    + Demoman
    + Heavy
    + Engineer
    + Medic
    + Sniper
    + Spy
+ Re-model creeps.
+ Make the TF2 terrain.
    + Create tile-sets containing TF2 textures.
    + Make new props to detail the world.
    + Change the soundscaping and particles to match.
+ Make Roboshan.
    + Make model.
    + Make/import textures.
    + Make animations.
    + Sounscape.
    + Make new particles for abilities.
+ Re-model wards to fit the TF2 aesthetic, preferably with an imported asset.

## Pipe Dreams
These are nice-to-haves that would definitely improve the quality of the mod, but are either too much work, have a monetary cost involved or both, since these are all things I would not be able to do alone.
+ Make the Delivery Drone Delux, a courier in the style of the Egineer's buildings.
+ Make new art for all of the Dota 2 items to better fit the TF2 aesthetic.
+ Give the MvM treatment to all jungle creeps as opposed to only Roboshan.
+ Hire Ellen McLain to voice an Administrator announcer and mega-kill pack for the mod. (This is by far the least likely, but I'd be willing to pay from my own pocket to see it happen)
    + As a bonus on top of what's already highly unlikely to happen, hire Angee Salazar to record voice lines for Miss Pauling for the announcer pack.
+ Hire the original voice actors to make brand new lines for the game (for events such as buying a Blink Dagger)

## Instructions and Setup
If you've read this far and are interested to participate in the project, here's how you can download a working copy of the source files to start working at it.
There are two ways of doing this, a simple yet incomplete way, and a more complicated yet complete way.

Before any of the following steps, make sure you have both Dota 2, Dota 2 Workshop Tools DLC and Team Fortress 2 installed.

### The Easy Way
Simply download the repository as a .zip file and extract the "content" and "game" folders to your Dota 2 game files location, most commonly located at C:/Program Files (x86)/Steam/steamapps/dota 2 beta/. The extraction should merge these folders with the correponding folders in the target location and automatically create the defense_of_the_forts addon in the Custom Game section of the Workshop Tools when you open them.
This way is quick and simple, however whenever there's an update to the main branch of the project you will need to re-do this step in order to merge the current working version with your own work.

### The Complicated Way
This method requires that you either have Git or SVN installed.

Check-out a copy of this repository into a separate project folder (this way you don't version your entire Dota folder). Move the "content" and "game" folders into your Dota 2 game files location. The next step is platform dependant.

#### Windows
Run Command Prompt as an administrator and execute the commands:

<code>mklink /J "/Path/To/Project/Folder/content/dota_addons/defense_of_the_forts" "/Path/To/Dota/Files/content/dota_addons/defense_of_the_forts"</code>

<code>mklink /J "/Path/To/Project/Folder/game/dota_addons/defense_of_the_forts" "/Path/To/Dota/Files/game/dota_addons/defense_of_the_forts"</code>


#### Linux and MacOS
Open the terminal and run the following commands:

<code>ln "/Path/To/Dota/Files/content/dota_addons/defense_of_the_forts" "/Path/To/Project/Folder/content/dota_addons/defense_of_the_forts"</code>

<code>ln "/Path/To/Dota/Files/game/dota_addons/defense_of_the_forts" "/Path/To/Project/Folder/game/dota_addons/defense_of_the_forts"</code>


We do these steps to ensure separation between the versioned project folder and the unversioned dota files. I know it would have been better to do it the other way around (create the links in the Dota folder as opposed to moving the original folders there), but the Workshop tools can't deal with links while Git and SVN can. If this feels too finicky, I understand if you opt to do the easy way. If you have tried this way and have not succeeded, even if you have followed every step correctly, I recommend you do it the easy way instead.

## Recommended Downloads

<a href="https://gamebanana.com/dl/468817">GCFScape v1.8.6</a>