# SubHunt  
**Link to Play the Game:** [SubHunt Online](https://presser.sites.gettysburg.edu/games/SubHunt/)

**Itch.io Page:** [SubHunt on Itch.io](https://cpresser.itch.io/subhunt)  

SubHunt is an underwater tactical game built with the Godot engine, where players take control of a submarine on a mission to hunt down hidden targets using sonar and torpedoes. The game combines stealth, precision, and action in an immersive underwater environment.  

---

## 🎯 Game Background  
SubHunt was created as part of the **[Games for Blind Gamers 4 Game Jam](https://itch.io/jam/games-for-blind-gamers-4)**, hosted on itch.io. The game jam challenges developers to create accessible games for blind and visually impaired players, encouraging innovative use of sound-based mechanics, haptics, and audio cues.  

In response to this challenge, SubHunt was designed to emphasize sound-based detection and gameplay, allowing players to rely primarily on sonar pings and audible cues to locate and track hidden targets. The game aims to be inclusive while also offering a fun and challenging experience for all players.  

---


## 🎮 Controls  
- **Arrow Keys:** Move and turn the submarine.  
- **C** or **`**: Toggle camera (on/off).  
- **S:** Emit a sonar ping to detect nearby targets.  
- **SPACE:** Fire a torpedo.  
- **R:** Randomly reposition the target (Note: may need to press twice due to a known bug).  
- **E:** Toggle "last known location" mechanic.  

---

## 🛠️ Game Features  
- **Physics-Based Target Movement:** Targets move using applied forces, making them behave more realistically.  
- **Torpedo Combat:** Both the player and enemy targets can fire torpedoes, adding an element of risk and combat strategy.  
- **Sound-Based Detection:** Use sonar pings to detect hidden targets, and listen for audible cues when targets are nearby.  
- **Level Progression and Game States:** Start, end, and next-level functionalities guide the player through various challenges.  
- **Modular Structure:** Player, Target, and Field are designed as individual scenes for easier modification and expansion.  
- **Immersive Audio:** Includes sonar sounds, torpedo effects, and other audio cues to heighten the tension.  

---

## 🎯 Future Goals  
The project aims to evolve with additional features such as improved audio design, refined game mechanics, and the addition of new levels and challenges. Stay tuned for updates as SubHunt continues to grow!  

---

## 🆕 What's New?  
### 2/26/2025  
- Added sound settings and instructions UI for enhanced user experience.  
- Implemented game over and next-level functionality.  
- Introduced "last known location" mechanic (toggle using the **E** key).  

### 2/25/2025  
- Targets emit audible cues when you are nearby, adding an element of sound-based detection.  
- Targets can fire torpedoes at the player.  
- Physics-based movement added for dynamic target behavior.  
- Players now take damage when hit by enemy torpedoes.  
- Reduced the gameplay field to one active target to focus on core mechanics.  

### 2/24/2025  
- Improved project organization by adding subfolders in `res://` for better code management.  
- Integrated key contributions:  
  - **Torpedo mechanics:** from Anaya.  
  - **Short sonar sound effect:** from Dipto.  
  - **Movement controls:** from Yash.  
- Expanded the game field to a larger, more square area.  
- Separated Player, Target, and Field elements into individual scenes for modularity.  
- Added out-of-bounds detection for the player when they stray 90m beyond the center.  
- Enhanced gameplay with multiple sonar-pinging targets, target responses to torpedo hits, and diverse sound effects.  
