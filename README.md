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
 the input size can show different results with n^2 doing better than nlogn if the constant is large enough for example n^2 + 1 will run faster than nlogn + 1,000,000 while n < 1000.
 It the code is run on different machines you will likely get different results as the processing power and memory limitations might come into play or if it has processing consuming tasks run in the background.

 if the list is 10x bigger for the elements and you assume that the tree is balanced than the time to get the information would be logn meaning that log(10,000) would take 33% longer
 making the run time 5 x1.33 = 6.66 seconds.

1. The tree could be unbalanced with the element searched for being the first element taking 5 seconds and the element searched for in the second taking 100 seconds.
2. When the program is run at low imput sizes the program would run efficently but when it gets a large array size it could slow down the machine to a degree that would cause it to run over 100 seconds.
3. The code might be running on a machine that struggles to handle an array of the larger size or it might have a process running in the background that is slowing down the machine.
 


I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
