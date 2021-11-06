# VBA Challenge

##  Project Overview
  The VBA Challenge encompassed all of the concepts from Module 2, including for loops, conditionals, and nested for loops. These concepts will are critical to understand because they have similar structures in other programming languages. Just like how sentences have subjects, actions and descriptions across different spoken languages, programming languages have similar conceptual structure.
  
  The VBA Challenge also introduced the concept of refactoring. Refactoring is critical to programming as it is a method to improve the efficiency and resource utilization of programs. The following analysis explains how the code developed through Module 2 was refactored and the efficiency gained.
  
## Results
  
  ### Before Refactoring
  ![2017 Before Refactoring](https://github.com/mjkleineck/stocks-analysis/blob/main/Resources/run_time_2017_before_refactoring.png)
  
  ![2018 Before Refactoring](https://github.com/mjkleineck/stocks-analysis/blob/main/Resources/run_time_%202018_before_refactoring.png)
  
  ![Code Before Refactoring](https://github.com/mjkleineck/stocks-analysis/blob/main/Resources/code_before_refactoring.png)
  
  ### After Refactoring
  ![2017 After Refactoring](https://github.com/mjkleineck/stocks-analysis/blob/main/Resources/run_time_2017_after_refactoring.png)
  
  ![2018 After Refactoring](https://github.com/mjkleineck/stocks-analysis/blob/main/Resources/run_time_2018_after_refactoring.png)
  
  ![Code After Refactoring](https://github.com/mjkleineck/stocks-analysis/blob/main/Resources/code_after_refactoring.png)
  
  After refactoring, the program's run-time **decreased by nearly 80%**!

## Summary
  Just how there is more than one way to tell a story, there is more than one way to write a program to accomplish the same goal. Refactoring not only serves as a method to increase the efficiency of a program and decrease the amount of required processing power. It also creates a way for programmers to learn and observe different ways of logic and style to accomplish the same result. Refactoring is a way to share knowledge and learn from others too. Although refactoring can be a slow, tedious process, the outcomes pay dividends for the long-term.
  
  In this particular program, the original code required the whole data set of 3000+ rows to be looped through 12 times. The refactored code required the data set to be looped through only once, leveraging an array as a way to store a list of values to be output at the completion of the program. The time it took to run the program decreased by half a second. That is not a huge gain with a data set of 12 stocks. Imagine if there were thousands of stocks in the data set though. That time savings and reduction in processing power really adds up. The refactored code also did not require the program to switch back and forth between sheets within the workbook. Even though the original code is easier to follow an less complex, the refactored code made use of more complex concepts of arrays and indices making the additional time and effort worthwhile.
