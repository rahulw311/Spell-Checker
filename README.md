# Spell-Checker

This is a project on a spell checker that was designed using Levenshtein's algorithm.

The Levenshtein distance (also called the edit distance) is a string metric for measuring the difference between two sequences. Informally, the Levenshtein distance between two words is the minimum number of single-character edits required to change one word into the other. There are 3 diffrerent types of operations that can be performed- adding a character, deleting a character and substituting a character. 

Each of these operations are associated with a cost. In this case the cost of all the operations is set as 1, however in some cases the cost for adding and deleting a character can be fixed as 1 whereas the cost for substituting a character is fixed as 2.

The spell checker has been applied to the text in the book Moby Dick and the dictionary used has been downloaded from github and can be found at the link- https://raw.githubusercontent.com/dwyl/english-words/master/words_alpha.txt

Once the list of misspelt words has been found, 3 of the closest suggestions are output to the user based on Levenshtein's algotrithm.
