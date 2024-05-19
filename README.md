# WordleBot
This project includes a fully capable Wordle Console Application. Additionally there is a "WordleBot" that can play the game on it's own or make guesses for you. Press 'h' in the Main Menu to understand how to play the game.

For feedback on guesses, there is a function simply called get_result that takes the guess and the target word, and outputs 0's, 1's, and 2's to represent the correctness of each letter in the guess. This function is not as straightforward as it seems, as it has to account for the fact that the same letter can be used multiple times in the guess word and the target word.

The WordleBot can take this output, and begin to deduce the possible words that the taget word could be. Again, this is not as straightforward as it seems, because a '0' in the output does not necessarily mean that letter is not in the target word (specific scenario).

The program will keep track of all scores received by the bot and the user throughout that runtime, and you can view and compare the statistics with an ASCII bar graph from an option in the Main Menu.