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
![alt text](https://lh3.googleusercontent.com/HPsvmSmoIlX9eL8FT8kBVpOFjWTypDmXMAYrfpMnh9oxsl13iCPPMee3HL5PBb0lf3VCej03OQLlDifUSP9Y0RapUCyq8rNuJBeS2M7IhWC8RG1ODVnwBeEAc_q-sPS2AB_ohdgQy3pt3ZzDarVb7WU6Uutr909RXXF-ZYyz5ySKHnvJGSVs9MyaxJ7FKqPjvclCAOscPSyhnyCTvFj0heJXgBVIQYxFxkKFQo-DYLpAoLJhpgVTnoIx1mplkHod_vot3qZSoJr6M4-y0xF9Ex85VCXQmm1GbNDReVKQLsWVg4t9VqRv6C_fX3NMwawHccjmBYGA2sGXDluXZrhl640zlS7fZva-J7Xr14UaUSXWr0SO-VDK04z3kNMPW17VnXOaThXsj5AIJJz1CZQ9dSOu6BKO25mMoGut-i1D34vuruDsDOAv2U-boHLVNUvt52mMAVwyYnO7oN-mTFrJWaz94oDx71Ju50iodvDIeknE86FvdiMMzfgx6LwoDIguXCtdFrJ96DimJgPgU5Wi9Xh2KjE13k9ilpnCSEZQ4vQB_nsbcUuR-PFz_w651f5Je1-nFpgBjufsEdfrtDF-9F30ScVezK8tkhN0YB0EmHh6snFs_xLn9XaSLPSFaVNWIbJ2p9o-FVKpbV6Dsnj7Vi8CpNcqSJ0E5UjZHF87R5NoE59chmK4mXZ8heIG2HKVSPFgDZTWqnIltgVcU_fDlDwYwy3NUv2FrgrWBNcegt8npt0Ydat6h-BmqYp2mipy1UNk3W3Ls8rpyg3RVXw_Aj72XBcxtU6BSe1PomljrzHdFWR-M5z6n_h7nlvuTT5g7rf9A2Qc7DXYOo3p6KN7IUvmOYd-nLgB1nvQ7xEm_wiDiCcxI7uCzC-adkPEviYMTTc26NadDp-yxESowPB8Q0sReoWTwh1ZI7CmLrfyfe-f2Zk=w732-h375-s-no?authuser=0 "That's it")
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
