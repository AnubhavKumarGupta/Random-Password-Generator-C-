# Random-Password-Generator-C

This is a simple random password generator written in C. The program generates a password of desired length with a combination of numbers, lowercase letters, uppercase letters, and symbols.

## How to Use
1. Run the program.
2. Enter the desired length of the password when prompted.
3. The program will generate a random password of the specified length and display it on the screen.

## Features
- Generates random passwords with a mix of numbers, lowercase letters, uppercase letters, and symbols.
- Allows customization of the password length.

## Running the Program
Ensure you have a C compiler installed on your system. You can compile and run the program using a C compiler like GCC.

```bash
gcc -o Random Password Generator.c
```

## Requirements
- C compiler (e.g., GCC)

## File Structure
- `Random Password Generator.c`: Contains the source code of the password generator.

## Note
- The program uses the `rand()` function along with the `srand()` function to generate random numbers. The `srand()` function is seeded with the current time to ensure randomness.
- The generated password will consist of a mix of numbers, lowercase letters, uppercase letters, and symbols. The ratio of each type of character is randomized.
- The program will continue to generate passwords indefinitely until terminated by the user.

Feel free to use this password generator to create random passwords for various purposes, such as securing accounts or generating temporary access codes!

---

**Author:** Anubhav Kumar Gupta
