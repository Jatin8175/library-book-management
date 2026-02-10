# 📚 Library Books Management (Python)

## 📖 Overview

This Python program allows you to store and manage details of books in a small library system using **dictionary, list, set, and tuple** data structures.
You can add books, view them, find the most expensive and cheapest book, search by genre, and list unique authors.

---

## ⚙️ Features

* Add multiple books with details:

  * Book ID
  * Title
  * Author
  * Price
  * Genres
* Display all stored books
* Find:

  * Most expensive book
  * Cheapest book
* Search books by genre
* Show unique authors
* Create tuple of all book titles

---

## 🧱 Data Structures Used

* **Dictionary (`dict`)** → Store book details using Book ID as key
* **List (`list`)** → Store genres and prices
* **Set (`set`)** → Store unique authors
* **Tuple (`tuple`)** → Store book titles

---

## ▶️ How to Run

1. Install Python (3.x recommended)
2. Save the file as:

   ```
   library_books.py
   ```
3. Run the program:

   ```
   python library_books.py
   ```
4. Enter book details when prompted.

---

## 💻 Example Input

```
Enter number of books: 2

Enter details of book 1
Book ID: 101
Title: Python Basics
Author: John
Price: 350
Genres: Programming, Education

Enter details of book 2
Book ID: 102
Title: Data Science
Author: Alice
Price: 550
Genres: Data, AI
```

---

## 📤 Example Output

```
----- Library Books -----

Book ID: 101
Title: Python Basics
Author: John
Price: 350.0
Genres: ['Programming', 'Education']

Book ID: 102
Title: Data Science
Author: Alice
Price: 550.0
Genres: ['Data', 'AI']

Most Expensive Book:
Data Science - 550.0

Cheapest Book:
Python Basics - 350.0

Books in genre 'AI':
Data Science

Unique Authors:
John
Alice

Tuple of Book Titles:
('Python Basics', 'Data Science')
```

---

## 🧠 Program Logic (Simple)

1. Take number of books from user
2. Store book details in dictionary
3. Print all books
4. Calculate max & min price
5. Search books by genre
6. Collect unique authors using set
7. Convert titles into tuple

---

## 📌 Requirements

* Python 3.x
* No external libraries required

---

## 👨‍💻 Author

Created for learning **Python Data Structures** and basic library management logic.

---

## 📜 License

Free to use for educational purposes.

