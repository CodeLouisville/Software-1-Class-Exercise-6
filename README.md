# Software 1 - Class Exercise 6
## Goals
- Reafactor code to take advantage of "Clean Coding" principles you've learned.

## Instructions
This exercise won't have the usual format where there are detailed instructions.  Instead, it will simply provide some suggestions to make the application easier to maintain, extened, and read.
- Try finding duplicate code and moving them to methods.
- Is having everything in the program file the easiest to read?  Probably not, maybe try moving some stuff around into a new `UILogic` class or something like that.
- Add some class comments.  You can get them easily generated for you by adding `///` above a class, property, or method.
- Organize your files in the solution.  Add some folders to put classes in.  Don't forget to adjust the namespace to reflect it's new location in the solution.
- Wherever you can, use interfaces instead of concrete classes.  Some easy examples would be `IList`, `IDictionary`, and `IProductLogic`.
- Discuss with someone and try to figure out if you all were using any clean coding principles in the past exercises.
