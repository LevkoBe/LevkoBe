### Hi there 👋

#### Here you can see a brief summary of some programs I've worked on during this year of studying at "Kyiv School of Economics". So it can be my own work, or assignment, completed with a partner. Anyway, I have a complete understanding of the code, i.e., all algorithms, data structures, LINQ expressions etc.

### 1. And, moving from the end, my last assignment, that I've done with Ivan Solomatin, was a misspelling corrector.

The idea is simple: user enters some text, program works on it, and gives suggestions to misspelled words.
For doing this program needs some correct words, in my case it's a SCOWL (Spell Checker Oriented Word List) with 168065 words in it.
The program works on the entered sentence in the following way:
  1. Sentence is splitted into words;
  2. For each unfound in the SCOWL word, we use Damerau-Levenshtein algorithm to find five the most similar words, as algorithm Longest Common Subsequence not always gives us the best option;
  3. And finally program writes five recommendations for each misspelled word.


Example of the work:

![alt text](https://res.cloudinary.com/dcxd4mjy0/image/upload/v1684241975/example1_wsatpm.png "T")
>Longest common substring, longest common subsequence and Levenshtein algorithms are only three examples of problems solved by Dynamic Programming, which is very exciting at least because of its way of managing some difficult problems in easy and interesting way! 

## 2. The second code I'll talk a little about is "Huffman coding"
And I must say, I love that one! It's about another way to write files, where each sign, each letter may have a different number of digits. At first it sounded strange, but actually it isn't!
Huffman coding's idea is the next: to reduce the size of a given file we can simply code each letter not by 8, but with 7, 6, or even 1 bit, depending on how often this letter appears in the file.
And here is the way the program works:
  1. Reading the file to count how often each character appears in a file;
  2. Build Huffman tree of character's frequencies;
  3. Write a smaller file!
>The way of making smaller codes to letters names prefix coding and it works just because each character has its unique code, its own "place in a tree".
<!--
**LevkoBe/LevkoBe** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
