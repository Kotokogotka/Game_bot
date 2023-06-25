# Bot Readme

This is a bot that allows you to play the game "Rock, Paper, Scissors" with it.

## Commands

- `/start`: Initiates the game and provides a brief introduction. If you forget the rules, you can use the `/help` command.
- `/help`: Displays the rules of the game.

## Handlers

- `/start` handler: Triggered by the `/start` command. Sends a greeting message and asks if the user wants to play the game.
- `/help` handler: Triggered by the `/help` command. Provides information about the rules of the game.
- "Yes" answer handler: Triggered when the user agrees to play the game. Sends a confirmation message and displays the game buttons.
- "No" answer handler: Triggered when the user declines to play the game. Sends a message expressing regret.
- Game button handler: Triggered when any of the game buttons ("Rock," "Paper," or "Scissors") are pressed. Sends the bot's choice and determines the winner of the game.

## Lexicon

The following dictionary contains the text messages used in the bot:

- `/start`: Greeting message with an invitation to play the game.
- `/help`: Explanation of the game rules.
- `rock`: Text representation of the "Rock" choice.
- `paper`: Text representation of the "Paper" choice.
- `scissors`: Text representation of the "Scissors" choice.
- `yes_button`: Text for the "Yes" button.
- `no_button`: Text for the "No" button.
- `other_answer`: Error message for unrecognized user input.
- `yes`: Confirmation message after the user agrees to play the game.
- `no`: Message expressing regret after the user declines to play the game.
- `bot_won`: Message displayed when the bot wins the game.
- `user_won`: Message displayed when the user wins the game.
- `nobody_won`: Message displayed when the game ends in a draw.
- `bot_choice`: Label for the bot's choice in the game.
