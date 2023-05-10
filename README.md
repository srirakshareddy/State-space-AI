# State-space-AI

This is an exercise to practice the usability of State Space Search.I am employing two search algorithms to search for the path of finding a path from a start word to an end word. The rules of changing the letters are illustrated as follows:
The player is given a start word and an end word. In order to have a successful search for changing the word from the start into the end, the player must change the start word into the end word progressively, creating an existing word at each step (given a dictionary of words). Each step consists of a single letter substitution. For example, the following are the seven shortest solutions to the word ladder puzzle between words "cold" and "warm", using words from Collins Scrabble Words (https://drive.google.com/file/d/1oGDf1wjWp5RF_X9C7HoedhIWMh5uJs8s/view).

<img width="213" alt="Screen Shot 2023-05-09 at 8 33 40 PM" src="https://github.com/srirakshareddy/State-space-AI/assets/132956605/7d22f25b-923b-4b03-9ff6-5a0ed6250fcd">

As each step changes only one letter of the word to form a new word.
The new word must exist in the given dictionary.
The Goal: Use the least steps to convert start word into end word. You will need to implement at least two state space search mechanisms like (e.g. Depth-First Search and Breadth-First Search, A-Star Search, Dijkstra Search). You will need to test your two mechanisms and state which one can provide the shortest path. For testing, you need to use the following wordlist as your dictionary:
wordList = ["fool", "pool", "foil", "foul", "cool", "poll", "fail", "pole", "pall", "pope", "pale", "page", "sale", "sage", "pipe", "doll", "soil", "soul", "nail", "jail", "tail", "bail", "fall"]
I am using my start as = “pole” and end as “soul” and one of the algorithm mechanisms will find it in five letters changes:

<img width="521" alt="Screen Shot 2023-05-09 at 8 34 50 PM" src="https://github.com/srirakshareddy/State-space-AI/assets/132956605/68d5f885-789f-4ce7-b1d2-c655a065ecee">

Overview:
1. Using the BFS and DFS to search for the path and finding a path from a start
word to an end word.
2. The code is in Python and has 4 parts.
3. The wordlist is first defined.
4. After defining the wordlist we then use the breadth first search to implement
the state space search mechanism
5. The second state space search mechanism is depth first search.
6. The length of the shortest chain in both BFS and DFS.
