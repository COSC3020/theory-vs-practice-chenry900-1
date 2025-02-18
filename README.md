# Theory vs. Practice

- List 3 reasons why asymptotic analysis may be misleading with respect to
  actual performance in practice.

- Suppose finding a particular element in a binary search tree with 1,000
  elements takes 5 seconds. Given what you know about the asymptotic complexity
  of search in a binary search tree, how long would you guess finding the same
  element in a search tree with 10,000 elements takes? Explain your reasoning.

- You measure the time with 10,000 elements and it takes 100 seconds! List 3
  reasons why this could be the case, given that reasoning with the asymptotic
  complexity suggests a different time.

Add your answers to this markdown file.

 when looking at the analysis the constants might be large and affect the run time for example if it runs at O(logn) + 100,000 then even if it finishes instantly it still appears slower than O(n) + 2.
 the input size can show different results with n^2 doing better than nlogn for example if n < 1.
 a piece of code might be made to do the specific task for the set sample size and out performs
 against code that theoretically runs better.

 if the list is 10x bigger for the elements an you assume that the tree is balanced than the time to get the information would be logn meaning that log(10,000) would take 33% longer
 making the run time 5 x1.33 = 6.66 seconds.

the tree could be unbalanced making the run time O(n) instead of O(logn) a balanced tree being run time of O(logn) while the worst case is the tree is a linked list.
the constants could be extreamly large making it run slow even if the first element is the element in the first search and the element in the 2nd the last one in a tree if it takes 5 seconds to find the frist element in the array and a tree with the depth of 14 to hold the 10,000 elements with the element at the end 5 x 14 = 70 seconds and if you get a mix of the other 2 that could push it over 100 seconds.
the code is made to run effiently with elements of 1000 so it runs very ineffiently at the size of 10,000 by asking the tree to rebalance the tree after each element so smaller sizes would be more effient.
 


I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
