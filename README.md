# 📚 Library Management System

![Library Screenshot](images/LibrarySystem.png)

A simple and modular Library Management System built in C that allows users to manage book records using a console-based interface. This project was developed as a coursework submission and demonstrates effective use of file handling, modular functions, and best coding practices.

## 🚀 Features

- ✅ Add new books with date and time  
- 📖 Display all available books  
- ❌ Delete books by ID  
- 🔍 Search books by ID  
- 📥 Issue books to students with timestamp  
- 📤 Return issued books and update records  
- 🗂️ Maintain issued book history  
- 🔒 Input validation for reliable data entry  
- 💡 Modular structure with switch-based main menu

## 🛠 Technologies Used

- C Programming Language  
- File Handling (binary and text)  
- Standard C Libraries (`stdio.h`, `stdlib.h`, `string.h`, `time.h`)

## 📂 Project Structure

```text
├── main.c              # Contains the main function and menu system
├── addBook()           # Adds a new book to the database
├── booksList()         # Displays all books
├── del()               # Deletes a book by ID
├── issueBook()         # Issues a book to a student
├── returnBook()        # Processes book returns
├── issueList()         # Displays issued book records
├── searchBook()        # Searches for a book by ID
├── books.txt           # File to store book data
├── issue.txt           # File to store issued book data



## 📌 Best Practices Followed

- Modular code using well-named functions  
- Switch statements for clear flow control  
- Properly managed file operations (`fopen`, `fclose`, `fwrite`, `fread`)  
- Formatted output for readability  
- Input validation to prevent incorrect data entries  
- Use of `time.h` for accurate timestamping

## 🙋‍♂️ Author

Project developed by **Tajith Rashidha**
