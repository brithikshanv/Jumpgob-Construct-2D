#  JumpGob – A Simple 2D Coin Collector Game

##  Overview

**JumpGob** is a simple 2D platformer game created during my **third year of college** using **Construct 2**. We were asked to build a game—not something complex—and I chose to make this fun little side-scroller featuring a **goblin that sprints and collects coins**.

The process was intuitive thanks to Construct 2's visual event-based logic. I really enjoyed bringing this concept to life!

##  Gameplay

- Control a goblin who **runs**, **jumps**, and **attacks**
- Collect coins placed on floating platforms
- Score increases on each coin collected
- A score counter is shown in real time

##  Controls & Animations

The game uses keyboard input to trigger animations and actions:

| Key Pressed        | Action & Animation     |
|--------------------|------------------------|
| → Right Arrow      | Run (Not mirrored)     |
| ← Left Arrow       | Run (Mirrored)         |
| ↑ Up Arrow         | Jump                   |
| ↓ Down Arrow       | Attack                 |
| Release Arrow Keys | Switch to Idle         |


##  Game Logic

All logic is built using **event sheets** in Construct 2. Highlights include:

- **Keyboard input detection** for movement and animation switching
- **Coin collision detection** using sprite interactions
- **Destroying collected coins**
- **Adding to score and updating score display** using a text object
- **Background layers and platform placement** for a lively scene


##  Screenshots

###  Gameplay View:
*(Goblin collecting coins with score display and background)*  
<img width="1919" height="1030" alt="image" src="https://github.com/user-attachments/assets/81987bd1-abef-40dc-a51a-a57cd05c7eb7" />


###  Event Sheet Logic:
*(Animations, collisions, score update logic)*  
<img width="1919" height="1030" alt="image" src="https://github.com/user-attachments/assets/3b5413c9-8981-490e-980d-72c08b3cdefb" />


