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