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

A. the machine that your doing the test on might be limited in cache size so when processing a larger amount of data it would slow down. 
B. the input size can show different results with n^2 doing better than nlogn if the constant is large enough for example n^2 + 1 will run faster than nlogn + 1,000,000 while n < 1000.
C. It the code is run on different machines you will likely get different results as the memory limitations might come into play.

 if the list is 10x bigger for the elements and you assume that the tree is balanced than the time to get the information would be logn meaning that log(10,000) would take 33% longer
 making the run time 5 x1.33 = 6.66 seconds.

1. The tree could be unbalanced with the element searched for being the first element taking 5 seconds and the element searched for in the second taking 100 seconds. If the first element searched took 5 seconds and it takes 5 seconds to search for each element if it needs to go 20 elements deep thats 5 * 20 = 100 seconds.
2. When the program is run at low imput sizes the program would run efficently but when it gets a large array size it could slow down the machine due to it using all its memory to a degree that would cause it to run over 100 seconds.
3. The code might be running on a machine that struggles to handle an array of the larger size or it might have a process running in the background that is slowing down the machine.
 


I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
