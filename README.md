
# 📚 C++ Library Management System

A console-based Library Management System built in C++. This project enables basic functionalities for managing books in a library, issuing and returning books to/from students, and administrative features accessible to librarians via password protection.

## 🚀 Features

- Add, delete, or modify book records
- Search books by name or ID
- Issue and return books
- View issued book history
- Fine calculation for late returns
- Student and Librarian roles
- Password-protected librarian panel
- Book categorized by branches (AI, OOP, Python, etc.)

## 🛠️ Technologies Used

- C++
- File Handling (Binary I/O)
- Console UI (Windows-based using `<conio.h>`)
- OOP (Object-Oriented Programming)

## 📂 Project Structure

```
.
├── main.cpp              # Complete program file with all features
├── Booksdata.txt         # Binary file to store book records
├── student.txt           # Binary file to store issued book records
├── password.txt          # Text file to store librarian password
```

## 🔐 Default Credentials

- **Librarian password**: `pass`

## 💡 How to Run

1. **Compile the Program**
   ```bash
   g++ -o library_system main.cpp
   ```

2. **Run the Executable**
   ```bash
   ./library_system
   ```

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change or add.

## 📃 License

This project is open-source and available under the [MIT License](LICENSE).
