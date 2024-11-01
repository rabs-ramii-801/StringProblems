﻿# StringProblems
 # StringSolver

`StringSolver` is a Java-based utility program with multiple string manipulation functionalities. It provides methods to check if a string is a palindrome, count vowels, consonants, and spaces, reverse a string, remove vowels, find character frequencies, identify non-repeating characters, determine the most frequently occurring character, and remove duplicates from a string.

## Features

1. **Palindrome Check**: Determines if a given string is a palindrome.
2. **Vowels, Consonants, and Spaces Count**: Counts the number of vowels, consonants, and spaces in a string.
3. **Remove Vowels**: Returns the string after removing all vowel characters.
4. **Reverse String**: Reverses the input string.
5. **Character Frequency Count**: Counts the frequency of each character in the string.
6. **Non-Repeating Characters**: Identifies characters that occur only once in the string.
7. **Max Occurring Character**: Finds the character with the highest frequency in the string.
8. **Remove Duplicates**: Removes all duplicate characters from the input string.

## Getting Started

### Prerequisites

- Java 8 or above

### Running the Application

1. Clone the repository or download the `StringSolver.java` file.
2. Open the file in your preferred Java IDE or editor.
3. Compile and run the program using the following commands:

    ```sh
    javac StringSolver.java
    java StringSolver
    ```

4. Enter any string at the prompt to see the various operations performed on it.

## Usage

Below is an example of running `StringSolver`:

```plaintext
Enter the string: programming

The given string is: Not Palindrome

Total no. of vowels consonants and spaces are : vowels:3 consonant:8

String after removing all vowels is: prgrmmng

String after reversing it is: gnimmargorp

Frequency of each characters in the string are: p:1 r:2 o:1 g:2 a:1 m:2 i:1 n:1

Non repeating characters in the string are: p o a i n

The maximum occurring character in the input string is: r

String after removing duplicates is: progamin


Functions


isPalindrome(String str): Returns true if str is a palindrome, false otherwise.

countVowelsConsonantSpaces(String str): Returns a HashMap<String, Integer> with counts for vowels, consonants, and spaces.

removeVowels(String str): Removes all vowels from str.

reverseString(String str): Reverses str.

frequencyCount(String str): Returns a HashMap<Character, Integer> containing each character's frequency in str.

nonRepeatingChars(String str): Returns a list of non-repeating characters in str.

maxOccuringChar(String str): Returns the character with the highest occurrence in str.

removeDuplicates(String str): Removes duplicate characters from str.

Contributing

Feel free to contribute to this project by submitting issues or pull requests.


License

This project is licensed under the MIT License.

