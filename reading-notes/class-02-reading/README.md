#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [JavaScript Review](https://JoelMWatson.github.io/reading-notes/class-02-reading)

---

## Class 02 Reading: JavaScript Review

#### What is one benefit of JavaScript not enforcing type?

One of the benefits of JavaScript not enforcing types is that you are able to create arrays that hold multiple types since all arrays are arrays of 'objects'.

#### What is one downside of JavaScript not enforcing type?

One of the cons of JavaScript not enforcing types is that sometimes you must write in your own type checking in order to avoid weird situations where you recieve the incorrect type as a parameter for your function.

#### Should the parameters of a function be changed when the function returns? Why or why not?

When you are doing functional programming with pure functions, you dont want to change the data in the parameter. Instead you want to return a different object with the new data. This gives you the ability to run the functions in any order and still get the same results without side effects.

#### Describe a type of data that has rules, aside from the given examples of Number, Integer and Float. What are the rules the data should follow?

One type in javascript that has rules is an object. Every object has to contain a pointer to some address in memory. An extention of this is an array. An array object in javascript has a pointer to an address in memory where it stores a number of pointers to other addresses in memory(for the indexes of the array).
