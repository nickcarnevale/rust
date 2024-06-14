Learning Rust

## Assignment

This assignment asks you to familiarize yourself with the syntax and semantics of the Rust programming language. The assignment is broken down into 7 sections:

- Section1 - Variables
- Section2 - Strings
- Section3 - Primitive Types
- Section4 - Control
- Section5 - Functions
- Section6 - Structs
- Section7 - Move Semantics

Each section presents a number of problems that ask you to correct the given code so that it compiles. Do this for every file so that the project builds and all tests pass. Each section contains a README.md file with a link to the relevant chapters in the Rust programming language handbook. If you're stuck, be sure to look at the hint at the bottom of each file.

## Running

The functions you are to fix in this project are annotated as `#[test]`, which means they only run in a testing context. To run the project:

```bash
> cargo test
```

This will run every test defined throughout the project. You can test a specific module though. For example, if you only wanted to test the variables module you could run the following command:

```bash
> cargo test variables
```

Or to test specifically one file:

```bash
> cargo test variables::variables1
```
