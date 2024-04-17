# INST_consolidation_project1
run code in ?
•	The object of the game is to guess a secret word from a bank of words split into three categories: school, countries, fruit
The program will choose one word randomly from these categories.

1. The game will welcome the user with a message personalized to their name, after user inputs name of choice
2. As a hint, it will automatically tell the user what category the random word is from
However, the user is not able to see the list of random words in each category and will not be able to see the random word
3. As an additional hint, it will tell the user how many letters are in that word
4. It will remind the user how many incorrect letter guesses/lives they have- 3
5. The user must first guess a letter (CANNOT immediately guess the word)
   If the letter is not found in the word, it will increase the score count by 1, inform the user of that and ask the user to try again.
If the letter is found in the word, it will still increase the score by 1 and will inform the user how many times the letter was found in the word. It will NOT tell them WHERE the letter is!

Now that they have guessed the letter once they can begin guessing the final word 
The code will now ask them if they want to guess
-if they say no it will retun to prompting them to guess another letter
-otherwise it will prompt them to guess the final word

If the user guesses the correct final word, the code will congratulate them
Otherwise after three incorrect letter guesses the code will not allow the user to guess again.. instead it will inform them of what the correct word was 

   
* right now the code does not keep track of the letters guessed
* right now the code does not have a point system

The game does NOT “remember” and avoid any words it used before with a player
