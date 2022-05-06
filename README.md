
- Create a new solution in visual studio
- Add a new C# project with an appropriate name to the solution
- Add a new interface with 2 methods
- The first function takes as __input a string__ and __outputs a string__. 
  - The function must return a string using the following rules:
    ```
    if the number is divisible by 3 then return “fizz”
    if the number is divisible by 5 then return “buzz”
    if the number is divisible by both 5 and 3 then return “fizzbuzz”
    otherwise just return the number itself
    ```
- The second function takes as input an collection of strings and returns as output an resolved collection of strings where for each element (number) in the collection we apply the first function. 
```
Input
["8","3","5", "15"]

Output
["8","fizz","buzz", "fizzbuzz"]
```
- Add a new class which implements the interface and create the implementation for the 2 functions.
- Create a new test project with an appropriate name
- Add a test class with several test methods that validate your implementation for the created function.
