# SnowmanProjectsCSP2
Snowman Game
A command-line Snowman game where players guess a random word with limited guesses.

Features:

difficulty levels

Random word API

Hint system

Points and leaderboard

Error handling


How It Works
The game gets a random word from an API. If the API does not work, it uses a backup word list.
Players guess letters, and correct letters appear in the word. Each guess lowers the number of guesses remaining.
The player wins by guessing the whole word before running out of guesses.

Challenges I Ran Into
One challenge was that the word that the API chose woul not always be connected . I fixed this by using try/except and a backup word list.

What I'd Improve With More Time
I would add more words or and save the leaderboard.

Made by Inam Ahmed https://github.com/Inam-Ahmed
