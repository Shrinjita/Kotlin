This repository contains Kotlin practice files, covering various basic and advanced features of the Kotlin programming language. Each file demonstrates core concepts like control flow, collections, functions, and more.

---

## Requirements

To run the Kotlin files in this repository, ensure the following are installed on your system:

### 1. **Java Development Kit (JDK 11 or higher)**  
   Since Kotlin runs on the JVM (Java Virtual Machine), you'll need to have JDK installed on your system.  
   - **Check your Java version:**

     ```bash
     java -version
     ```

### 2. **Kotlin Compiler**  
   The Kotlin compiler is required to compile and execute Kotlin programs. You can install it using the following methods:

   - **Using SDKMAN (Recommended):**

     ```bash
     curl -s https://get.sdkman.io | bash
     source "$HOME/.sdkman/bin/sdkman-init.sh"
     sdk install kotlin
     ```

   - **Using APT on Ubuntu:**

     ```bash
     sudo apt update
     sudo apt install kotlin
     ```

   - **Verifying Kotlin installation:**

     ```bash
     kotlin -version
     ```

### 3. **Requirement File**  
   For easy setup, you can refer to the `requirements.txt` file, which lists all the necessary steps to get your environment ready.

---

## Running the Kotlin Files

### 1. **Hello World (HelloWorld.kt)**  
   This file prints the classic "Hello, World!" message, demonstrating the basic structure of a Kotlin program.

   - **To run:**

     ```bash
     kotlin HelloWorld.kt
     ```

### 2. **Basic Types (dtype.kt)**  
   This file covers the basic types in Kotlin such as integers, strings, booleans, and type conversions.

   - **To run:**

     ```bash
     kotlin dtype.kt
     ```

### 3. **Collections (collections.kt)**  
   Learn how to work with Kotlin’s collections, including lists, sets, and maps.

   - **To run:**

     ```bash
     kotlin collections.kt
     ```

### 4. **Control Flow (controlFlow.kt)**  
   This file demonstrates control flow in Kotlin using `if`, `when`, `for`, and `while` loops.

   - **To run:**

     ```bash
     kotlin controlFlow.kt
     ```

### 5. **Functions (functions.kt)**  
   This file covers defining and using functions in Kotlin, including higher-order functions and lambdas.

   - **To run:**

     ```bash
     kotlin functions.kt
     ```

### 6. **Classes (classes.kt)**  
   Explore Kotlin's object-oriented programming features such as classes, objects, inheritance, and interfaces.

   - **To run:**

     ```bash
     kotlin classes.kt
     ```

### 7. **Null Safety (strCust.kt)**  
   This file explains Kotlin's null safety features, including safe calls and the `!!` operator to handle nullable types.

   - **To run:**

     ```bash
     kotlin strCust.kt
     ```

This `README.md` outlines everything about the repository, its structure, and how to run each file. You can replace the filenames as needed if they differ.
