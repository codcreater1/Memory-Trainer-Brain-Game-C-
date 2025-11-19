Memory Trainer – Brain Game (C++)

A simple terminal-based memory training game written in single-file modern C++.
The game shows a random sequence of numbers that the user must memorize and type back correctly.
Each correct round increases difficulty by increasing the sequence length.

⭐ Features

Dynamic difficulty progression

Random number sequences

Clear UI with countdown

Score tracking

Strike system (3 mistakes allowed)

Fully single-file C++ project

Works on Linux, macOS, Windows

🎮 How It Works

A sequence of random numbers is generated.

You get a short countdown to get ready.

The sequence is shown briefly.

It disappears.

You must type the sequence exactly.

Difficulty increases after each correct round.

Game ends after 3 incorrect attempts.

📦 Build & Run
🔧 Compile
g++ -std=c++17 memory_trainer.cpp -o memory_trainer

▶ Run
./memory_trainer


Windows:

g++ -std=c++17 memory_trainer.cpp -o memory_trainer.exe
memory_trainer.exe

📁 File Structure
memory_trainer.cpp      # The whole game in a single file
README.md

📝 Example Gameplay
Round 3 – Sequence length: 5  
Get ready...  
3 1 8 9 4  
Now type the sequence:  
> 31894  
Correct!

🚀 Future Ideas

Word memory mode

Colors & animations

High-score save file

Pattern memory mode

Sound effects

📜 License

MIT License – free to use, modify, and share.
