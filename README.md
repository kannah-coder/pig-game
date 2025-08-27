#  Pig Dice Game (Python)

A simple multiplayer **Pig Dice Game** written in Python.  
Players take turns rolling a die and try to be the first to reach 100 points.

---

## Rules
1. The game supports **1 to 4 players**.
2. On each turn, a player may roll the dice as many times as they like:
   - If the player rolls a **1**, they lose all points for that turn and their turn ends.
   - If they roll **2–6**, the value is added to their **current turn score**.
3. At any point, the player may choose **not to roll** and "hold".  
   - Their **turn score is added to total score**.
4. The first player to reach **100 points** wins the game. 🎉

---

## How to Run
1. Make sure you have **Python 3** installed.
2. Save the code into a file (e.g., `pig.py`).
3. Run the program:
   ```bash
   python pig.py
---   
Enter number of players(1-4): 2
Player number 1 turn has just started!

Would you like to roll (yes/no)? yes
You rolled a: 5
Your score is: 5
Would you like to roll (yes/no)? yes
You rolled a: 1
You rolled 1! You are done.
Your total score is: 0
