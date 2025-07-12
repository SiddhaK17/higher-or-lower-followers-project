# 📊 Higher or Lower: Follower Comparison Game (CLI Edition)

Inspired by real-world decision-making and developed as a hands-on challenge while progressing through the *"100 Days of Code: The Complete Python Pro Bootcamp"*, under the guidance of Dr. Angela Yu throughout the course.  
This interactive terminal-based game challenges users to compare global celebrities and brands by guessing who has more social media followers — a perfect fusion of entertainment and Python programming logic.

---

## 📖 Overview

**Higher or Lower: Follower Comparison Game** is a command-line Python project that puts players’ intuition and pop culture knowledge to the test. The objective is simple yet addictive:  
> *Guess who has a higher follower count between two randomly chosen public figures or brands.*

With every correct answer, the score increases — and with one wrong guess, it’s game over.  
This project emphasizes structured programming practices, modular code design, and data-driven logic, all within a clean and engaging text-based UI.  
It offers a great example of how fundamental programming skills can be applied to build interactive and replayable software experiences using Python.

Whether you’re a budding developer refining your skills or someone exploring creative ways to practice coding, this game serves as an ideal mini-project to solidify core Python concepts.

---

## 🛠️ Technologies & Concepts Used

> This project goes beyond basic scripting by showcasing foundational and intermediate Python development principles through an engaging CLI game.

- ⚙️ **Python 3.x** – The entire game is built using Python, emphasizing structured scripting and modularity.
- 🧩 **Modular Programming** – The codebase is split into multiple files (`main.py`, `art.py`, `game_data.py`) promoting clarity, reuse, and maintainability.
- 🔁 **Control Flow & Decision Logic** – Implements conditional statements (`if`, `else`) and loops to manage user input and game progression.
- 🎯 **Function Design** – Key logic is encapsulated in reusable functions like `format_data()` and `check_answer()` to enforce clean, testable code.
- 🎲 **Randomization** – Uses Python’s `random.choice()` for dynamic, unpredictable entity selection—critical for replayability.
- 🧱 **Data Handling** – Effectively manipulates dictionaries and lists to store, retrieve, and display structured celebrity data.
- 📜 **String Interpolation** – Dynamic message generation using `f-strings` to personalize game feedback in real-time.
- 🎨 **ASCII Art Integration** – Enhances CLI experience with visually engaging splash screens and separators stored in a separate module.
- 🚀 **Beginner-Friendly Design** – Designed with educational value, simulating real-world development patterns in a simplified environment.

---

## 🎮 Gameplay Mechanics

> A clean and logic-driven game loop that blends strategy with intuition, encouraging players to think critically based on cultural knowledge.

- 🔄 **Continuous Round Loop** – The game progresses until the player makes an incorrect guess, using smooth transitions from one round to the next.
- 👥 **Dynamic Comparisons** – Players compare two random personalities/brands based on hidden follower counts.
- 📈 **Score Progression** – Each correct guess increases the player’s score, providing feedback and a sense of achievement.
- 🧠 **Deductive Reasoning** – Players are challenged to infer who’s more popular based on their own knowledge of the figures.
- 🧹 **Duplicate Prevention** – Built-in logic ensures two different entities are always compared—avoiding redundant or broken comparisons.
- 🎯 **Guess Evaluation System** – Validates player input against real data, then provides context-aware feedback using formatted strings.
- 🖼️ **Visual Consistency** – Each round displays consistent visual structure (Compare A → VS → Compare B), enhancing user cognition.
- 🚫 **Game Termination** – The game exits gracefully on a wrong answer, clearly displaying the final score for closure.
- 🔧 **Scalable Logic Base** – Easily extendable to include categories, difficulty levels, or even a GUI in future iterations.

---

## 🧱 Project Structure

```
higher-or-lower-followers-project/
    ├── main.py         # Core game logic and main script
    ├── art.py          # Contains ASCII art used in the game
    └── game_data.py    # Dataset of influencers and their details
    └── README.md       # Game documentation and usage guide
```

---
### 🛠️ How to Run

> ⚠️ Make sure Python 3 is installed on your system.

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/higher-or-lower-followers-project.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd higher-or-lower-followers-project
   ```

3. **Run the script**
   ```bash
   python main.py
   ```

---

### 🔑 Key Highlights

✨ **Engaging CLI Experience**  
Delivers an interactive, user-friendly game interface directly in the terminal, enriched with ASCII visuals and real-time feedback.

🧠 **Logic-Driven Gameplay**  
Implements comparison logic using conditional statements and encapsulated functions to drive the game's progression.

🔄 **Dynamic Content Rotation**  
Ensures every round presents fresh, randomized comparisons from a diverse dataset — improving replayability and challenge.

📈 **Score Tracking Mechanism**  
Maintains and displays the player's score across rounds, encouraging competitive gameplay and personal improvement.

🧪 **Modular Codebase**  
Follows clean separation of concerns using modular files (`main.py`, `game_data.py`, `art.py`) for scalability and maintainability.

🎯 **Real-World Context Simulation**  
Uses real-life influencer data, making the game both entertaining and relatable for modern audiences.

🧰 **Hands-On Python Practice**  
Reinforces Python fundamentals such as functions, imports, data structures, input/output, loops, and control flow — ideal for beginners and learners.

---

### 🙌 Credits

This project was created as part of my Python learning journey, guided throughout the course by **Dr. Angela Yu**.  
Inspired by real-world social media logic, the game serves as a practical application of Python fundamentals taught during the "100 Days of Code: The Complete Python Pro Bootcamp".

Gratitude to:
- **Dr. Angela Yu** for her clear and insightful teaching.
- The **Python open-source community** for fostering a rich learning environment.
- You, the reader, for exploring this project!

---
