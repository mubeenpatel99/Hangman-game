# Hangman-game
Hangman is a paper and pencil guessing game for two or more players. One player thinks of a word, phrase or sentence and the other(s) tries to guess it by suggesting letters or numbers, within a certain number of guesses.
The following example game illustrates a player trying to guess the word hangman using a strategy based solely on letter frequency. As the player continues, a part of the stick figure on the noose is added. Once a full body is drawn, the game is over, and the player lost.

0	
 // refer image Hangman-0.png
Word:	hangman
Guess:	E
Misses:	
1	
// refer image Hangman-1.png
Word:	_ _ _ _ _ _ _
Guess:	T
Misses:	e
2	

// refer image Hangman-2.png
Word:	_ _ _ _ _ _ _
Guess:	A
Misses:	e, t
3	

// refer image Hangman-2.png
Word:	_ A _ _ _ A _
Guess:	O
Misses:	e, t
4	

// refer image Hangman-3.png
Word:	_ A _ _ _ A _
Guess:	I
Misses:	e, o, t
5	

// refer image Hangman-4.png
Word:	_ A _ _ _ A _
Guess:	S
Misses:	e, i, o, t
6	

// refer image Hangman-5.png
Word:	_ A _ _ _ A _
Guess:	N
Misses:	e, i, o, s, t
7	

// refer image Hangman-5.png
Word:	_ A N _ _ A N
Guess:	R
Misses:	e ,i, o, s, t
8	

// refer image Hangman-6.png
Word:	_ A N _ _ A N
Guess:	
Misses:	e, i, o, r, s, t
The guessing player has lost this game as the diagram had been completed before all the letters were guessed.
