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

A. the machine that your doing the test on might be limited in cache size so when processing a larger amount of data it would slow down. If the data is larger than what the cache can hold then run time slows down meaning it doesnt conform to the asymptotic prediction.
B. Since asymptotic ignores constants and lower order terms such as n if thecomplexity is n^2 it can cause the runtime to be worse at small input sizes. The example of O(n^2) with small constants can be faster than  O(nlogn) with large constants even though the asymtotic complexity would ignore the constants in such an equation but at larger input sizes the large constants would have a smaller impact on the run time.
C. Asymptotic analysis ignores the proccessing power of machines it might run on so if they are run on different machines or have background processes taking some of the processing power then it wouldn't run at the same time an asymptotic complexity would expect.

 if the list is 10x bigger for the elements and you assume that the tree is balanced than the time to get the information would be logn meaning that log(10,000) would take 33% longer
 making the run time 5 x1.33 = 6.66 seconds.

1. The tree could be unbalanced with the element searched for being the first element taking 5 seconds and the element searched for in the second taking 100 seconds. If the first element searched took 5 seconds and it takes 5 seconds to search for each element if it needs to go 20 elements deep thats 5 * 20 = 100 seconds. if the tree is unbalanced then it could be longer than 14 deep as it could be up to 10000 deep if its formed like a linked list.
2. when you have small input sizes the program would likely fit into the cache so it runs at a faster pace. while at larger input sizes it would need to rely on disk space making the program run at a slower speed increasing run time.
3. If the computer is running background processes it would take up processing power and cache memory so it would leave less for the program to use before it needs to start using disk memory slowing the process down with both processing power and memory.
 


I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
