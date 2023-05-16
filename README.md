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

![alt text](https://lh3.googleusercontent.com/pw/AJFCJaWxuS9sW1EhislIvcqfHT17SWfiubTz6-id-ySMthDqy4fneF5t0wpmeTHIQ9nSxKhzECLrRf6bHuHq_07pzxDJr4ilVbnfe9BZekfZJoDCcmumtL5uQvpJnoHn0DuHwTPipUpBSL8KWyjifboJbXiJLugd1VeSY_oMSWSCApN_90h43kgkG13mWxLyy1V994nPMdvz97GaHOsqy2BMir7WQhB_OOk2n7dk28Xr0k7mpzE0-JL2wq-p5ztVKVW-yfgi3tgri74EpF_4fhUAKSFRcpXfShuUkhSws-YLwkQYJ-LRENlQ5yu3oUlpGbTDUq0D3wPaNpuejkESmTyscMs9y6StcUbsDZD_R9iTCcbxTMRQ_-mBU-_y3YsA7ndNlmaV8bwVRx9WuJ4PTTRGCsT5r9gssfIwz2WiSylr_8x-GJ287Q-oL5qE_8OGz0LY7BHGVDFZ5wggRfEJf5Ab8A0-tG6bBCUZk7__EEhgRxc7Kn2EYGcXhW2mWu0McyRSfIgM5RRfbReuhJhz3BJQiQjn1UBU_VcDgh7be4lpr9Lk4AZpBGCo0bXYUSGjw2YQbS8tfj31qm-pS5S19ypMg--lrOEPcZFjLHPPqNtPEymAOJqEN0--2pn5CBQN2kz2BQTGGMWnFIL327tRX0ccTPFyIH2Kr0XCUOJaTKENdgv6LKKfkc1Wwd5pvYlIzKAQkPzXNVjMpghR-l5hgrtMuPUHLO1fFM8A4ofzhs100qNYKqGpImF0I0SAuIVn9nO1m_ShYhpDm-6HnGNJOSQF4PdpiKOKiWnAfuQgLIwDBOmn_m0qAQY6wwpmu75YYn460KywZHb-JX22HlXpeQoAWZGyM4TBUX194VAY7Eg6ys9VuDIu-k3gTRbMM17Or6dkVkWs9vUrU0W8weSOfrhv5g=w732-h375-s-no?authuser=0 "T")
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
