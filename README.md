Readme File for Algorithm Checkpoint
Description
This algorithm is designed to analyze a given input sentence and provide information about its structure. It counts the total number of words, vowels, and characters in the sentence. The algorithm utilizes a combination of loops, conditional statements, and switch cases to iterate through the input sentence and keep track of relevant counts.

Algorithm Structure
Variables
sent (STRING): Variable to store the input sentence.
first (INTEGER): Variable to track the position in the sentence.
totalWords (INTEGER): Variable to count the total words (initialized to 1 for the first word).
totalVowels (INTEGER): Variable to count the total vowels.
totalChar (INTEGER): Variable to count the total characters (initialized to 1 for the first character).
Main Logic
Read Input: The algorithm starts by reading the input sentence from the user.

Loop Through Sentence:

The algorithm uses a WHILE loop to iterate through the characters of the sentence until a period ('.') is encountered, marking the end of the sentence.
Word Count:

The algorithm increments the totalWords variable each time a space character is encountered, indicating the start of a new word.
Vowel Count:

A SWITCH statement is used to check each character against the vowels (a, e, i, o, u). If a match is found, the totalVowels variable is incremented.
Character Count:

The totalChar variable is incremented for each character in the sentence.
Display Results:

Finally, the algorithm displays the total word count, total vowel count, and total character count.
Usage
Run the algorithm and provide a sentence as input.
The algorithm will process the input and display the total word count, total vowel count, and total character count.