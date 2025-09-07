Workflow of the Emoji Riddle Game Program 
1. A predefined list of emoji sentences and their word mappings is stored in a list of 
dictionaries called emoji_hint_sentences. 
2. The program starts with a menu offering two options, to either start the game or exit the 
program. 
3. A welcome message and basic instructions are displayed. 
4. The players are prompted to enter the number of rounds (validated as a positive integer), 
then their names. 
5. In the event of duplicate names, this is resolved by appending “(2)” to the second one. 
6. The scores for both players are initialized to zero. 
7. For each round, a unique emoji sentence is randomly selected from emoji_hint_sentences 
(already-used ones are excluded). 
8. The sentence is displayed to the players. 
9. Each emoji in the sentence is presented one-by-one. 
10. For each emoji, the current player is asked to guess its meaning. 
11. The answer is checked and awarded a point if correct. 
12. Turn switches to the other player. 
13. After all rounds are completed, final scores are printed. 
14. If one player has more points, they are declared the winner, else it’s a tie. 
15. The game ends with a thank-you message, and the user is returned to the main menu. 
