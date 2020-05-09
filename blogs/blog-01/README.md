#### [Home](https://joelmwatson.github.io) >> [Blogs](https://joelmwatson.github.io/blogs) >> [How to Solve Programming Problems](https://joelmwatson.github.io/blogs/blog-01)

#

## How to Solve Programming Problems

[Original Article](https://simpleprogrammer.com/solving-problems-breaking-it-down/)

The number one mistake new programmers make in technical interviews is jumping straight into writing code without taking the time to fully understand the problem. Luckly, John Sonmez gives us an easy 6 step process to ensure we don't fall into the trap. I will demonstrate using Johns process to solve the simple example problem below.

First, you'll want to **read through the problem at least twice**. You want to make sure you fully understand what it is asking of you.

Example Problem: Create a function that takes an array of numbers and returns the sum of the array.

Second, you'll want to **solve the problem manually with some sample data**. This lets you work out what the process is to get to the solution. Remember to keep it simple here, you can go back and refine your process after you reach a solution.

- create variable to hold sample data
- fill data variable (data = [1, 2, 3, 4])
- initials a variable to hold the sum (sum = 0)
- add the first element to the sum (sum = 1)
- add the second element to the sum (sum = 3)
- add the third element to the sum (sum = 6)
- add the last element to the sum (sum = 10)
- return the sum (sum = 10)

Third, you need to **optimize your manual process**. Now that you've got a working solution, you might see some steps in your process that aren't as efficient as they could be. Go ahead and fix these inefficiencies before moving on.

- create variable & fill to hold sample data (data = [1, 2, 3, 4])
- <----- removed unneccessary step
- initials a variable to hold the sum (sum = 0)
- add the first element to the sum (sum = 1)
- add the second element to the sum (sum = 3)
- add the third element to the sum (sum = 6)
- add the last element to the sum (sum = 10)
- return the sum (sum = 10)

Fourth, it's time to begin the transition from manual process to automated process. **Write out your manual process in pseudo-code or comments**. This step is pretty easy since you already know all the steps, you just need to think about how a computer would do it.

     function (sampleData) {
       // initialize sum to zero

       // for loop through sampleData adding the current index value to the sum

       // return the sum
     }

Fifth, it's finally the time you've been waiting for. At this point you have a full understanding of the problem, and a good idea of how you plan to solve it. It's time to **replace those comments and pseudo-code with some real code**.

     const sum = (sampleData) => {
       let sum = 0;
       for (let i=0; i< sampleData.length; i++) {
         sum += sampleData[i];
       }
       return sum;
     }

Sixth, congratulations! You officially have working software that solves the problem you set out to solve, but there is still one more step to be done. Look over your solution for anywhere you can **optimize your code**.

    const sum = (sampleData) => {
     return sampleData.reduce((acc, cur) => acc + cur, 0);
    }

Great Job! The more you practice breaking down your programming problems into these simple 6 steps, the more your software will improve and your time spent running into unexpected issues will reduce as well.
