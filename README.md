# custom-methods
The provided code showcases two different approaches to extending JavaScript's built-in Number type or creating a custom class for performing arithmetic operations.
The provided code showcases two different approaches to extending JavaScript's built-in Number type or creating a custom class for performing arithmetic operations. Here's a description of each section:

Class Approach:
The code defines a class called bigJs with a constructor that takes an initial value. The class has methods for adding, subtracting, dividing, and multiplying numbers. Each method modifies the init property of the class and returns the instance of the class itself, allowing for method chaining.
An instance of the bigJs class is created with an initial value of 5. The methods add, subtract, divide, and multiply are called in a chain to perform arithmetic operations on the initial value. The final result is logged to the console.

Number Prototype Approach:
The code modifies the prototype of the Number type to add custom methods for performing arithmetic operations. The add, subtract, divide, and multiply methods are added to the Number prototype, allowing numbers to directly invoke these methods.
A number (5) is used as the starting value, and the custom methods are called in a chain to perform arithmetic operations. The final result is logged to the console.

A Git repository for this project would likely include the JavaScript code as well as any additional files, such as an HTML file for testing or a README.md file with explanations. It could also include documentation or additional features related to arithmetic operations or other functionalities.
