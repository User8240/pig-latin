# _Pig latin_

#### By _**Grace Kostanich & Derrak Richard**_

#### _A README file containing a set of practice tests to create a webpage that changes words in a sentence to pig latin!_

## Technologies Used

* _Markdown_

## Description

_This README is written in Markdown_

## Setup/Installation Requirements

* _Fork project to your own GitHub repository_ 
* _Clone that repository to your desktop_
* _Open README.md file if you'd like!_

## Known Bugs

* _No known issues_

## License

_MIT License_

Copyright (c) _6/8/2022_ _Grace Kostanich & Derrak Richard_

----------------------------------------------------------------------
Describe: pigLatinVowelFirst()

Test: "It will add 'way' to the end of words that begin with a single vowel (a)."
Code: pigLatin("a");
Expected Output: "away"

Test: "It will add 'way' to the end of words that begin with an array of vowels."
Code: pigLatin("u");
Expected Output: "uway"

Test: "It will add 'way' to the end of words that begin with a vowel, regardless of case."
Code: pigLatin("O") and pigLatin("o");
Expected Output: "Oway" and "oway"


Describe: pigLatinConsonateFirst()

Test: "Slice off and store letter(s) from word(s) that start with not a vowel right before the first vowel in word"
Code: pigLatinConsonateFirst("code");
Expected Output: "ode"

Test: "It will append stored letter(s) to end of word"
Code: pigLatinConsonateFirst("code");
Expected Output: "odec"

Test: "It will append "ay" end of word"
Code: pigLatinConsonateFirst("code");
Expected Output: "odecay"
