# 🎮 Java Hangman Game 🕹️

Welcome to the **Java Hangman Game** — a fun command-line game where you guess the hidden word one letter at a time before the stickman is fully drawn! ✍️

---

## 📁 File Structure

- `Main.java` — Contains the main game logic.
- `words.txt` — A text file with a list of words (one per line) for the game to randomly choose from.

---

## 🧠 How It Works

1. 📖 Reads words from `src/words.txt`
2. 🎲 Randomly selects one word
3. 👤 Prompts the user to guess a letter
4. ✅ Displays correct guesses
5. ❌ Tracks wrong guesses (up to 6)
6. ☠️ Ends game if too many incorrect guesses
7. 🏆 Congratulates the player on winning

---

## ▶️ How to Play

### 1. Clone or Download the Project

```bash
git clone https://github.com/Nika-HISK/Java-Hangman-Game.git
```
### 2. Navigate to the Source Directory
```
cd src
```
### 3. Compile the Program
```
javac Main.java
```
### 4. Run the Program
```bash
java Main
```
Make sure `words.txt` exists and is populated with words (one per line).

## Start guessing letters!

## The game ends when you:

- Correctly guess all letters ✅

- Make 6 incorrect guesses ❌

### 🎨 Hangman Art
```
  o
 /|\
 / \
```

## 🛠 Requirements
Java 8 or higher ☕

## 📌 Notes
- Words are loaded from the second line of words.txt onward (first line is skipped).

- Make sure the file path in the code matches your project structure.

## 📄 Example words.txt
```
# Word List
commission
injury
designer
parachute
```
## 🙌 Have Fun!
