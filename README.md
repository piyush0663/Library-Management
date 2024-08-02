# Library Management System

This repository contains a Library Management System implemented in C++. The system provides functionality to manage books, members, and transactions in a library.

## Features

- Add, delete, and update book information
- Add, delete, and update member information
- Issue and return books
- Search for books and members
- Display all books and members

## Getting Started

### Prerequisites

- C++ compiler (GCC, Clang, etc.)
- Makefile (optional, for ease of compilation)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/library-management-system.git
    cd library-management-system
    ```

2. Compile the code:
    ```sh
    g++ -o library_management main.cpp book.cpp member.cpp transaction.cpp
    ```

    Alternatively, if a Makefile is provided, run:
    ```sh
    make
    ```

### Usage

1. Run the executable:
    ```sh
    ./library_management
    ```

2. Follow the on-screen instructions to interact with the Library Management System.

### Directory Structure

```plaintext
library-management-system/
├── src/
│   ├── main.cpp
│   ├── book.cpp
│   ├── member.cpp
│   ├── transaction.cpp
│   └── ...
├── include/
│   ├── book.h
│   ├── member.h
│   ├── transaction.h
│   └── ...
├── Makefile
├── README.md
└── ...
