## Sentence Analysis Algorithm
Overview
The Sentence Analysis Algorithm is a program designed to analyze a given sentence. It calculates and provides information about the sentence, including its length, word count, and the count of vowels.

### Algorithm Details
The algorithm operates as follows:

1.Variable declaration and Initialization of counters
- STRING sentence;
- INTEGER length = 0;
- INTEGER wordcount = 0;
- INTEGER vowelcount = 0;
- STRING vowel := "aeiouAEIOU";
- STRING words[];

2. Calculate Sentence Length:
Iterate through each character in the sentence to find the length of the sentence.
Preprocess Sentence:

- Replace full stops with blank spaces.
- Remove leading and trailing spaces.
- Split Sentence into Words:

3. Split the sentence into an array of words.
Word Count and Vowel Count:

4. Iterate through each word in the array.
Increment the word count for each non-empty word.
For each character in a word, check if it is a vowel and increment the vowel count accordingly.
Output Results:

5. Display the calculated results, including the length of the sentence, word count, and vowel count.
Usage

### To use the Sentence Analysis Algorithm, follow these steps:

1. Provide a sentence as input.
2. Execute the algorithm.

### Summary
1. Input: Read a sentence.
2. Length Count: Iterate through each character in the sentence to find the length of the sentence.
3. Sentence Modification: replaces the full stop with a blank space and removes leading and trailing whitespaces.
4. Word Count: Split the sentence into an array of words and iterate through each word, incrementing the word count.
5. Vowel Count: For each non-empty word, iterate through each character to count vowels and increment the vowel count.
6. Output: Display the length of the sentence, the number of words, and the number of vowels.

### Prerequisites
None

### License
This project is licensed under Elaine .Muhombe
