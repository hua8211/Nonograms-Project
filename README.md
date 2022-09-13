# Nonograms-Project

Requirements

If the user left-clicks on a cell, that cell becomes shaded. But, if they right-click on a cell, that cell becomes eliminated---just like the reference implementation. There must be a visual difference between a shaded and an eliminated cell. A cell cannot be both shaded and eliminated. Cells must be clearly marked, so the user can tell which cell they are selecting.

If the user left-clicks on an already-shaded cell, that cell should return to a blank state. If the user right-clicks on an already-eliminated cell, that cell should return to a blank state.

After each move, your app must check to see if the user solved the puzzle. If so, the UI must visually update to let the user know that they completed the puzzle. The puzzle is "solved" if the shaded squares match the clues. Non-shaded squares do not need to be labeled "eliminated" in order to solve the puzzle.

The UI must include a clearly visible and labeled "reset" button that will clear all the cells in the board and let the user start over from a blank state.

The starter code contains a pre-coded library of 5 puzzles to solve. The UI must provide clearly visible and labeled buttons to go to the next puzzle, to go to the previous puzzle, and to jump to a random puzzle. The "previous" button should not cause an uncaught exception if the user accidentally presses it on the first puzzle. Similarly, the "next" button should not cause an uncaught exception if the user accidentally presses it on the last puzzle.

The library of puzzles is a List, which means the puzzles are indexed. Your app must clearly display the index of the active puzzle in the library and how many puzzles are in the library in total. The displayed index should start from one, not zero. In other words, the first puzzle in the List (at index 0) should be displayed as "puzzle 1 of 5" to the user.

Your app must support arbitrary-sized boards with different widths and heights. To demonstrate this functionality, the provided pre-coded library of puzzles includes puzzles of at least two different sizes.
