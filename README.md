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

A. you could be running the test on two different computers
B. the lower order variables are ignored in the asymtotic complexity and could increase the time 
C. since asymtotic analysis is theoretical and only describes the behavior and when it comes to actual performance you can see two different results.

 if the list is 10x bigger for the elements and you assume that the tree is balanced than the time to get the information would be logn meaning that log(10,000) would take 33% longer
 making the run time 5 x1.33 = 6.66 seconds.

1. it could be that the computer has a virus that is sending all your personal information causing everything to run slower on the computer making it take longer.
2. when you have small input sizes the program would likely fit into the cache so it runs at a faster pace. while at larger input sizes it would need to rely on disk space making the program run at a slower speed increasing run time.
3. If the computer is running background processes it would take up processing power and cache memory so it would leave less for the program to use before it needs to start using disk memory slowing the process down with both processing power and memory.
 


I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
