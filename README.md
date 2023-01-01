## Our Student Class

### WHAT IS IT?
A class for creating student instances

### WHAT DOES IT DO?
Serves as a base for testing methods

### HOW DO YOU USE IT?
Use the Student class’ properties and methods as targets for assestions

## Testing methods and properties

### WHAT IS IT?
Creating a test for the full_name Student class method

### WHAT DOES IT DO?
Tests whether the full_name method returns a student’s full name as a string

### HOW DO YOU USE IT?
Create an instance of the Student class with first and last name values, followed by an assert to test the full_name method

## Building a method using TDD - creating the first test

### WHAT IS IT?
The first stage of red-green-refactor
 
### WHAT DOES IT DO?
Create a test that fails

### HOW DO YOU USE IT?
Write a test for a function that doesn’t exist yet based on expected behaviour

## Building a method using TDD - creating the code

### WHAT IS IT?
The green stage of red-green-refactor
 
### WHAT DOES IT DO?
Makes the failing test pass

### HOW DO YOU USE IT?
Write code that will perform the required actions to make the test pass

## The lifecycle of a test

### WHAT IS IT?
The order in which steps are performed when tests are run
 
### WHAT DOES IT DO?
Allows for the setup of the testing environment
 
### HOW DO YOU USE IT?
Create the required test methods to perform actions before tests are run

## Introduction to Mocking

### WHAT IS IT?
A module that comes as standard with unittest

### WHAT DOES IT DO?
Allows us to imitate certain conditions that are beyond our control

### HOW DO YOU USE IT?
Import it into a test file and use it to create a mock object

## Mocking our method

### WHAT IS IT?
A method to get a student’s course schedule from a fictional external API

### WHAT DOES IT DO?
Imitates an API call so successful and failed responses can be tested

### HOW DO YOU USE IT?
Import patch from unittest.mock and use it to create a mock object

