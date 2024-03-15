### Hi there 👋

#### Here you will see a summary of some programs I've worked on during the last two years of studying at the University "Kyiv School of Economics". So it can be my work, or assignments, completed with a partner. In any case, I have a thorough understanding of the code, i.e., all algorithms, data structures, etc.

## Recently I've written a program that implements [chat application](https://github.com/LevkoBe/GroupChat) in C++ using TCP connection with sockets
The link to the application with further description of it is here. One small screenshot of how it works:
![image](https://github.com/LevkoBe/LevkoBe/assets/118983753/285af220-3440-4f9a-ac1e-c3e44165caf5)

## Before that, I implemented code for the [Tanks game](https://github.com/LevkoBe/TanksGame):

This game is a tank battle game where players control a tank and engage in combat with enemy tanks while navigating through a maze-like environment. The objective is to defeat all enemy tanks and clear the level.

https://github.com/LevkoBe/TanksGame/assets/118983753/9b19883a-1db3-428c-90e8-cea0679d55d5

### Next, an assignment that I did with Ivan Solomatin in the first year of study in Kyiv School of Economics: misspelling corrector.

The idea is simple: the user enters some text, the program works on it and gives suggestions for misspelled words.
For doing this program needs some correct words, in my case, it's a SCOWL (Spell Checker Oriented Word List) with 168065 words in it.
The program works on the entered sentence in the following way:
  1. Sentence is split into words;
  2. For each unfound in the SCOWL word, we use the Damerau-Levenshtein algorithm to find five of the most similar words, as the algorithm Longest Common Subsequence not always give us the best option;
  3. Finally the program writes five recommendations for each misspelled word.


Example of the work:

![alt text](https://res.cloudinary.com/dcxd4mjy0/image/upload/v1684241975/example1_wsatpm.png "Correcting mistakes")
>Longest common substring, longest common subsequence, and Levenshtein algorithms are only three examples of problems solved by Dynamic Programming, which is very exciting at least because of its way of managing some difficult problems easily and interestingly! 

## The second code I'll talk a little about is "Huffman coding"
And I must say, I love that one! It's another way to write files, where each sign and each letter may have a different number of digits. At first, it sounded strange, but it isn't!
Huffman coding's idea is the next: to reduce the size of a given file we can code each letter not by 8, but with 7, 6, or even 1 bit, depending on how often this letter appears in the file.
Here is a short explanation of how the program works:
  1. Reading the file to count how often each character appears in a file;
  2. Building Huffman tree of character's frequencies;
  3. Writing a smaller file!

![alt text](https://res.cloudinary.com/dcxd4mjy0/image/upload/v1684405820/ex2_rrzg1g.png "Work with a file")
>The way of making smaller codes to letter names is prefix coding and it works because each character has its unique code, its own "place in a tree".

## Realization of hash tables
In this assignment, the task was to create such a data structure as a dictionary to acquire a better understanding of how they work. After implementing the next structures and functions:
  1. Key-value pair;
  2. Linked list;
  3. Hash-function;

We can ultimately create a dictionary.
Its key features are a constant time of finding, deleting, and in most cases even adding elements. It's because all we need is to calculate the hash of our key and we immediately get the number of the bucket where our value should be. But sometimes we need to increase the number of buckets, and then all our key-value pairs have to get another hash, so the time complexity becomes linear, as we need to recalculate the hash for all N keys. 

## Dijkstra and A* algorithms
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
