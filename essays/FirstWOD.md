---
layout: essay
type: essay
title: "My First WOD"
# All dates must be YYYY-MM-DD format!
date: 2023-09-4
published: true
labels:
  - JavaScript
  - Software Engineering
  - Learning
---

# <img width="50%" class="rounded float-start pe-4" src="../img/Javascript.png">
## What are WODs?
Work Out of the Day (WOD) is an athletic approach to software engineering. Its goal is to practice implementing a solution to a problem, being as efficient as possible and while being time-constrained. Each WOD completion is ranked by Rx (as prescribed), Av (advanced), Sd (standard), and DNF (did not finish), with Rx being the best and DNF being the worst.

## Objective
My first Work Out of the Day (WOD) was called BertEarnie. The instruction for this WOD was basically to implement a function called BertEarnie, to print out "Bert" if an integer is a multiple of 4. If an integer is a multiple of 6, it'll then print out "Ernie". If the integer is a multiple of 4 and 6, it will print "BertErnie". And finally, if the integer didnt pass the conditions listed above, it will print the integer itself. To test the function, we were required to print the outcome corresponding to the numbers 1 to 100.

The Rx for this WOD is being able to complete it within 6 minutes. The Av time is completing the WOD from 8 to 13 minutes. The Sd time is from 13 to 18 minutes. Lastly, DNF is when it takes more than 18 minutes to complete the WOD.

## Experience and Reflection
The solution that I came up for this problem was done within the Rx time frame by utilizing for loops and if statements within the function "BertErnie". Despite the speedy completion of the task, after reviewing the solution I created, I realized that there were a couple flaws in it even though it gave the output I wanted. 

One notable issue that I noticed is that if I wanted to use function BertErnie again, it will always start from 1 and increment till the requested number. This limits the function's versatility. It would be more beneficial if the for loop was outside of the function such that if theres a case where only a specific number needs to be checked, it'll be able to do so, making the code more adaptable.

During the class discussions afterwards, we discussed some of the different approaches to implement the solution and I realized that there are a lot more things to consider such as the significance of code readability. I also came to appreciate the importance of these conversations after the WOD completion as they provide an opportunity to learn from my peers. These discussions highlights different perspectives to consider, explore more efficient algorithms and also the benefits of handling situations in a particular way.

Moving forward, my strategy to improve my performance for future WODs is to shift my focus away from speed a little bit and if time allows, prioritzie being able to create accurate, versatile, efficient, and readable code a little bit more. 


Code : <a href="https://jsfiddle.net/JoyTan/s4pkcx5o/11/">BertErnie</a>
