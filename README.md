This repository contains Kotlin practice files, covering various basic and advanced features of the Kotlin programming language. Each file demonstrates core concepts like control flow, collections, functions, and more. This README will guide you through setting up the environment, installing dependencies, and running the Kotlin files included in the repository.

Requirements
To run the Kotlin files in this repository, ensure the following are installed on your system:

1. Java Development Kit (JDK 11 or higher)
Since Kotlin runs on the JVM (Java Virtual Machine), you'll need to have JDK installed on your system.

Check your Java version:

bash
Copy code
java -version
2. Kotlin Compiler
The Kotlin compiler is required to compile and execute Kotlin programs. You can install it using the following methods:

Using SDKMAN (Recommended):

bash
Copy code
curl -s https://get.sdkman.io | bash
source "$HOME/.sdkman/bin/sdkman-init.sh"
sdk install kotlin
Using APT on Ubuntu:

bash
Copy code
sudo apt update
sudo apt install kotlin
Verifying Kotlin installation:

bash
Copy code
kotlin -version
3. Requirement File
For easy setup, you can refer to the requirements.txt file, which lists all the necessary steps to get your environment ready.

Running the Kotlin Files
1. Hello World (HelloWorld.kt)
This file prints the classic "Hello, World!" message, demonstrating the basic structure of a Kotlin program.

To run:

bash
Copy code
kotlin HelloWorld.kt
2. Basic Types (dtype.kt)
This file covers the basic types in Kotlin such as integers, strings, booleans, and type conversions.

To run:

bash
Copy code
kotlin dtype.kt
3. Collections (collections.kt)
Learn how to work with Kotlin’s collections, including lists, sets, and maps.

To run:

bash
Copy code
kotlin collections.kt
4. Control Flow (controlFlow.kt)
This file demonstrates control flow in Kotlin using if, when, for, and while loops.

To run:

bash
Copy code
kotlin controlFlow.kt
5. Functions (functions.kt)
This file covers defining and using functions in Kotlin, including higher-order functions and lambdas.

To run:

bash
Copy code
kotlin functions.kt
6. Classes (classes.kt)
Explore Kotlin's object-oriented programming features such as classes, objects, inheritance, and interfaces.

To run:

bash
Copy code
kotlin classes.kt
7. Null Safety (strCust.kt)
This file explains Kotlin's null safety features, including safe calls and the !! operator to handle nullable types.

