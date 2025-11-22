# City Library Digital Management System
A Java-based application designed to digitize the operations of the City Central Library. This system manages books, members, issue/return transactions, and uses File Handling + Java Collections Framework for efficient data storage and retrieval.

# Project Overview
The goal of this project is to create a simple, menu-driven Library Management System that:

Stores books and members using HashMap


Handles issuing and returning of books


Saves data persistently using text files



Uses Comparable and Comparator for sorting



Uses Buffered I/O + Character Streams for fast file operations



# Features
Book Management


Add new books



Store book details (ID, title, author, category, issued status)



Search books by title, author, or category



Sort books by title (Comparable)



# Member Management


Add members



Store member details (ID, name, email)




Maintain list of issued books for each member



# Transaction Handling


Issue a book to a member


Return a book



Update records in both book & member collections



# File Handling




Books stored in books.txt




Members stored in members.txt



Files auto-created if missing



BufferedReader/BufferedWriter used for efficient I/O



# Technologies Used


Java 8+

File Handling (Text Files)



Java Collections Framework




HashMap
ArrayList
Comparable / Comparator

BufferedReader / BufferedWriter
