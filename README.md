# Graderaide Backend

`npm install` && `npm test`!


### Stretch Goals

* Create a `School` function that returns a new object with a name and an array for students. It should also have an `addStudent` method that takes in a name, a course, and a term, and adds a new `Student` to its array.
* Write a new method for Student that averages all the grades for a course. So called with `student.someMethodNameHere('WDI')`, we'd get the average of all the grades in that student's course object, regardless of what terms they had. Whether there are 1 or 2 or 3 terms, we want ALL the grades for that course averaged up here.
* Write a new method for Student that averages all the grades for all courses. (This COULD be simply the previous function, but called with no parameters.)
* Calculate all of your averages WITHOUT loops. Consider using [Array's `reduce` method](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce) as one tool.
