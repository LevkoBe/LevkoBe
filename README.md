### Hi there 👋

#### Here you can see a brief summary of some programs I've worked on during previous year of studying at "Kyiv School of Economics". So it can be my own work, or assignment, completed with a partner. Anyway, I have a complete understanding of the code, i.e., all algorithms, data structures, LINQ expressions etc.

### 1. And, moving from the end, my last assignment, that I've done with Ivan Solomatin, was a misspelling corrector.

The idea is simple: user enters some text, program works on it, and gives suggestions to misspelled words.
For doing this program needs some correct words, in my case it's a SCOWL (Spell Checker Oriented Word List) with 168065 words in it.
The program works on the entered sentence in the following way:
  1. Sentence is splitted into words;
  2. For each unfound in the SCOWL word, we use Damerau-Levenshtein algorithm to find five the most similar words, as algorithm Longest Common Subsequence not always gives us the best option;
  3. And finally program writes five recommendations for each misspelled word.


Example of the work:

![alt text](https://res.cloudinary.com/dcxd4mjy0/image/upload/v1684241975/example1_wsatpm.png "Correcting mistakes")
>Longest common substring, longest common subsequence and Levenshtein algorithms are only three examples of problems solved by Dynamic Programming, which is very exciting at least because of its way of managing some difficult problems in easy and interesting way! 

## 2. The second code I'll talk a little about is "Huffman coding"
And I must say, I love that one! It's about another way to write files, where each sign, each letter may have a different number of digits. At first it sounded strange, but actually it isn't!
Huffman coding's idea is the next: to reduce the size of a given file we can simply code each letter not by 8, but with 7, 6, or even 1 bit, depending on how often this letter appears in the file.
And here is short explanation of how the program works:
  1. Reading the file to count how often each character appears in a file;
  2. Building Huffman tree of character's frequencies;
  3. Writing a smaller file!

![alt text](https://res.cloudinary.com/dcxd4mjy0/image/upload/v1684405820/ex2_rrzg1g.png "Work with a file")
>The way of making smaller codes to letters names prefix coding and it works because each character has its unique code, its own "place in a tree".

## 3. Realization of hash tables
In this assignment the task was to create such a data structure as a dictionary to acquire a better understanding of how they work. And after implementing the next structures and functions:
  1. Key-value pair;
  2. Linked list;
  3. Hash-function;

We can ultimately create a dictionary.
And its key features are constant time of finding, deleting and in most cases even adding elements. It's because all we need is just to calculate the hash of our key and we immediately get the number of the bucket where our value should be. But sometimes we need to increase the number of buckets, and then all our key-value pairs have to get another hash, so the time complexity becomes linear, as we need to recalculate the hash for all N keys. 

## 4. Dijkstra and A* algorithms
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
