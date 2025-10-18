# 🐍 AI Snake Game 🎮

An intelligent Snake game where the snake automatically follows the apple using AI/algorithmic logic! Watch as the snake hunts down apples on its own using smart pathfinding algorithms.

## 📝 Description

This is an AI-powered implementation of the classic Snake game where the snake operates autonomously. Instead of manual control, the snake uses intelligent algorithms to locate and reach apples automatically. Built with C/C++ and SDL2, this project demonstrates algorithmic problem-solving and game AI concepts in action.

## ✨ Features

- 🤖 **AI-Controlled Snake** - Autonomous movement with intelligent decision-making
- 🍎 **Auto Apple Hunting** - Snake automatically finds and consumes apples
- 🎯 **Smart Pathfinding** - Uses efficient algorithms to navigate the game grid
- 🎨 **Classic Snake Gameplay** - Traditional Snake game mechanics with an AI twist
- 💻 **C/C++ Codebase** - High-performance implementation using SDL2
- 🔊 **SDL2 Libraries** - Graphics rendering with SDL2_image, SDL2_mixer, and SDL2_ttf
- 🏆 **Self-Playing Game** - Watch the AI master the Snake game!

## 🧠 How It Works

The AI snake uses intelligent algorithms to automatically navigate toward the apple:

- **Greedy Search Algorithm**: The snake evaluates the shortest path to the apple
- **Directional Decision Making**: At each step, the snake calculates the optimal direction
- **Collision Avoidance**: Smart logic to avoid running into walls and its own body
- **Shortest Path Logic**: Prioritizes moves that reduce distance to the target apple

The algorithm continuously updates the snake's direction based on the apple's position, creating an autonomous gaming experience.

## 📋 Requirements

To build and run this project, you'll need:

- **SDL2** - Simple DirectMedia Layer 2.0
- **SDL2_image** - Image loading library for SDL2
- **SDL2_mixer** - Audio mixer library for SDL2
- **SDL2_ttf** - TrueType font library for SDL2
- **C/C++ Compiler** - GCC, MinGW, or MSVC
- **Platform** - Windows (or compatible platform with SDL2 support)

## 🚀 Setup Instructions

### Option 1: Run the Pre-built Executable (Windows)

```bash
# Simply run the provided executable
snake.exe
```

Make sure all SDL2 DLL files are in the same directory as the executable.

### Option 2: Build from Source

```bash
# Using the provided Makefile
make

# Or compile manually
gcc snake.c -o snake.exe -lSDL2 -lSDL2_image -lSDL2_mixer -lSDL2_ttf
```

### Option 3: Manual Compilation (C/C++ Users)

```bash
# Ensure SDL2 libraries are installed and linked properly
gcc -I<path-to-SDL2-include> -L<path-to-SDL2-lib> snake.c -o snake.exe -lSDL2 -lSDL2_image -lSDL2_mixer -lSDL2_ttf
```

**Note**: Make sure SDL2 DLL files are in your system PATH or in the same directory as the executable.

## 🎮 Controls

**This version features an AI-controlled snake!** 

There are no manual controls needed - just sit back and watch the AI play! The snake will automatically:
- Locate apples on the game board
- Navigate to reach them using optimal paths
- Avoid obstacles and self-collision
- Continuously hunt for the next apple

## 📸 Screenshots

_Coming soon! Screenshots and gameplay GIFs will be added here._

```
[Add your screenshots here]
- Screenshot 1: Game start screen
- Screenshot 2: AI snake in action
- Screenshot 3: High score achievement
```

## 👨‍💻 Credits

**Author**: [rahulkumar7189](https://github.com/rahulkumar7189)

**Libraries Used**:
- [SDL2](https://www.libsdl.org/) - Simple DirectMedia Layer
- SDL2_image - Image file loading
- SDL2_mixer - Audio mixing
- SDL2_ttf - TrueType font rendering

Special thanks to the SDL2 community and contributors!

```
MIT License

Copyright (c) 2025 rahulkumar7189

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

⭐ If you found this project interesting, please consider giving it a star!

🐛 Found a bug or have a suggestion? Feel free to open an issue!

🤝 Contributions are welcome! Fork the repository and submit a pull request.
