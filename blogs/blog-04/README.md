#### [Home](https://joelmwatson.github.io) >> [Blogs](https://joelmwatson.github.io/blogs) >> [The Tech Blog Writer Podcast 1166](https://joelmwatson.github.io/blogs/blog-04)

---

## Stepping Through Insertion Sort

Using the the input array [8,4,23,42,16,15], we will be going through the pseudocode
bewlow showing the the output at each step.

![pseudocode](https://raw.githubusercontent.com/JoelMWatson/JoelMWatson.github.io/master/assets/pseudocode.png)

First we start with i at position 2 (index 1) of the array and j at postion 1
(index 0). We take the value at position i (4), store it in the temp variable,
and compare it to the value in position j (8).

![step1.1](https://raw.githubusercontent.com/JoelMWatson/JoelMWatson.github.io/master/assets/step1.1.png)

While j is greater than or equal to 0 and temp is less than the value at position
j, the value at positon j is moved forward one postion, j is decremented, and
the while statement conditions are checked again before repeating.

![step1.2](https://raw.githubusercontent.com/JoelMWatson/JoelMWatson.github.io/master/assets/step1.2.png)

Once the while statement conditions fail, the temp will be set in the postion j + 1
and the output is array [4,8,23,42,16,15]

![step1.3](https://raw.githubusercontent.com/JoelMWatson/JoelMWatson.github.io/master/assets/step1.3.png)

For step two we move forward to position 3 (index 2) for i and position 2 (index 1)
for j. Set the temp to the value at i (23).

![step2.1](https://raw.githubusercontent.com/JoelMWatson/JoelMWatson.github.io/master/assets/step2.1.png)

This time, since temp is larger than the value at array[j], we immediately break
out of the while loop.

![step2.2](https://raw.githubusercontent.com/JoelMWatson/JoelMWatson.github.io/master/assets/step2.2.png)

The temp is now set in the postion j + 1 and the output is array [4,8,23,42,16,15]

![step2.3](https://raw.githubusercontent.com/JoelMWatson/JoelMWatson.github.io/master/assets/step2.3.png)

For step three we move forward to position 4 (index 3) for i and position 3 (index 2)
for j. Set the temp to the value at i (42).

![step3.1](https://raw.githubusercontent.com/JoelMWatson/JoelMWatson.github.io/master/assets/step3.1.png)

Again, like with step two, temp is larger than the value at array[j] so we immediately
break out of the while loop.

![step3.2](https://raw.githubusercontent.com/JoelMWatson/JoelMWatson.github.io/master/assets/step3.2.png)

The temp is now set in the postion j + 1 and the output is array [4,8,23,42,16,15]

![step3.3](https://raw.githubusercontent.com/JoelMWatson/JoelMWatson.github.io/master/assets/step3.3.png)

For step four we move forward to position 5 (index 4) for i and position 4 (index 3)
for j. Set the temp to the value at i (16).

![step4.1](https://raw.githubusercontent.com/JoelMWatson/JoelMWatson.github.io/master/assets/step4.1.png)

This time, we move through our while loop twice to move the element to the left 2
spaces.

![step4.2](https://raw.githubusercontent.com/JoelMWatson/JoelMWatson.github.io/master/assets/step4.2.png)

Once the while statement conditions fail, the temp will be set in the postion j + 1
and the output is array [4,8,16,23,42,15]

![step4.3](https://raw.githubusercontent.com/JoelMWatson/JoelMWatson.github.io/master/assets/step4.3.png)

For step four we move forward to position 6 (index 5) for i and position 5 (index 4)
for j. Set the temp to the value at i (15). We know this is the last step because
we have reached the end of the array.

![step5.1](https://raw.githubusercontent.com/JoelMWatson/JoelMWatson.github.io/master/assets/step5.1.png)

This time, we move through our while loop 3 times to move the element to the left
3 spaces.

![step5.2](https://raw.githubusercontent.com/JoelMWatson/JoelMWatson.github.io/master/assets/step5.2.png)

Once the while statement conditions fail, the temp will be set in the postion j + 1
and the final output is the sorted array [4,8,23,42,16,15]

![step5.3](https://raw.githubusercontent.com/JoelMWatson/JoelMWatson.github.io/master/assets/step5.3.png)
