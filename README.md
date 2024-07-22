# Library-management-System
## Description
This project is a simple library management system written in C. It allows users to manage a collection of books by adding new books, issuing books to users, returning books, and searching for books.

## Features
- Add new books to the library
- Issue books to users
- Return books to the library
- Search for books by title, author, or publisher
- Persistent storage of book records using file handling

## Prerequisites
To compile and run this project, you will need:
- GCC compiler (or any compatible C compiler)
- A terminal or command prompt to execute commands
- 
## Usage
When you run the program, you will see a menu with options:

Add a new book
Issue a book
Return a book
Search for a book
Exit

## Example Usage

Adding a Book

Enter your choice: 1
Enter book title: The C Programming Language
Enter author name: Brian W. Kernighan, Dennis M. Ritchie
Enter publisher name: Prentice Hall
Book added successfully.

Issuing a Book

Enter your choice: 2
Enter book ID: 1
Book issued successfully.

Returning a Book

Enter your choice: 3
Enter book ID: 1
Book returned successfully.

Searching for a Book

Enter your choice: 4
Enter search query: C Programming
Book ID: 1
Title: The C Programming Language
Author: Brian W. Kernighan, Dennis M. Ritchie
Publisher: Prentice Hall
Status: Available
File Format
Book records are stored in a text file named books.txt. Each record includes:

Book ID
Title
Author
Publisher
Status (Available or Issued)

Error Handling

The program includes basic error handling for invalid inputs and file operations. If an error occurs, an appropriate message is displayed to the user.

## Future Enhancements
Integrate with a database for more efficient data management
Add a graphical user interface (GUI) for better user interaction
Implement user authentication for role-based access control
Enhance search functionality with more advanced query options
