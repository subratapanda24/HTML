# Nokia Snake Game – Web Implementation

## Project Title
Nokia Snake Game (Web-Based Retro Simulation)

## Project Type
College Mini Project

## Abstract
This project presents a web-based implementation of the classic Nokia Snake game. 
The objective of the project is to recreate the retro gaming experience of early 
mobile devices using modern web technologies. The interface simulates a Nokia 
3310-inspired device design, while the core gameplay logic is implemented using 
JavaScript and rendered through the HTML5 Canvas API.

The project demonstrates understanding of DOM manipulation, game loop logic, 
collision detection, responsive layout structuring, and browser-based storage.

---

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- HTML5 Canvas API
- LocalStorage (for High Score persistence)
- Google Fonts (VT323 – Retro Pixel Typography)

---

## Functional Overview

1. Hero Section  
   A large retro-styled introduction section displaying the game title and 
   navigation to the gameplay area.

2. System Specification Section  
   Simulated Nokia-style device specifications displayed using responsive grid layout.

3. Information & History Section  
   Card-based layout presenting historical information about the original Snake game.

4. Game Interface Section  
   - Nokia 3310 styled casing
   - LCD-style screen effect
   - Functional Snake game
   - On-screen keypad controls
   - Keyboard arrow key support

5. Game Mechanics  
   - Snake movement with directional control  
   - Food spawning at random grid positions  
   - Score increment system  
   - Speed increase at score intervals  
   - Self-collision detection  
   - Wrap-around wall behavior  
   - High score stored using browser localStorage  

---

## Project Structure
## Project Structure

```
Nokia-Snake-MiniProject/
│
├── index.html
└── README.md
```

(All styling and scripting are embedded within the HTML file.)

---

## Implementation Details

- The game grid is rendered using the Canvas API.
- A continuous game loop is managed using setInterval().
- Collision detection is handled by comparing snake head coordinates 
  with body segments.
- Game speed dynamically adjusts based on score milestones.
- High score persistence is implemented using localStorage.

---

## Learning Outcomes

Through this project, the team gained practical experience in:

- Structuring large HTML documents
- Advanced CSS styling and retro UI recreation
- Implementing real-time game logic in JavaScript
- Managing state and dynamic rendering
- Handling keyboard and button-based input
- Using browser storage for persistent data

---

## Team Members

- Subrata Panda  
- Sanika Kangane  
- Japji Kaur  
- Parth Sarova  

---

## Conclusion

The Nokia Snake Game project successfully recreates a classic mobile gaming 
experience within a modern web environment. It combines front-end design 
principles with interactive programming logic to produce a fully functional, 
browser-based retro game simulation.
