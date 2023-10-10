**Quiz 1: Basic Concepts**

1. What is a closure in Swift?

   a. A predefined function in Swift.
   b. A self-contained block of code that can be passed around and used in your code.
   c. A data type used for storing text.

2. Which keyword is used to separate the parameters and body of a closure in Swift?

   a. `func`
   b. `in`
   c. `return`

**Exercise 1: Closure Syntax**

Write a closure that takes two integers as parameters and returns their sum. Assign the closure to a constant called `addition` and call it with sample values.

**Quiz 2: Capturing Values**

3. What does it mean for a closure to "capture" values in Swift?

   a. It retains and stores references to variables and constants from the surrounding context.
   b. It converts values into strings.
   c. It discards values that are not needed.

4. When might you use a captured value in a closure?

   a. When you want to modify a value from the outer scope.
   b. When you want to create a new variable.
   c. Captured values are never used in closures.

**Exercise 2: Capturing Values**

Write a function `makeCounter` that returns a closure. The closure should capture an integer and, when called, increment the captured integer by 1. Create two counters using this function and demonstrate that they can count independently.

**Quiz 3: Escaping Closures**

5. When do you mark a closure as `@escaping` in Swift?

   a. When the closure doesn't capture any values.
   b. When the closure is used as an argument to a function and might be called after the function returns.
   c. When the closure is used within a struct.

6. Why is marking a closure as `@escaping` important?

   a. It improves the performance of the closure.
   b. It prevents the closure from being used.
   c. It ensures the closure remains valid for execution after the function returns.

**Exercise 3: Escaping Closures**

Write a function `downloadData` that takes a closure as an argument. The closure should simulate downloading data asynchronously and, once the data is downloaded, call the closure with the downloaded data as a parameter. Mark the closure as `@escaping`. Use a `DispatchQueue` to simulate an asynchronous operation and call the closure after a delay.

**Quiz 4: Higher-Order Functions**

7. What are higher-order functions in Swift?

   a. Functions that return closures.
   b. Functions that take closures as arguments or return closures.
   c. Functions with a higher level of complexity.

8. Which higher-order function can be used to transform elements in an array and return a new array with the transformed values?

   a. `filter`
   b. `map`
   c. `reduce`

**Exercise 4: Higher-Order Functions**

Given an array of integers, use the `map` higher-order function to transform it into a new array where each element is doubled.

These quizzes and exercises should help you solidify your understanding of closures in Swift. Feel free to explore more complex scenarios and use closures in real-world applications to become more proficient with this essential Swift feature.
