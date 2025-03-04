# String shifter


## Description
This Java program takes a string (containing only letters) and an integer as input. It shifts the characters of the string by the given integer amount, wrapping around when necessary.

## Requirements
- Java 8 or later
- Gradle 8.0.2 or later 
- A terminal or command prompt to run the program


## How to Run
1. Compile the project:
   ```sh
   ./gradlew build

2. Run test cases
    ```sh
    ./gradlew app:test

3. Run the project to enter inputs
    ```sh
    ./gradlew app:run --console=plain

4. Enter a string containing only letters.
5. Enter an integer representing the shift amount.
6. The program will output the shifted string.

## Example Usage

    ```sh
    Enter a string : Welcome to Edmonton!
    Enter a number: 5
    Shifted string: 'nton!Welcome to Edmo'

## Error Handling
The program ensures that the input string contains  letters.
If the shift value is larger than the string length, it wraps around properly.

## License
This project is open-source. Feel free to modify and distribute it.