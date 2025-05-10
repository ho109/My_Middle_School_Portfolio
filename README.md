# 📘 My Middle School Project (age 14 ~ 15)

A portfolio by **Kim Hyojae**, a student at **Naegok Middle School**, passionate about  
**IT**, **Artificial Intelligence**, and creating real-world solutions through code.

---

## 👋 About Me

Hello! I'm **Kim Hyojae**, a middle school student from South Korea.  
I’m deeply interested in **AI**, **software development**, and solving problems I face in daily school life using technology.  
Currently learning **Python**, **Java**, and **Entry** (a Korean visual coding platform.)  
Always growing through hands-on projects.

---

## 📂 Projects

### 1. Proper Waste Sorting Program

**📅 Period**: 2024.10.15 ~ 2024.10.21  
**🎯 Role**: Project leader, AI trainer, UI designer, and app developer  
**🛠 Technologies Used**:  
- **AI Training**: Entry’s image training feature  
- **Frontend**: Entry’s built-in UI tools  
- **Backend**: Entry’s built-in functions + custom additions  
- **Login System**: Entry’s data saving feature  

---

**📖 Description**  
This project began with the broad topic of **climate change**.  
By narrowing down to relatable issues, we chose **waste disposal** and identified that **improper sorting** was the key problem.

**Core Questions**:
- Why is recycling not working?  
  → Because of improper waste sorting practices  
- Solution: Use AI to help users sort waste correctly

The app was developed for a Zero Waste initiative in an IT class by our team *Hojae*.  
It helps students and users understand and perform correct waste sorting, even if they don’t know how.

**Key Features**:
- Button-based guide for known waste categories (e.g., plastic)  
- AI camera recognition for unknown waste  
- Friendly interface designed for beginners  

---

**🏆 Achievements**:
- Collected and trained ~100 images per category using Kaggle dataset  
- Avoided overload by focusing on plastics, paper, and cans  
- Designed presentation materials with Canva  
- Simplified UI based on peer feedback  
- Scored highly in school evaluation and presented in auditorium as a top team

---

### 🛠 Development Notes

- **10/10**: Started SW/AI project in school  
- **10/15**: Created paper prototype and mockup video  
- **10/16**: Researched how Entry could solve the problem  
- **10/17**: Applied Entry’s object recognition feature  
- Collected images from Kaggle (~100 per category)  
- Reduced data size and emphasized 3 main categories  
- **10/22**: Finalized app and Canva presentation  
- Improved UI based on peer feedback  
- **10/29**: Presented in class, voted by students, and ranked as a top project

---

### 2. Lost & Found App for School

**📅 Period**: 2025.03.24 ~ 2025.04.11  
**🎯 Role**: Planned, designed, and developed everything – both frontend and backend  
**🛠 Technologies Used**:  
- **Hosting**: Firebase Hosting  
- **Frontend**: HTML, CSS, JavaScript, Material Design UI, AI (Vive)  
- **Backend**: Firebase Realtime Database or Firestore, JavaScript, Vive  

---

**📖 Description**  
This project was submitted to the **46th Seoul Gangnam-Seocho Student Science Invention Contest**.  
It’s a **web-based lost & found management app** that helps students locate lost items more efficiently at school.

**Key Features**:
- Register and browse lost items by floor (1st to 4th)  
- Image and item name registration for visual clarity  
- Simple delete function for better management  
- Real-time data sync with Firebase  
- Optimized for Chromebooks and other school devices  
- Accessible UI with large buttons and clean layout  
- Represents a shift from analog to digital lost item management  
- Built using Vive AI tools as development support  

Admins can upload lost items, and students can search by floor—eliminating the need to visit the office and saving time.  
The system is designed to be scalable for **libraries, public institutions**, and other environments.

---

**🧠 Reflections & Lessons Learned**:
- Vive made frontend development faster, but overreliance led to debugging difficulty and less creativity  
- AI should be a tool—developers must retain independent judgment and problem-solving skills  
- Firebase was helpful but raised concerns over security (API key exposure), suggesting a need to explore safer alternatives

---

### 🛠 Development Notes

- **3/17**: Learned about the science invention contest  
- **3/19**: Lost my padded jacket due to a poor system → inspired the app idea  
- **3/25**: Received official notice to submit a project  
- **3/28**: Began development using Java and HTML, supported by AI tools  
- **3/29**: Discovered data was not saving properly  
- AI suggested using Firebase  
- **4/01**: Learned and applied Firebase integration in Java  
- **4/02**: Implemented real-time syncing  
- **4/03**: Improved UI and wrote documentation  
- **4/10**: Designed a poster for school distribution  
- **4/14**: School considering full adoption of the app

---
### 3. Undertale-Inspired Turn-Based Battle Game

- **Period**: 2025.05.09 ~ 2025.05.11  
- **Role**: Full planning and design, developed entire logic and UI using AI assistance  
- **Technologies Used**:  
  - **Frontend**: HTML, CSS (Vive), JavaScript, Canvas API  
  - **Game Structure**: VIVE coding environment + custom-made sprites (via Piskel)  
  - **Image Assets**: Hand-edited pixel art monster images  

---

**📌 Project Overview**  
This is a **turn-based battle game** fully implemented using the Canvas API and plain JavaScript.  
The structure is inspired by *Undertale*, one of my favorite games, and simplified into a playable prototype.

- **Z key**: Attack & start (you must press Z to begin the game) → Damage varies based on timing (closer to center = more damage)  
- **X key**: Use item (restore HP)  
- **C key**: Use a strong skill at the cost of some HP  
- **Spacebar**: Restart the game after losing  
- **Arrow keys / WASD**: Move and dodge attacks

- Each enemy features a **unique bullet pattern**:
  - Goblin: Diagonal slow bullets from the top right corner  
  - Wolf: Alternating vertical waves (currently too easy, may need rebalance)  
  - Wizard: Spiral-shaped projectile pattern  
  - Fire: Rising flame bullets from the bottom  
  - Robot: Large square-shaped bullets fired in cardinal directions (quite hard to dodge, may need tweaking)  
  - Slime: Very weak and can be defeated in one hit

> After every enemy turn, their pattern is automatically triggered.  
> Failing to dodge results in damage.  
> When an enemy is defeated, the player's HP is **fully restored** for the next round.

---

**💬 Reflections & Takeaways**  
- This was my first time designing a full game using the **Canvas API** and JavaScript.  
  I implemented **animation, collision detection, key input logic, and difficulty tuning** all by myself.  
- Although tools like **Vive AI** helped me quickly structure the project,  
  I realized that **debugging and refining the logic manually is absolutely essential**.  
- It was especially fun and rewarding to fine-tune small details such as **goblin bullet spread** and **auto-heal after defeating slime**.

---

### 🛠 Development Notes

- **2025.05.09**:  
  Played *Undertale* all evening and suddenly wanted to create my own pixel-style game.  
  Originally planned a 2-character switching battle system using WASD & arrow keys,  
  but it became too complex to debug and I couldn't finish it, so I restarted with a simpler idea.

- **2025.05.10**:  
  Implemented basic movement, dodging, and sway effects for enemy sprites.  
  Added enemies like Goblin, Wolf, Wizard instead of just Slime, and diversified attack patterns.  
  Fixed bugs related to item usage, restarting with spacebar, and HP recovery.

- **2025.05.11**:  
  Finalized code structure and cleaned it up.  
  Wrote portfolio documentation and finished gameplay testing.  

---

🔗 **Game Demo**: [https://ho109.github.io/pixel/](https://ho109.github.io/pixel/)

---

## 💫 Learning Highlights

### Micro:bit Projects  
- Controlled servo motors, OLED displays, LED I/O  
- Practiced predictive logic with real-world sensors

### SFPC 2024 Participation  
- Solved 8/11 problems (Rank: 119th)  
- Visualized school API data with Google Sheets  
- Studied computer systems and logic structure

### Data Handling Practice  
- Cleaned and structured spreadsheet datasets  
- Found and fixed errors  
- Created visual charts from raw data

---

## ❓ What is Entry?

**Entry** is a Korean block-based coding platform similar to Scratch.  
Used widely in Korean schools for teaching programming.  
Supports:  
- AI model training  
- Object recognition  

---

## 🎁 Resources & Links

- 🔗 [Entry Project - Waste Sorting App](https://playentry.org/project/671593d4c40ad113746d7067)  
- 🎥 [Presentation (Canva)](https://www.canva.com/design/DAGlgHBqS0U/5Zv8k1mrrHjHVt1lRMjH6w/edit)  <-- If you would like to know more about this project, please read this
- 📊 [Kaggle Dataset for AI Training](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification)  
- 🖼 [Poster - Lost & Found App (Korean)](https://www.canva.com/design/DAGTPe0au8E/fj4cUME4IcYzAhzeEHhMFg/e)

---

## 🙌 Closing Thoughts

These projects taught me how real-world experiences can lead to meaningful software solutions.  
They helped me grow technically and creatively, and sparked my interest in solving problems through technology.  
I’m excited to keep learning and building even better solutions in the future.
