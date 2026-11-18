# Datheon Python Programming Internship

A collection of Python projects created for learning and practicing Python programming concepts as part of the Datheon Python Programming Internship.

## Projects

### Task 1 – Hangman Word Guessing Game
- Interactive word guessing game.
- ASCII-based Hangman graphics.
- Tracks incorrect guesses.
- Displays victory and defeat messages.

**Run:**
```bash
python hangman.py
```

### Task 2 – Stock Portfolio Performance Tracker
- Accepts stock ticker symbols, buy prices and share quantities.
- Retrieves stock prices using Yahoo Finance.
- Calculates investment value and profit or loss.
- Generates a CSV portfolio summary.

**Install dependency:**
```bash
pip install -r requirements.txt
```

**Run:**
```bash
python portfolio.py
```

### Task 3 – Automated File Organizer & Cleanup Utility
- Organizes files according to their extensions.
- Automatically creates category folders.
- Uses Python OS and Shutil libraries.
- Handles file naming conflicts and permission errors.
- Generates execution logs.

**Run:**
```bash
python organizer.py
```

### Task 4 – Rule-Based Interactive Terminal Assistant / Chatbot
- Recognizes greetings and multiple user intents.
- Answers business-hours questions.
- Provides internship submission information.
- Answers certificate-related FAQs.
- Supports fallback responses and exit commands.
- Uses a JSON FAQ dataset.

**Run:**
```bash
python chatbot.py
```

## Technologies Used

- Python 3
- CSV
- yfinance
- OS
- Shutil
- Pathlib
- Regular Expressions
- JSON

## Repository Structure

```text
Datheon_Python_Internship/
│
├── hangman.py
├── portfolio.py
├── portfolio_summary.csv
├── organizer.py
├── chatbot.py
├── faq.json
├── requirements.txt
└── README.md
```

## Installation and Setup

1. Install Python 3.
2. Clone or download this repository.
3. Open the project folder in VS Code.
4. Install dependencies:

```bash
pip install -r requirements.txt
```

5. Run each Python file using the commands provided above.

## Learning Outcomes

- Python programming fundamentals.
- Functions and exception handling.
- File handling and CSV operations.
- JSON data processing.
- Regular expressions.
- Automation using Python libraries.
- Basic financial calculations.

## Internship Information

**Program:** Datheon Python Programming Internship

**Repository:** Datheon_Python_Internship

**GitHub:** https://github.com/llenu119/Datheon_Python_Internship

---

*Developed for Python programming practice and learning.*

**Collaboration note:** Some project files in this repository are shared with another participant's implementation. Please follow Datheon's collaboration and attribution policy, understand and independently test the code, and disclose shared work when required before claiming individual completion.
