# Mobile_Project3
Repo for the third project of CSC 410

Project 3 will be your first step into mobile game development. 

You will need to design a game with the following:  
- A player avatar  
  - Stage 1: <strike>Spawns at a fixed location,</strike> fires towards the location the player taps <strong>(this works, but the spit doesn't rotate) </strong>
  - Stage 2: <strike>Spawns at a fixed location.</strike> Players can drag the avatar and tap to fire, <strike>fires in a straight line</strike>
- Multiple types of enemies  
  - <strike>Stage 1: Enemies spawn at random intervals in random locations and remain stationary</strike>  
  - Stage 2: Enemies spawn as in Stage 1. Enemies move randomly and enemies fire back at the player avatar  
- <strike>Count how many times the player shoots</strike>
- <strike>Count how many enemies the player hits</strike>
- <strike>Count how many enemies the player kills</strike>
- <strike>Track time during stages</strike>
- Multiple Stages  
  - Stage 1: Player and enemies spawn. Player has X time to kill enemies on the screen, each enemy killed adds time. Must kill at least 10 to continue to stage 2  
  - Stage 2: Player and enemies spawn. Player must kill all enemies on the screen without dying  
- Game Over Stage: display stats and player score  
- Notes:  
  - <strike>You may use simple hit detection object.dest.contains(object.position)</strike>
  - Limit the number of player projectiles on the screen at a given time  
  - <strike>Must have multiple enemy graphics</strike>  
  - You may use any sounds of your choice, Required sound actions:  
    - Player/Enemy fires  
    - Player Hit  
    - Enemy Hit  
    - Background Music on Loop (may use sound manager with small files or media player)  
  - You must calculate and display a score based on the statistics captured during play (weights are up to you, but must be logical)  
  - You will be graded on how well the game performs and how enjoyable it is!  


<h2>Camel Sprite Coordinates</h2>
- Sprite 1 
  - (0, 0) (77, 0)
  - (0, 52) (77, 52)
- Sprite (old)
  - (80, 183) (160, 183) 
  - (80, 237) (160, 237)
- Sprite 3 (old)
  - (160, 183) (241, 183)
  - (160, 237) (241, 237)

<h2>Snake Green</h2>
- Stationary Sprite
  - (0, 70) (56, 70)
  - (0, 126) (56, 126)
- Attack Sprite
  - (66, 70) (142, 70)
  - (66, 126) (142, 126)

<h2>Snake Blue</h2>
- Attack Sprite
  - (144, 70) (225, 70)
  - (144, 126) (225, 126)
- Stationary Sprite
  - (231, 70) (293, 70)
  - (231, 126) (293, 126)
  
<h2>Spit</h2>
  - (0, 150) (45, 150)
  - (0, 167) (45, 167)


