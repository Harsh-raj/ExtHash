# ExtHash
# Extensible Hashing Implementation

This repository contains an implementation of an extensible hashing data structure in Java. The implementation simulates an extendible hash table, capable of efficiently handling dynamic datasets by managing directory expansion, bucket splitting, and record insertion.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Implementation Details](#implementation-details)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Extensible hashing is a dynamic hashing technique used to efficiently manage large datasets with varying access patterns. This implementation demonstrates how extendible hashing manages bucket allocation, directory expansion, and record insertion.

## Features

- Dynamic resizing: Automatically adjusts directory and bucket sizes to accommodate growing datasets.
- Efficient record insertion: Handles record insertions with minimal collision and redistribution.
- Directory expansion: Dynamically expands the directory when global depth increases.
- Simulated Secondary Memory: Utilizes an array-based simulation of secondary memory for bucket storage.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or later

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Harsh-Raj/ExtHash.git
2. Navigate to the project directory:

   ```bash
   cd extensible-hashing
3. Compile the Java source files:
   ```bash
   javac *.java

### Usage
1. Compile the source files as mentioned in the installation steps.

2. Run the main class:
   ```bash
   java Main
3. Follow the prompts to simulate insertions and explore the behavior of the extendible hash table.

### Implementation Details
The implementation follows the principles of extendible hashing, including directory structure management, bucket allocation, and record insertion. It uses Java's built-in HashMap for directory management and implements custom logic for bucket handling.

For more detailed implementation information, refer to the source code comments and documentation.

### Contributing
Contributions are welcome! If you find any issues or improvements, feel free to open a GitHub issue or submit a pull request. Please follow the existing coding style and guidelines.

### License
This project is licensed under the MIT License - see the LICENSE file for details.
