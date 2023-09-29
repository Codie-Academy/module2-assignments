**Quiz 1: Set Basics**

1. What is a set in programming?
   a) A collection of ordered values
   b) A collection of values with no defined order
   c) A single value

2. In Swift, can a set contain duplicate values?
   a) Yes
   b) No

3. Which of the following best describes a set's primary characteristic?
   a) Allows duplicate values
   b) Stores values in a specific order
   c) Stores distinct values

**Exercise 1: Set Initialization**

Declare an empty set called `colors` to store String values.

**Quiz 2: Set Operations**

4. How do you add a new element, "Blue," to a set called `colors` in Swift?
   a) `colors.add("Blue")`
   b) `colors.insert("Blue")`
   c) `colors.append("Blue")`

5. What is the result of `colors.count` after adding "Green" and "Red" to the `colors` set from Exercise 1?
   a) 0
   b) 2
   c) 3

**Exercise 2: Set Manipulation**

Add "Green" to the `colors` set, and then remove "Red" from it.

**Quiz 3: Set Membership**

6. Which method can you use to check if a set contains a specific element?
   a) `contains(_:)`
   b) `has(_:)`
   c) `find(_:)`

7. What does the `remove(_:)` method return if the element is successfully removed from the set?
   a) nil
   b) The removed element
   c) True

**Exercise 3: Set Searching**

Check if the `colors` set contains "Red." If it does, print "Red found," otherwise print "Red not found."

**Quiz 4: Set Intersection and Union**

8. Which set operation combines two sets and returns a new set containing the values that are common to both sets?
   a) Intersection
   b) Union
   c) Difference

9. What is the result of `setA.union(setB)` if `setA` contains {1, 2, 3} and `setB` contains {3, 4, 5}?
   a) {1, 2, 3, 4, 5}
   b) {1, 2}
   c) {3}

**Exercise 4: Set Operations**

Create two sets, `setA` and `setB`, with integer values. Perform an intersection operation to find the common elements between them and store the result in a new set called `commonElements`.

**Quiz 5: Set Equality**

10. How can you check if two sets are equal in Swift?
    a) Using `equals(_:)`
    b) Using `==` operator
    c) Using `isEqual(_:)`

**Exercise 5: Set Equality Check**

Create two sets, `setX` and `setY`, with some elements. Check if they are equal and print the result.
