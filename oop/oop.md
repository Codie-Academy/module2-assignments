**Quiz 1: Basic Concepts of OOP**

1. What is object-oriented programming (OOP), and what are its core principles?
2. Explain the concepts of encapsulation, inheritance, and polymorphism in OOP.
3. Define the terms "class" and "object" in the context of OOP. What is the relationship between them?
4. How does Swift support OOP, and what are some key features in the language for implementing OOP concepts?
5. Provide an example of a real-world scenario where OOP can be applied effectively.

**Exercise 1: Creating a Class**

Create a Swift class called `Person` with the following properties and methods:

- Properties: `name` (String), `age` (Int), `isMale` (Bool), `address` (String).
- Methods: `introduce()`, which prints a message introducing the person.

**Exercise 2: Inheritance**

Create a subclass of the `Person` class called `Student`. The `Student` class should have an additional property `studentID` (String). Override the `introduce()` method to include the student's name, age, and student ID in the introduction.

**Exercise 3: Polymorphism**

Create an array that can hold objects of both the `Person` and `Student` classes. Add a few `Person` and `Student` objects to the array. Then, iterate through the array and call the `introduce()` method for each object. Observe how polymorphism allows you to treat objects of different classes uniformly.

**Exercise 4: Encapsulation**

Update the `Person` and `Student` classes by making the properties private and providing getter and setter methods to access and modify the properties. Ensure that you encapsulate the data effectively.

**Exercise 5: Method Overloading**

Add a method `celebrateBirthday()` to the `Person` class that increments the age of the person by 1. Overload this method in the `Student` class to include a special message for students celebrating their birthday.
