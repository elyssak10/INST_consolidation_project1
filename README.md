# INST_consolidation_project1
run code in ?

•	The object of the game is to guess a secret word from a bank of words split into three categories: school, countries, fruit
The program will choose one word randomly from these categories. The user will have three tries to guess the final word, and the count score will go up by one everytime they either 
a) guess the word incorrectly
b) guess a letter incorrectly 
c) guess a letter that is in the word
Therefore, the lower the score the better!


-The game will welcome the user with a message personalized to their name, after user inputs name of choice

-As a hint, it will automatically tell the user what category the random word is from
   However, the user is not able to see the list of random words in each category and will not be able to see the random word
   
-As an additional hint, it will tell the user how many letters are in that word

-It will remind the user how many incorrect letter guesses/lives they have- 3

-The user must first guess a letter (CANNOT immediately guess the word)

   1. If the letter is not found in the word, it will increase the score count by 1, inform the user of that and ask the user to try again.
   2. If the letter is found in the word, it will still increase the score by 1 and will inform the user how many times the letter was found in the word. It will NOT tell them WHERE the letter is!


-Now that they have guessed the letter once they can begin guessing the final word 

-The code will now ask them if they want to guess

   1. if they say no it will retun to prompting them to guess another letter
   2. otherwise it will prompt them to guess the final word

- if they guess correctly it will: congratulate them, repeat the word, and give them their final score
  
-If the final word was incorrect it will inform them and will take note and let the user know of the 1st failed attempt

-The user will then be able to go back and continue to guess letters and will be asked each round if they would like to guess the word

-The program tracks how many letter guesses and how many word guesses each player makes.

-If after 3 incorrect guesses for the word the code will break and will inform the user that the game is over. It will tell them what the correct word was but will not give them a final score, as they have failed.

-The game does not keep track of the letters guessed

-The game does not remember how many times a person played or failed or keep track of their final winning scores

-The game does NOT “remember” and avoid any words it used before with a player
