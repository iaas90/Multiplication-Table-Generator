<!-- Badges: start --> 
[![GitHub stars](https://img.shields.io/github/stars/YOUR_USERNAME/YOUR_REPO.svg?style=social&label=Stars)](https://github.com/YOUR_USERNAME/YOUR_REPO)  
<!-- Badges: end -->

# Multiplication Table Generator

> A simple Java console application that prints the multiplication table for a user-entered number (1 through 10).

## ✨ Features

- Prompts the user to enter an integer.  
- Prints the multiplication table for that number (from 1 to 10).  
- Demonstrates basic Java concepts: console input (`Scanner`), loops, and output formatting.

## 🧰 Requirements

- Java Development Kit (JDK 8 or newer)  
- Terminal / Command Line  

## 🚀 Getting Started

bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git

# Navigate into the project folder
cd YOUR_REPO

# Compile the code
javac day5/MultiplicationTableGenerator.java

# Run the program
java day5.MultiplicationTableGenerator


## 🎯 Usage

When you run the program, you’ll see:


Enter a number to print it's multiplication table


Enter a number (e.g. `5`) and press Enter. The program will output:


Number 5 times 1 = 5  
Number 5 times 2 = 10  
…  
Number 5 times 10 = 50


## 📝 Example


Enter a number to print it's multiplication table
7
Number 7 times 1 = 7
Number 7 times 2 = 14
Number 7 times 3 = 21
…
Number 7 times 10 = 70


## 🔧 How It Works

Internally, the program:

1. Uses `Scanner` to read integer input from the user.
2. Uses a `for` loop to iterate from 1 through 10.
3. For each iteration, computes `number × i`, and prints a formatted line to the console.

## 📈 Potential Improvements

* Allow user to specify the multiplication table length (not just up to 10).
* Validate input (e.g. handle non-integer or negative input gracefully).
* Add unit tests.
* Add GUI or web interface for interactive use.

## 🙋 Author

Your Name — feel free to fork, contribute, or use this as a learning project.



### 🔖 About Badges

- The badge syntax above uses badge-images from Shields.io (e.g. for license, stars). :contentReference[oaicite:1]{index=1}  
- Many open-source projects include badges to show project status, license, CI build status, etc. :contentReference[oaicite:2]{index=2}  
- Once you publish your repo on GitHub, you can swap `YOUR_USERNAME/YOUR_REPO` with your actual GitHub username and repository name to make the badges functional.

---

