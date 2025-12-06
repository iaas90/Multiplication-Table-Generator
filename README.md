# Multiplication Table Generator

A simple Java console application that prints the multiplication table for a user-entered number (from 1 to 10).

## Description

This program prompts the user to enter an integer, then prints the multiplication table of that number (from 1 up to 10).  
It demonstrates basic Java programming concepts such as user input (with `Scanner`), loops (`for`), and console output.

## Table of Contents

- [Getting Started](#getting-started)  
- [Usage](#usage)  
- [Example](#example)  
- [Requirements](#requirements)  
- [How it Works](#how-it-works)  
- [Author](#author)  

## Getting Started

### Requirements

- Java Development Kit (JDK) — version 8 or higher  
- A terminal or command line interface  

### Compilation & Running

1. Clone or download this repository.  
2. Navigate to the project directory in your terminal.  
3. Compile the Java file:  
   bash
   javac day5/MultiplicationTableGenerator.java


4. Run the compiled class:

   bash
   java day5.MultiplicationTableGenerator
   

## Usage

When you run the program, you will see:


Enter a number to print it's multiplication table


Type an integer (e.g., `5`) and press Enter — the program will then output:


Number 5 times 1 = 5  
Number 5 times 2 = 10  
...
Number 5 times 10 = 50

## Example


Enter a number to print it's multiplication table
7
Number 7 times 1 = 7
Number 7 times 2 = 14
Number 7 times 3 = 21
...
Number 7 times 10 = 70


## How it Works

* The program reads an integer input using `Scanner`.
* It then loops from `1` to `10` using a `for` loop.
* For each iteration, it calculates the product of the input number and the loop index, then prints a formatted line to the console.

## Author

Your Name — (optional: link to your GitHub profile)

Feel free to fork and enhance the program (e.g., allow custom table length, handle invalid input, add unit tests, etc.).
