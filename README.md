### Hi there 👋

#### Here you can see a brief summary of some programs I've worked on during this year of studying at "Kyiv School of Economics". So it can be my own work, or assignment, completed with a partner. Anyway, I have a complete understanding of the code, i.e., all algorithms, data structures, LINQ expressions etc.

### And, moving from the end, my last assignment, that I've done with Ivan Solomatin, was a misspelling corrector.

##### The idea is simple: user enters some text, program works on it, and gives suggestions to misspelled words.
##### For doing this program needs some correct words, in my case it's a SCOWL (Spell Checker Oriented Word List) with 168065 words in it.
##### The program works on the entered sentence in the following way:
  1. Sentence is splitted into words
  2. For each unfound in the SCOWL word, we use Damerau-Levenshtein algorithm to find five the most similar words, as algorithm Longest Common Subsequence not always gives us the best option.
  3. And finally program writes five recommendations for each misspelled word.

Example of work:
![alt text](https://photos.google.com/search/_tra_/photo/AF1QipPfEvxRdcS2pt0pd6tzgGFlmV_3b0oLxyuc14JD "That's it")
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
