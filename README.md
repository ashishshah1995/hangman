# Hangman

The Hangman game written in Java

Hangman is a words guessing game for one player. This is command line application where user Input the answer while running the program. The program then prints out a row of dashes, one for each letter in the secret word, and asks the user to guess a letter. If the user guesses a letter that is in the word, the word is redisplayed with all instances of that letter shown in the correct positions, along with any letters correctly guessed on previous turns. If the letter does not appear in the word, the user is charged with an incorrect guess. The user keeps guessing letters until either (1) the user has correctly guessed all the letters in the word or (2) the user has made seven incorrect guesses.

# How to run the program
In your IDE of choice go to Run > Edit Configurations menu setting. Add any word to Arguments configuration and you can play Hangman through console

This is the code with comments.

To play:

$ git clone https://github.com/ashishshah1995/hangman
$ clear && javac Hangman.java && java Hangman <5 letter word> 
(dont include the <> when giving the 5 letter word)

Have fun!
