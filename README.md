###  📚 Library Management System (Python)

A simple **Library Management System** built in Python using **OOP concepts** and the `datetime` module.  
This project allows an **Admin** to manage books, issue them to students, calculate fines for late returns, and view issued/available books.

---

### ✨ Features

-  **Add Book** – Store book details with ID, title, and author.
-  **Issue Book** – Issue books to students with an issue date.
-  **Return Book** – Return books and calculate fines if returned late.
-  **Delete Book** – Remove a book from the library.
-  **Display Books** – Show all available books with their status.
-  **Issued Books List** – View all issued books with details.
-  **Fine Calculation** – ₹50 per day fine for late returns (after 30 days).

---

### 🛠 Technologies Used

- **Python 3**
- **OOP (Object-Oriented Programming)**
- **Datetime Module**

---
### 🔐 Login Credentials

| Role   | Username | Password |
|--------|----------|----------|
| Admin  | admin    | 1234     |

---

### 📜 How It Works

#### 1️⃣ Add Book
- Enter **Book ID**, **Book Title**, and **Author Name**.
- Marks the book as **Available (YES)**.

#### 2️⃣ Issue Book
- Enter **Student Name**, **USN**, and **Book Name**.
- Marks the book as **Issued (NO)** and records the **Issue Date**.
- User must return the book within **30 days**.

#### 3️⃣ Return Book
- Enter **Name** and **Book ID**.
- If returned after **30 days**, fine = ₹50 × extra days.
- Updates the book status to **Available (YES)**.

#### 4️⃣ Delete Book
- Removes a book from the system permanently.

#### 5️⃣ Display Books
- Shows all books with their availability status.

#### 6️⃣ Display Issued Books
- Lists all issued books with **Student Name, USN, Book ID, Title, and Issue Date**.

---

#### 📊 Example Output
Pycoders LIBRARY MANAGEMENT SYSTEM
1. Add book
2. Issue book
3. Return book
4. Display books
5. Delete book
6. Exit
Enter your choice: 1
Enter BOOK ID: B101
Enter BOOK Name: Python Programming
Enter Author name: John Doe
Data Entered Successfully for book id: B101
---
### 💡 Real-World Application

- Can be extended for **college libraries**, **public libraries**, or **personal book management**.  
- Can integrate with a **database** for permanent storage.  
- Can be converted into a **GUI app** using Tkinter or a **Web App** using Django/Flask.
---
## 🙏 Acknowledgements
Thanks to all contributors and libraries used in this project.




