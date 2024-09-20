# Matchmaker-
This Python code creates a simple memory matching game using the Tkinter library for the GUI. The player clicks buttons to reveal hidden symbols and tries to match pairs of identical symbols. The game shuffles a set of symbols and places them on a grid of buttons.


Key Features:
1.Grid Layout: The game board consists of a 6x4 grid of buttons, each hiding a random symbol from a predefined set of 24 symbols (12 unique pairs).
2.Symbol Matching: When the player clicks a button, the symbol underneath is revealed. If two clicked symbols match, both buttons are disabled. If they don't match, the symbols are hidden again after a short delay.
3.Game Logic: The show_symbol() function controls the game flow, checking if the clicked symbols match or not, and handles disabling buttons for correct matches.
