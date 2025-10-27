# Zookeeper — Console Habitats (Jetbrains project)

Here's the link to the project: https://hyperskill.org/projects/98

Check out my profile: https://hyperskill.org/profile/386978127

A tiny console application that simulates camera feeds from different animal habitats. This is a JetBrains Academy learning project to practice lists, loops, user input, and basic program structure in Python.

## Features

- Display ASCII-art "camera" views for a set of animals (camel, lion, deer, goose, bat, rabbit).
- Simple menu driven by user input (enter habitat number or `exit`).
- Lightweight, dependency-free — runs on Python 3.

## Learning goals

- Work with lists to store multiple items.
- Use loops and conditionals to control program flow.
- Read user input and handle simple input validation.
- Practice building a small, interactive console app.

## Prerequisites

- Python 3.6 or later installed.

## Running the program

1. Clone or download the repository.
2. From the project directory run:

```bash
python zookeeper.py
# or
python3 zookeeper.py
```

(Replace the filename above if your main script uses a different name.)

## Usage example

When you run the program you'll see a prompt like:

```
Please enter the number of the habitat you would like to view:
```

Enter a number between 0 and 5 to view an animal habitat (0 — camel, 1 — lion, 2 — deer, 3 — goose, 4 — bat, 5 — rabbit). Enter `exit` to quit the app.

Example session:

```
Please enter the number of the habitat you would like to view: 0
Switching on the camera in the camel habitat...
  ___.-''''-.
 /___  @    |
 ...
Look at that! Our little camel is sunbathing!

Please enter the number of the habitat you would like to view: exit
See you later!
```

## Project structure

- zookeeper.py — main script containing the habitats list and interactive loop.
- README.md — this file.