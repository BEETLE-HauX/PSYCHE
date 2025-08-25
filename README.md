# 🧠 PSYCHE: Retro Cyber Quest

> *"The Neon Mainframe awaits those who can decipher its digital whispers..."*

![Cyberpunk Terminal](https://img.shields.io/badge/Theme-Retro__Cyberpunk-39ff14?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Built_with-Streamlit-FF4B4B?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge)

A terminal-style puzzle adventure set in a neon-drenched cyberpunk world. Solve cryptographic challenges, play retro mini-games, and assemble the Master Key to unlock the secrets of the Neon Mainframe.

## 🌌 Terminal Initiation

### Prerequisites

```bash
# Clone the repository
git clone https://github.com/your-username/psyche-cyber-quest.git
cd psyche-cyber-quest
```
```bash
# Create virtual environment
python -m venv neon_env
source neon_env/bin/activate  # Linux/Mac
# or
neon_env\Scripts\activate    # Windows
```
```bash
# Install dependencies
pip install -r requirements.txt
# Optional: AI Integration
# For enhanced cybernetic responses, set up Groq AI:
```

```bash
# Create .env file
echo "GROQ_API_KEY=your_api_key_here" > .env
# Note: The system works perfectly without AI - uses built-in persona emulator
```
## Launch Sequence
```bash
streamlit run app.py
# TERMINAL ONLINE - Mainframe connection established at http://localhost:8501
```

## 🎮 Interface Commands
### Command	Effect	Usage

<img width="569" height="586" alt="image" src="https://github.com/user-attachments/assets/02485b9c-656a-4eae-8122-ff65c4426d8a" />


## 🧩 Puzzle Matrix
###Fragment Collection
1. Solve 8 cryptographic puzzles to collect fragments:
2. Sound Ghost - Identify the canyon's answer
3. Triangular Sequence - Decipher the numeric pattern
4. Mainframe Whisper - Caesar cipher decryption
5. Dusty Badge - Word reorganization puzzle
6. Acrostic Cipher - Extract skyline initials
7. Packet Payload - Base64 decoding challenge
8. Binary Glyphs - Byte-to-ASCII translation
9. Patch-note Prose - Commit lore terminology

## Mini-Games
### Two retro challenges await:

1. Neon Snake - Score ≥ 10, then type score X (your actual score)
2. Typing Reflex - Reach 25+ CPM, then type score X (your actual CPM)

### Final Assembly
Collect all fragments to form: NE ON GR ID UN LO CK ED
Assemble into Master Key

## 🎯 How to Play
1. Type quest to begin your initiation
2. Read each puzzle carefully - cyberpunk riddles require perception
3. Type answers directly - the mainframe validates your input
4. Use hint when the digital static overwhelms you
5. Play mini-games when they appear in the sequence
6. Collect all fragments - watch your inventory grow
7. Assemble the Master Key - final format: ** ** ****
8. Claim your reward - type secret after unlocking everything

## 🕹️ Mini-Game Instructions
### Neon Snake
1. Controls: Arrow keys to navigate
2. Objective: Eat neon dots, avoid your tail
3. Success: Score ≥ 10, then type score [your-actual-score]
4. Pro Tip: Corners are lethal - plan your route

### Typing Reflex
1. Objective: Type phrases quickly and accurately
3. Success: Reach 25+ CPM, then type score [your-actual-CPM]
3. Pro Tip: Rhythm beats speed - steady pacing wins

## 🔧 Technical Architecture

psyche-cyber-quest/
├── app.py              # Main application driver
├── puzzles.py          # Puzzle definitions & validators
├── llm.py             # AI/Persona response system
├── ui.py              # Interface rendering components
├── styles.py          # Cyberpunk CSS and themes
├── matrix.py          # Matrix rain background effect
├── games.py           # Mini-game implementations
└── requirements.txt   # Dependencies

## 🚀 Deployment
### Local Development
```bash
streamlit run app.py
```
### Cloud Deployment
Ready for deployment on:
1. Streamlit Cloud
2. Heroku (with Procfile)
3. Railway
4. Hugging Face Spaces

🎲 Sample Gameplay
text
> quest
🤖 Quest initiated. Solve the puzzles to assemble the Master Key.
🤖 Signal without source. No lungs, no lips—yet the canyon answers...

> echo
🧑 echo
🤖 Correct! Fragment [NE] secured.
🤖 Next puzzle: Triangular surge (Observe the sequence): 2, 6, 12, 20, 30, __?

> 42
🧑 42
🤖 Fragment [ON] resonates with the grid...
📜 License
MIT License - Feel free to hack the mainframe and modify as you see fit.

👨‍💻 Cyber-Operative
Created by Mayank Kumar - Keeper of the Neon Mainframe, for the GDG Retro Project....
[Demo Video link = https://youtu.be/EKkquM3WAeE]

"The grid welcomes those who dare to solve its mysteries..."

