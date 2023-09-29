**Quiz 1: Dictionary Basics**

1. What is a dictionary in programming?
   a) A collection of ordered key-value pairs
   b) A collection of values with no defined order
   c) A single value

2. In Swift, can a dictionary contain duplicate keys?
   a) Yes
   b) No

3. What does a key do in a dictionary?
   a) It identifies the type of values in the dictionary.
   b) It uniquely identifies each value in the dictionary.
   c) It defines the order of values in the dictionary.

**Exercise 1: Dictionary Initialization**

Declare an empty dictionary called `fruitPrices` to store the prices of fruits. Use fruit names (String) as keys and prices (Double) as values.

**Quiz 2: Dictionary Operations**

4. How do you add a new key-value pair, "Banana" with a price of 0.99, to a dictionary called `fruitPrices` in Swift?
   a) `fruitPrices.add("Banana", 0.99)`
   b) `fruitPrices["Banana"] = 0.99`
   c) `fruitPrices.insert("Banana", at: 0.99)`

5. What is the result of `fruitPrices.count` after adding three fruit prices to the `fruitPrices` dictionary from Exercise 1?
   a) 0
   b) 2
   c) 3

**Exercise 2: Dictionary Manipulation**

Add prices for "Apple," "Orange," and "Grapes" to the `fruitPrices` dictionary.

**Quiz 3: Dictionary Access**

6. How do you retrieve the price of "Apple" from the `fruitPrices` dictionary?
   a) `fruitPrices["Apple"]`
   b) `fruitPrices.getValue("Apple")`
   c) `fruitPrices.getPrice("Apple")`

7. What does the `removeValue(forKey:)` method return if the key is successfully removed from the dictionary?
   a) nil
   b) The removed value
   c) True

**Exercise 3: Dictionary Searching**

Retrieve and print the price of "Orange" from the `fruitPrices` dictionary. If it doesn't exist, print "Price not found."

**Quiz 4: Dictionary Iteration**

8. How can you iterate over the key-value pairs in a dictionary in Swift?
   a) Using a for-in loop
   b) Using a while loop
   c) Using a switch statement

9. What does the `keys` property of a dictionary return?
   a) An array of keys
   b) A set of keys
   c) A dictionary of keys

**Exercise 4: Dictionary Iteration**

Iterate over the `fruitPrices` dictionary and print each fruit name and its price.

**Quiz 5: Dictionary Update**

10. How can you update the price of "Banana" to 1.49 in the `fruitPrices` dictionary?
    a) `fruitPrices.updateValue(1.49, forKey: "Banana")`
    b) `fruitPrices["Banana"] = 1.49`
    c) `fruitPrices.setValue(1.49, forKey: "Banana")`

**Exercise 5: Dictionary Update**

Update the price of "Banana" to 1.49 in the `fruitPrices` dictionary and print the updated price.
