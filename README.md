# Scrabble Aid 1

Python allows you to easily convert a string to a list of characters.  Consider the code below:
```
a = 'hello'
b = list(a)
```
After this code executes, the value of b will be:
```
['h', 'e', 'l', 'l', 'o']
```
The popular board game Scrabble is played by randoming drawing seven letters from which a player must form words.  **Write a function canSpell() that helps a player determine whether the letters she has drawn can be used to spell a particular word.** 
- The function accepts two strings.  
- The first is a string of characters representing the drawn letters.  
- The second represents the word the user wants to spell out.   
- The function returns *True* if the word can be spelled out with the available letters and *False* otherwise.  Thus, if the function is passed the strings 'hetrelx' and 'tree', the function returns *True* because 'tree' can be spelled out with the given letters.  The function returns *False* when given the same letters and the word 'text' because, while all the letters in 'text' appear in the letters string, only one letter 't' is available.  
- Write a program that prompts the user for the string of letters and the word to test.  


**Your program should use your canSpell() function to determine whether or not the word can be spelled out with the available letters.**

## Here is an example run:

```
Enter the available letters: hetrelx
Enter the word you wish to write: text
Sorry, that word cannot be spelled out :(
```
