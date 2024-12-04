# Tries
- [Implement Trie (Prefix Tree)](https://leetcode.com/problems/implement-trie-prefix-tree/)
- [Design Add and Search Words Data Structure](https://leetcode.com/problems/design-add-and-search-words-data-structure/)
- [Word Search II](https://leetcode.com/problems/word-search-ii/)
- [Encode and Decode Strings](https://leetcode.com/problems/encode-and-decode-strings/)
- [Palindrome Pairs](https://leetcode.com/problems/palindrome-pairs/)
- [Detect Squares](https://leetcode.com/problems/detect-squares/)
- [Word Break](https://leetcode.com/problems/word-break)

IMPORTANT SOURCES:
https://leetcode.com/discuss/general-discussion/931977/beginner-friendly-guide-to-trie-tutorial-practice-problems
https://www.geeksforgeeks.org/tag/trie/ 
https://github.com/Devinterview-io/trie-data-structure-interview-questions 

YOUTUBE VIDEOS:
https://youtube.com/playlist?list=PLgUwDviBIf0pcIDCZnxhv0LkHf5KzG9zp&si=bZzV4nv1FnOKzUKl 
https://youtube.com/playlist?list=PLEL7R4Pm6EmBVW7C4rdJ5kDL9gUfh575I&si=wj2sBKadRPLFW45j
https://youtube.com/playlist?list=PL-Jc9J83PIiHgzR2UIDD7MI2ABIIZztON&si=kmHPAE4gPg2NGUzD 

Tries are special trees (prefix trees) that make searching and storing strings more efficient. Tries have many practical applications, such as conducting searches and providing autocomplete. It is helpful to know these common applications so that you can easily identify when a problem can be efficiently solved using a trie.

Be familiar with implementing from scratch, a `Trie` class and its `add`, `remove` and `search` methods.

## Time complexity

`m` is the length of the string used in the operation.

| Operation | Big-O |
| --------- | ----- |
| Search    | O(m)  |
| Insert    | O(m)  |
| Remove    | O(m)  |

## Corner cases

- Searching for a string in an empty trie
- Inserting empty strings into a trie

## Techniques

Sometimes preprocessing a dictionary of words (given in a list) into a trie, will improve the efficiency of searching for a word of length k, among n words. Searching becomes O(k) instead of O(n).


