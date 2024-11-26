# gowords
A Command Line Interface (CLI) implementation of the word game **wordle** written in Go using the **Bubble Tea TUI** framework.

The game is to guess a secret work of 5 or more characters within a limited number of attempts. The number of attempts depends on the diffiduclty level.

# Features
* Secret Word Guessing Game
* Number of attempts allowed is based on difficulty level
* Feedback on guesses:
  * Letter is correct: Green
  * Letter is in the secret word: Yellow
  * Letter is missing in the secret word: Red
* Difficulty Level
  * Newbie: Seven (7) Attempts
  * Beginner: Six (6) Attempts
  * Intermediate: Five (5) Attempts
  * Advance: Four (4) Attemps
  * Expert: Three (3) Attempts

# Future Features
* Ability to Add and Remove words from Word List
* Score Boards for multiple players
  * Remote DB to store Players and Scores
* Stats tracked by Words and Players

# Getting Started

## Prerequisites
* Go 1.23
* Bubble Tea TUI

## Installation

1. Clone the Repository
```
git clone https://github.com/coraxwolf/gowords
cd gowords
```

2. Compile TUI
```
make build
./bin/gowordle
```

## Contribution

1. Run Tests
```
make tests
```

2. Check Test Coverage
```
make coverage
```


