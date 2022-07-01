# Spellchecking-system

implement a spell checking system based on a binary search tree. You will find attached a file containing all language words. The file would contain one word per line. At the beginning, print the count and height of the generated Binary Search Tree. the program prompts the user to enter a sentence to check its spelling.
For each word in the entered sentence,it checks whether the word exists in the binary search tree.

(a) If the word exists, program will print that the word is correct.
(b) If the word does not exist, program will print three suggestions for the correct word:
- The word in the leaf node you reached before declaring that the word does not exist.
- The word in the inorder predecessor of that leaf node.
- The word in the inorder successor of that leaf node.

In Binary Search Tree, the inorder successor of an input node is defined as the node with the smallest key greater than the key of the input node. Similarly, the inorder predecessor of an input node is defined as the node with the largest key smaller than the key of the input node.

When the program starts it loads the text file by default and print the size and height of tree
then It will ask user to enter a sentence and check for each word in the sentence if it exists in the dictionary or not and if not it should print the three suggestions as mentioned above.
