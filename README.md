# Invalid-Resolution-Exception
# Java Object-Oriented Programming Programs

## Description

This project contains three Java programs that demonstrate important
Object-Oriented Programming concepts such as inheritance, method overriding,
abstraction, constructors, and custom exception handling.

## Problems Covered

### 1. Photography Studio – Photo and EditedPhoto

This program demonstrates inheritance and method overriding.

- `Photo` is the parent class.
- `EditedPhoto` extends the `Photo` class.
- The `Photo` class contains `title` and `resolutionMP`.
- The `EditedPhoto` class adds `filterApplied`.
- The `display()` method is overridden in the subclass.

### 2. Print Order – Abstract Class

This program demonstrates abstraction using an abstract class.

- `PrintOrder` is an abstract class.
- It contains the abstract method `processPrint()`.
- `PosterPrint` extends `PrintOrder`.
- The `processPrint()` method is implemented in `PosterPrint`.

### 3. Invalid Resolution Exception

This program demonstrates exception handling and custom exceptions.

- A custom exception named `InvalidResolutionException` is created.
- The program accepts a photo resolution from the user.
- If the resolution is zero, the custom exception is thrown.
- The exception is handled using `try-catch`.

## Concepts Used

- Classes and Objects
- Constructors
- Inheritance
- Method Overriding
- Abstraction
- Abstract Classes
- Exception Handling
- Custom Exceptions
- User Input using Scanner

## Technologies Used

- Java
- GitHub

## Project Structure

```text
Java-OOP-Programs/
│
├── src/
│   ├── Photo.java
│   ├── PrintOrder.java
│   └── InvalidResolutionException.java
│
├── tests/
│   └── Sample test cases
│
├── docs/
│   └── Documentation and screenshots
│
└── README.md
