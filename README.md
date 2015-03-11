# JSWheelOfFortune

This project requires you to develop a special puzzle web page. In the following you will only find some general ideas. Please use your wild imagination and creativity to make your project attractive and professional.

  * 1)      The web page shall contain a table with 2x50 cells nicely positioned on the page. Choose 20 of your favorite proverbs from famous proverbs, each as a string literal pre-stored in a JavaScript array. Randomly choose one from the 20 proverbs and have the content filled character-by-character in the cells of the table (once character per cell). Set the initial visibility of the characters as hidden (Hint: you may define each cell as a button or as a span element to make it responsible to the onclick event). Unoccupied cells must be displayed in relatively lighter color to look different from occupied cells.

  * 2)      Allow a user to reveal (flip) one letter by each click, and limit the revealed cells to a half of the total number of occupied cells.

  * 3)      When a user flipped a half of the occupied cells, a popup message shall immediately shows up, saying "You have no more letters to flip, please make your guess NOW!” (After the user confirming OK, a textarea immediately shows up waiting for the user's answer).

  * 4)      You shall allow a smart guy to guess before flipping a half of the letters of a proverb, e.g., always providing the "Make your guess NOW” button to receive early guess.

  * 5)      In either case (3 or 4), a textarea is then showed up for the user to type in his/her guess of the proverb (this textarea widget should not be prematurely displayed on the page).

  * 6)      Then, your web page checks and confirms whether the guess is correct or not. If the guess is incorrect, let the user choose to either continue (can try at most two more times) or give up, then reveals the puzzle (by flipping the remaining letters of the partially revealed proverb). If the guess is correct, then grades the user based on the number of allowed-to-flip characters that are still left un-flipped. For example, if a user has 3 allowed characters left un-flipped and provided a correct guess, then your webpage shall respond the user with "You are 3-star guesser!”

  * 7)      The user may choose to continue with the next proverb after putting a correct guess or giving up a difficult one. The next proverb will again be randomly chosen from the 20 proverbs.

  * 8)      Finally, you need to put a title for your game page, like "John's Proverb Puzzle Page". Also, provide a short description of the rules for playing this game, e.g., "To play this game, you can reveal no more than half of the characters of each proverb before make a guess. The more characters you left un-flipped before you make a correct guess, the more scores you will be awarded."
