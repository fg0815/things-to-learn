**maxmimun subarray**
http://www.programcreek.com/2013/02/leetcode-maximum-subarray-java/

**linked list reversal**


**Print out the level order traversal of a Binary Tree, with new line after each level.  /Binary Tree Serialization, deserialize**
http://www.jiuzhang.com/solutions/binary-tree-preorder-traversal/

**Merge two sorted lists**


**Add/Delete from binary tree**

**public double pow(double a, int b) Look for special if b<0. write it in O(Log n) time.**
http://www.jiuzhang.com/solutions/powx-n/
http://www.programcreek.com/2012/12/leetcode-powx-n/


**Count the number of occurrences in a sorted array**
http://www.geeksforgeeks.org/count-number-of-occurrences-in-a-sorted-array/

**LRU Cache**
http://www.jiuzhang.com/solutions/lru-cache/

**Implement an algorithm to convert an integer into a roman numeral string and vice versa.**
http://stackoverflow.com/questions/12967896/converting-integers-to-roman-numerals-java

**nested array**
https://gist.github.com/shoumikhin/ac5d40e11f957e30c649
http://www.mitbbs.com/article_t/JobHunting/32583985.html

**Find median of an infinite stream of integers in O(1) time**
https://www.careercup.com/question?id=5717488440442880

**Isomorphic Strings**
Using hashmap to check if the value is the same


**square root**
```
boolean isPerfectSquare(long number)
{
    if (number < 0) return false;
    if (number < 2) return true;

    for (int i = 0; ; i++)
    {
        long square = squareTable[i];
        if (square > number) return false;
        while (number % square == 0)
        {
            number /= square;
        }
        if (number == 1) return true;
    }
}
```
**Given a dictionary find and set of two words find path from one word to another such that all the intermediate words are also from dictionary.
 Example: GOD -> GID -> DID -> DIG -> DOG.**
http://www.programcreek.com/2012/12/leetcode-word-ladder/

**given a DNA sequence find pattern**
http://stackoverflow.com/questions/16871113/how-to-match-dna-sequence-pattern

**implement a O(1) min function for Stack** 
http://stackoverflow.com/questions/685060/design-a-stack-such-that-getminimum-should-be-o1

**print factors for number**

**given like +77288.100, a772sb, 2000.00.11.
return if it's a number.
you could either write a regular expression or simply go through the string.
1. it should start with "+/-" or "0-9".
2. there should only have one "." in the string.
3. all other character are "0-9"**
https://www.careercup.com/question?id=5753629812195328
("-?\\d+(\\.\\d+)?")

**Find a triangle in a list of random numbers (a triangle is three numbers such that no one number is larger than the other two numbers added up)**
http://www.jiuzhang.com/solutions/triangle-count/

**lowest common ancerster**
http://www.jiuzhang.com/solutions/lowest-common-ancestor/

**is valid binary tree**
http://www.geeksforgeeks.org/a-program-to-check-if-a-binary-tree-is-bst-or-not/

**permutations of a given string**
http://stackoverflow.com/questions/4240080/generating-all-permutations-of-a-given-string

**determine if a graph is bipartite** 
http://www.geeksforgeeks.org/bipartite-graph/

**Check for balanced parentheses in an expression**
http://stackoverflow.com/questions/16874176/parenthesis-brackets-matching-using-stack-algorithm

**dynamic programming or greedy algorithm**
http://stackoverflow.com/questions/13713572/how-is-dynamic-programming-different-from-greedy-algorithms

**compare binary tree**
http://stackoverflow.com/questions/9597188/the-most-efficient-way-to-test-two-binary-trees-for-equality

**two sum**
http://www.jiuzhang.com/solutions/two-sum-ii/
http://www.jiuzhang.com/solutions/two-sum-closest/
http://www.jiuzhang.com/solutions/two-sum/

**Reverse a string**
http://www.jiuzhang.com/solutions/reverse-words-in-a-string/
