# 📘 My Middle School Development Portfolio

Hello! I'm **Kim Hyojae**, currently attending **Naegok Middle School**.  
I have a deep interest in IT and artificial intelligence, and I aim to solve  
problems I encounter at school using coding and AI as tools.

This portfolio showcases the **AI app development projects**,  
**environmental problem-solving projects**, and  
**learning activity records** I completed during middle school.

---

## 👤 About Me

- **Name**: Kim Hyojae  
- **Time Period**: Grade 8 ~ Grade 9 (2024–2025)  
- **School**: Naegok Middle School  
- **Fields of Interest**: IT, Artificial Intelligence, App Development, Problem Solving  
- **Technologies Used**: `Python`, `HTML`, `Java`, `Entry`, `AI (Vive)`

---

## 📂 Projects

### 1. Proper Waste Separation Program

- **Period**: 2024.10.15 ~ 2024.10.21  
- **Role**: Project Leader, Developer, Designer, AI Image Trainer  
- **Technologies Used**:  
  - AI Image Training: Entry's image training feature  
  - Frontend: Entry buttons and UI tools  
  - Backend: Entry core functions + custom features  
  - Login: Entry data storage functions  
  - Others: Canva for presentations, Kaggle dataset used  

---

**Project Description**  

Started by analyzing the broad topic of **climate change**

→ Extracted key issues like **deforestation**, **carbon emissions**, **waste generation**

→ Chose **waste disposal** as the most relatable issue

> What is the core problem with waste disposal?

→ Recycling is not happening properly

> Why is recycling rate low?

→ Due to incorrect waste separation

→ Chose **incorrect waste separation** as the problem

Started as a SW/AI problem-solving school project under the theme of zero waste.  
From the broad topic of **climate change**, we extracted the issue of **improper waste separation**  
and decided to tackle it using **AI image recognition**.

- Recycling fails primarily due to incorrect waste sorting  
- To solve this, we built an **app that uses AI to recognize waste types**  
  and **suggests proper disposal methods**.

**Key Features**:  
- Provides disposal instructions by button click  
- AI auto-recognizes waste via camera and offers separation guidance  
- Intuitive UI improves accessibility  
- Designed for ease of use by students unfamiliar with recycling

---

### 🛠 Development Log

- **10/10**: Project kickoff  
- **10/15**: Paper prototype and mockup video  
- **10/16**: Researched Entry capabilities and structured data  
- **10/17**: Applied object recognition in Entry  
- **10/18–20**: Collected and trained 150 images each from Kaggle  
  - Focused on plastic, paper, and cans to avoid overload  
- **10/22**: Made presentation slides with Canva, improved app polish  
- **10/25–28**: Collaborated with peers for UI simplification  
- **10/29**: Class presentation and group voting → Selected for auditorium presentation and awarded gift card

**Links**:  
- 🔗 [Entry Project](https://playentry.org/project/671593d4c40ad113746d7067)  
- 🎥 [Presentation (Canva)](https://www.canva.com/design/DAGUKJn3pSI/M9Ogjcmxi96MZn3XSw-Wcw/edit)  
- 📊 [Kaggle Image Dataset](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification)

---

### 2. School Lost-and-Found App

- **Period**: 2025.03.24 ~ 2025.04.11  
- **Role**: Full planning, design, frontend & backend development  
- **Technologies Used**:
  - **Hosting**: Firebase Hosting  
  - **Frontend**: HTML, CSS (Vive), JavaScript, Material Design UI, AI (Vive)  
  - **Backend**: Firebase Realtime DB or Firestore, JavaScript, Vive  

---

**Project Description**  
Submitted to the **46th Seoul Gangnam-Seocho Student Science Invention Contest**,  
this **digital lost-and-found management system** is a web-based app  
designed to help students easily find their lost items at school.

- Users choose from floors 1–4 to register lost items  
- Inputs: Image and item name → provides visual information  
- Features: Simple delete function for ease of management  
- Real-time sync: Firebase enables instant multi-device updates  
- UI/UX: Optimized layout and large buttons for accessibility  

This software-based app enables a practical shift  
from analog to digital systems, showing both innovation and usability.  
Assuming a management point per floor, users can check lost item locations  
without visiting the teacher’s office, saving time and improving satisfaction.

> First time using **Vive** for UI design support.

This structure can be adapted for use in **libraries, public spaces, and more**  
as a general-purpose **digital asset management solution**.

---

**Reflections / Lessons Learned**  
- **Vive** helped build designs quickly  
- However, **debugging was difficult** and **creative control felt limited**,  
  so AI tools are best as assistants  
- Learned that **Firebase is easy to use**, but exposed API keys reminded me  
  to study **security practices** more (e.g., securing keys)  
- Developers should use tools wisely while **thinking critically and improving actively**

---

### 🛠 Development Log

- **3/17**: Heard about the invention contest  
- **3/19**: Lost my padded jacket → experienced the problem firsthand  
- **3/25**: Project submission announced in science class  
- **3/26–27**: Formed app idea based on my lost item experience  
- **3/28**: Began development with Java, HTML, AI  
- **3/29**: Data wouldn’t save → AI suggested Firebase  
- **3/30**: Finalized submission, fixed bugs  
- **4/01**: Learned Firebase and implemented  
- **4/02**: Real-time sync completed  
- **4/03**: UI improvements, documentation written  
- **4/10**: Poster created for submission  
- **4/14**: Started discussions to adopt it at school

🔗 **App Demo**: [View App](https://ho109-6eb98.web.app/)  

---

### 3. Undertale-Style Turn-Based Battle Game

- **Period**: 2025.05.9 ~ 2025.05.13  
- **Role**: Planning, design, game logic, and UI — fully developed using AI  
- **Technologies Used**:  
  - **Frontend**: HTML, CSS (Vive), JavaScript, Canvas API, VIVE  
  - **Game Structure**: VIVE coding + Piskel-made sprites  
  - **Image Assets**: Custom-edited pixel art monsters  

---

**📌 Project Description**  
Inspired by the game **Undertale**,  
this turn-based battle game was created using pure JavaScript and the Canvas API.

- **z key**: Attack & Start → damage based on timing (closer to center = more damage)  
- **x key**: Use healing item  
- **c key**: Consume HP to deal powerful attack  
- **p key**: Choose monster (0 = Slime / 1 = Bat …)  
- **spacebar**: Restart game after game over  
- **Arrow keys / WASD**: Dodge and move  


- Enemies have unique **bullet patterns**:
  - Goblin: Diagonal bullets tracking the player  
  - Wolf: Vertical bullets with slight side movement  
  - Wizard: Spiral pattern bullets  
  - Fire: Rising fire bullets that explode  
  - Robot: Diagonal large boxes that explode clockwise/counter-clockwise  
  - Slime: Very weak, can be defeated in one hit

> Enemy patterns play out each turn. Failing to dodge causes damage.  
> Defeating an enemy **automatically restores your health** for the next round.

---

**Reflections / Lessons Learned**  
- First time using **Canvas API** and JavaScript to build a game from scratch  
- Implemented **animations, hit detection, key events, difficulty balance**  
- AI (Vive) was useful for structure, but real insight came from  
  **manual debugging and logical refinement**  
- Enjoyed fine-tuning mechanics like Goblin’s homing bullets  
  and auto-healing after defeating Slime

---

### 🛠 Development Log

- **5/9**: Got inspired while playing Undertale to make a pixel game  
  Tried a 2-player version but gave up as it got too hard to beat  
- **5/10**: Implemented movement, dodge, sway effects  
  Added Goblin, Wolf, Wizard enemies with unique patterns  
- **5/11**: Refactored code, tested gameplay  
  Fixed a major bug due to missing `draw ui` function  
- **5/12**: Final balance patch (2 hours)  
  Reworked Goblin’s bullets to homing type  
  Enhanced Fire & Robot bullets with explosion and visual effects
  
- **5/13**
  Last update (took a total of 1 hour)  
  The slime was too easy to defeat, so I added a giant slime at the end  
  The giant slime's projectiles now bounce off walls twice and scatter widely in a pattern  


🔗 **GitHub**: https://github.com/ho109/pixel  
🔗 **Game Demo**: https://ho109.github.io/pixel/  

---

## 💡 Learning Record

### Micro:bit Projects
- Controlled servo motor, OLED, LED  
- Implemented linear regression model in Entry  
- Built prediction algorithms for data-based solutions

### Participated in 2024 SFPC as Team "Baked Salt"
- Solved 8 out of 11 problems → Ranked 119th  
- Visualized API data with Google Sheets  
- Studied computer systems and their operation

### Data Practice
- Organized data using Excel and Google Sheets  
- Detected and corrected errors  
- Created and visualized charts
