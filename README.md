# Connect-Four-Game
![Start Shot](https://github.com/user-attachments/assets/3e7da981-09d4-493d-937d-0e276d88e002)
![Win Shot 2](https://github.com/user-attachments/assets/ecaa7db3-41ad-4bb2-af79-75ed7d4f62a9)
![Win Shot](https://github.com/user-attachments/assets/cd4d4369-f8aa-4151-9a55-1da71892425d)

Key functionalities:

    Player Setup:
        Prompts players to enter their names.
        Assigns colors (blue for player 1, red for player 2).

    Game Logic:
        Turn Management: Alternates between players.
        Chip Placement: Determines the lowest available row in a selected column and places a chip of the current player's color.
        Win Condition Checks:
            Horizontal win: Checks for four consecutive chips of the same color in a row.
            Vertical win: Checks for four consecutive chips of the same color in a column.
            Diagonal win (both directions): Checks for four consecutive chips of the same color diagonally.
        Game End: Declares the winner and displays a message.

    UI Interaction:
        Click events on the game board cells trigger the chip placement and win condition checks.
        The game board is dynamically updated to reflect the current state of the game.

Additional Features:

    Color Management: Functions to change and retrieve the color of a specific cell.
    Bottom Row Check: Determines the lowest available row in a column.

This code provides a solid foundation for a Connect Four game, handling player turns, win conditions, and UI interactions.


 ## How to Play

    Run the Game: Download and run the code on your preferred IDE.
    Take Turns: Players take turns dropping their colored discs into the grid.
    Win the Game: The first player to connect four of their discs in a row (horizontally, vertically, or diagonally) wins.

# How to Run:
Just download the code and run on your preferred IDE.
