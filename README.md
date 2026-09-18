# Sea Battle

A graphical Battleship game developed in **C++ using the Qt framework**.

## Overview

Sea Battle is a desktop-based Battleship game developed as a C++/Qt project. The project includes the implementation of the game logic, graphical user interface, ship placement, AI gameplay, and online multiplayer functionality with an integrated chat system.

The project was developed to gain practical experience with **Object-Oriented Programming, GUI development, and network programming**.

## Features

* Graphical user interface built with Qt
* Battleship game logic
* Interactive ship placement
* Gameplay against an AI opponent
* Online multiplayer gameplay
* Integrated chat functionality
* Sound effects and background music
* Visual animations and game effects
* User login and registration

## Technologies

* C++
* Qt
* Qt Widgets
* Qt Designer
* qmake
* Network programming
* JSON

## Main Components

The project is organized into several components responsible for different parts of the application:

* `main.cpp` – Application entry point
* `mainwindow.*` – Main application window
* `gameboard.*` – Game board functionality
* `ship.*` – Ship-related functionality
* `dialoggameai.*` – AI game interface
* `dialogclient*.cpp/h` – Client-side multiplayer components
* `dialogserver*.cpp/h` – Server-side multiplayer components
* `dialogsetgameboard.*` – Game board setup
* `musicplayer.*` – Audio playback
* `user.*` – User-related functionality
* `validator.*` – Input validation
* `hashpassword.*` – Password-related functionality
* `*.ui` – Qt user interface files
* `*.qrc` – Qt resource files

## How to Run

### Requirements

* Qt
* Qt Creator
* A compatible C++ compiler

### Steps

1. Clone the repository:

```bash
git clone https://github.com/mamadhosein4455/Sea-Battle.git
```

2. Open `EntryPage.pro` in Qt Creator.

3. Configure the project with a compatible Qt kit and C++ compiler.

4. Build the project.

5. Run the application.

