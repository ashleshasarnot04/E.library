# E.library
🔹 Project Overview

This project is a console-based library management system.
Users can:

Add new books to the inventory.

Borrow a book (if available).

Return a book.

Undo the last borrow/return action using a stack.

Search/filter for books by title or author.

Display all books in the library.

🔹 Features in Detail
1. Inventory Management (Linked List)

Each book is a node in the linked list with fields:

Book ID

Title

Author

Availability (Yes/No)

Easy insertion/deletion of books.

2. Borrow & Return

When a user borrows a book:

Status changes to Unavailable.

Action is pushed onto the stack.

When a user returns a book:

Status changes to Available.

Action is pushed onto the stack.

3. Undo Functionality (Stack)

Undo the last action (borrow/return).

Pop action from the stack and reverse it.

Example: If the last action was borrow Book A, undo will mark it available again.

4. Search & Filter

Search by title or author in the linked list.

Case-insensitive matching for better usability.

🔹 How to Run

Compile the C++ code (g++ elibrary.cpp -o elibrary).

Run the program (./elibrary).

Menu will display options:
