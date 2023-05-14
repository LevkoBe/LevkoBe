### Hi there 👋

#### Here you can see a brief summary of some programs I've worked on during this year of studying at "Kyiv School of Economics". So it can be my own work, or assignment, completed with a partner. Anyway, I have a complete understanding of the code, i.e., all algorithms, data structures, LINQ expressions etc.

### And, moving from the end, my last assignment, that I've done with Ivan Solomatin, was a misspelling corrector.

The idea is simple: user enters some text, program works on it, and gives suggestions to misspelled words.
For doing this program needs some correct words, in my case it's a SCOWL (Spell Checker Oriented Word List) with 168065 words in it.
The program works on the entered sentence in the following way:
  1. Sentence is splitted into words
  2. For each unfound in the SCOWL word, we use Damerau-Levenshtein algorithm to find five the most similar words, as algorithm Longest Common Subsequence not always gives us the best option.
  3. And finally program writes five recommendations for each misspelled word.


Example of the work:

![alt text](https://lh3.googleusercontent.com/d6SDlOHm44hTq1tcXO8xMJChTgxKMWXiNMEaOUUtfrRb1mOIg_bbDh-oCLF8es9cByFFFteaWYCWxTbFgEZa37OR-6jxRe2F3u1XKPzGQExJGfgFiZyy6MVVDssF_tKxr9S3CXQQZATM4iozgrRDp_7RHUawPnWFfSG6sJH5Ix4ACFDrDPFY9bNAEtuDnmvXkG1bD_iqXH2n0RidpZGBxB7zGMPntVqua2KgxYzmwgmaRK4g9CAtiB9bQhEWNV8Jamp-4VSeOGxM5Sge8hnZnNFnPcYkCvMMUqBvWL5npSPpOTO-BGQuZPR3bJm_K3JJOxEiTr9jOOvrEbDn-r0ApyvSwDxPdziZnEAQAA_H5T5qqaEEOUY9mCuoJNYqbilGwf3NuhVaXdc5_nfSs3S17cJfUK6pIpdJDTaGlkyJJPV5kBcM2C88_0Sr6PLsHpyDRmYcQptXVbZXkTaTENcg9bg2AgdPgedALEIQIpZRHQ-tPeoMXhEdYp-EjAbcLsOcdE3qJirw_Zw2l4k7OqWXzTRM8PQeJ0fq1DaeB7ddT4i8VgtTNCBkdF2XLI5DnDOZ1jo7IWHZLSUruVzT4BGfdmnV9sZaquZtTPDSrxRb8eXwBDAgTysZb7uybZaAKD8VQDvEeC8kjnpz-562RplWYSRbHAZj9Z9Qz4wXWYXxrC0ql_3hsw_0mfQWYCYN5mvxtcmDuZH034-DGNplJOJbbeatqJdqSU0FC-8KARP6KJYdi_G6OtGct1lrU0ITGyRqtJ8IainVRcJBeENAF69TO1ZJntIsW8jbZCEEYDMdOJVILKM2rWVCiFB3XbAcEwQ4jmAjYiFnjBUDXcVysAlEUAjJf8gb4bpECSX0ZD5Atzt2vTZo6NyHs-owr0ikekrM9ExwFXuskT1EGmRrTEdiXv-FXHF6Og1V-ivp5a2SVz_k6PQ=w732-h375-s-no?authuser=0 "T")


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
