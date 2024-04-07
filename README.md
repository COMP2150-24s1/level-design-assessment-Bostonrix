[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Boston Rix
### Student number: 46618538


## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery
In the game, the discovery aspect of the player experience unfolds mostly within the tutorial stage (section 1). Through following the Assignment Outline, Mechanics and dynamics were introduced individually, and in a safe manor as to not complicated the experience of the player. The first section of the game consisted of a relatively safe linear experience of the games features and dynamics.
Through this, the player is provided the chance to grasp how their player interacts with the obstacles within the world.

### 1.2. Drama
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 

### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?

### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?

## 2. Core Gameplay
### 2.1. Acid
![Storyboard of the acid as a hurdle](DocImages/acidStory.png)
The player start by learning that acid respawns the player, rather than just damages, as this is the closest obstical from the respawn point, and thus an optimal first obstical.
### 2.2. Pushable blocks
![Storyboard of pushable box interaction](DocImages/Pushable.png)
Following this, the push box is introduced and requires interaction to progress.
### 2.3. Weapon Pickup (Staff) & Chompers
![Storyboard of Staff and Chomper interaction](DocImages/Staff&ChomperStory.png)
Then the staff is provided to the player, and a chomper closely following, representing that both are close range.
single enemy with no obstacles or further challenges around it.
### 2.4. Health Pickups
![Storyboard of Health Pickup interaction](DocImages/HealthStory.png)
after 2 instances of possible health loss, player is provided the chance to heal.
### 2.5. Weapon Pickup (Gun) & Spitters
![Storyboard of Gun & Spitter interaction](DocImages/GunStory.png)
The gun is then introduced, followed by a spitter a fair bit back, place in tight spot for enemy to reduce spitters movements, perfect height for use of gun. As before, representing that both are a farther range of combat than prior.
### 2.6. Spikes
![Storyboard of Spike interaction](DocImages/spikes.png)
used in basic parkour to present the threat that is the spikes. player can still be damaged but it is not game ending.
### 2.7. Moving Platforms & Passthrough Platforms
![Storyboard of Moving Platform interaction](DocImages/MPStory.png)
Moving Platforms used as a connective space to change elevation and take the player to the next section to progress and out of the tutorial section.
![Storyboard of One Way Platform interaction](DocImages/OWPStory.png)
Passthrough Platforms used as a one way door following the moving platform.
### 2.9. Checkpoints
![Storyboard of Checkpoint interaction](DocImages/Checkpoint.png)
introduced after the player has excited the tutorial.
### 2.10. Keys
![Storyboard of Keys interaction](DocImages/Keys.png)
After completing the section 2 puzzle, the player is presented with the first of three keys.
It is impossible to pass this key without picking it up, and therefore presents the player with its importance in finishing the game.


## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1

### 3.3.	Level Map – Section 2

### 3.4.	Level Map – Section 3

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.
As the tileset was made from the get go, Grey-boxed mapping wasnt an option. As such, rather than grey-boxed mapping, the basic layout of the map was set with little filled in, this allowed me to playtest each section, adding features as I went along.
This worked extremely well in Section 2, where I originally aimed to try and get a moving platform to move a pushable box across the acid, after many failed attempts however, I realised that the Box's had a floating effect, and could be used to "unlock" a path through the acid. With this, I design the first route within the game to take the player to the second box.
![First look at Section 2's puzzle](DocImages/S2P11.png)
After some playtesting of this route, it felt as if it was lacking something, and seemed bland with just being a parkour feature. Thus, Enemies were added to provide more challenge to the route.
![Enemies added to the puzzle map](DocImages/S2P12.png)
Continuing to playtest the sections puzzle, it still felt too short for a "hurdle puzzle" (Required to progress through the level), and I decided to mess around with adding a third route, and extending the acid pool to compensate for this change.
![Third route added to the puzzle map](DocImages/S2P13.png)