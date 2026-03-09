# FizzBuzz TDD (Java)

Java implementation of the FizzBuzz kata with JUnit 5 and Maven. The project includes a simple `FizzBuzz` converter, a `Main` entry point to print results from 1 to 15, and a focused test suite.

## Requirements
- Java 24
- Maven 3.9+

## Build and Test
```bash
mvn test
```

## Tests
Run the test suite with `mvn test`. Add the test run screenshot here if your instructor requires evidence of execution.

## Project Structure
```
src/
  main/java/org/example/
    FizzBuzz/FizzBuzz.java
    Main.java
  test/java/fizzbuzz/
    FizzBuzzTest.java
```

## Notes
The `FizzBuzz` converter follows the standard rules:
- Multiple of 3 => "Fizz"
- Multiple of 5 => "Buzz"
- Multiple of 3 and 5 => "FizzBuzz"
- Otherwise the number as a string
