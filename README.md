Initialize Counters:

Three counters are initialized:
lengthCounter: To count the length of the sentence (number of characters).
wordCounter: To count the number of words in the sentence.
vowelCounter: To count the number of vowels in the sentence.
Define Vowels:

A set named vowels is defined, containing the vowels 'a', 'e', 'i', 'o', 'u', 'A', 'E', 'I', 'O', 'U'. This set will be used to check if a character is a vowel.
Iterate Through Each Character:

A loop is set up to iterate through each character in the input sentence.
Increment Length Counter:

For every character, the lengthCounter is incremented by 1, counting the length of the sentence.
Check for Space to Count Words:

If the character is a space, it is assumed to be a word separator, so the wordCounter is incremented by 1.
Check for Vowels:

If the character is in the vowels set, it is considered a vowel, and the vowelCounter is incremented by 1.
Adjust Word Counter for Last Character:

Since the last character is a period (point), it is not counted as a space-separated word. Therefore, after the loop, 1 is added to wordCounter to account for the last word.
Display Results:

The algorithm then prints or outputs the results:
"Length of the sentence:", lengthCounter
"Number of words in the sentence:", wordCounter
"Number of vowels in the sentence:", vowelCounter
This algorithm ensures that each character is considered individually, and the three counters keep track of the specified metrics. It's a general algorithm written in pseudocode, and you can adapt it to any programming language of your choice.
