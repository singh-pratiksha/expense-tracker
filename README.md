
# 💰 Abstractive Expense Tracker

A beautifully designed, beginner-friendly **desktop expense tracker** built using **Python**, **Tkinter**, **SQLite**, and **TkCalendar**. This tool helps you record, update, and manage your personal or small business expenses efficiently with a sleek user interface.

---

## 🚀 Features

- ✅ Add daily expenses with details
- ✅ View all expenses in a sortable table
- ✅ Edit or delete specific entries
- ✅ Delete all records with one click
- ✅ Clear input fields anytime
- ✅ Convert any entry to a readable sentence
- ✅ Read your expense before saving
- ✅ Local SQLite database integration
- ✅ Simple, responsive GUI using Tkinter

---

<!-- ## 🖼️ GUI Preview

> *Insert screenshot here if available, or ignore this section until added.* -->

## 🛠 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/singh-pratiksha/expense-tracker.git
cd expense-tracker
```

### 2. Install Required Libraries

Only one library needs to be installed:

```bash
pip install tkcalendar
```

> `tkinter` and `sqlite3` are included in standard Python installations.

---

## ▶️ Usage

Run the app with:

```bash
python main.py
```

You’ll see a simple and intuitive GUI window. From there, you can:

- 📅 Select a date
- 🧾 Enter payee, description, and amount
- 💳 Choose payment method (Cash, UPI, Card, etc.)
- ➕ Add new expense
- 🧮 View and scroll all records
- ✏️ Edit or ❌ delete individual records
- 🗑️ Clear all records
- 📢 Convert expense to a readable sentence

---

## 📁 Project Structure

```
expense-tracker/
│
├── main.py                  # Main GUI app file
├── Expense Tracker.db       # Auto-generated SQLite database file
└── README.md                # Project documentation
```

---

## 🗃️ Database Schema

The database automatically creates the following table:

```sql
CREATE TABLE IF NOT EXISTS ExpenseTracker (
    ID INTEGER PRIMARY KEY AUTOINCREMENT NOT NULL,
    Date DATETIME,
    Payee TEXT,
    Description TEXT,
    Amount FLOAT,
    ModeOfPayment TEXT
);
```

---

## 📚 Technologies Used

- **Python 3.x** – Core language
- **Tkinter** – GUI framework
- **tkcalendar** – Date picker widget
- **SQLite3** – Lightweight local database

---

## 📸 Project Screenshots
![Screenshot 2025-07-06 195603](https://github.com/user-attachments/assets/97a281f4-5690-43cf-832e-51c59c0b97a9)
![Screenshot 2025-07-08 190504](https://github.com/user-attachments/assets/fc7bce98-ffd3-4cea-83b3-f2e2ab583b80)
![Screenshot 2025-07-08 191323](https://github.com/user-attachments/assets/b111f8bd-9097-42b7-b097-6c0e0ffb303f)
![Screenshot 2025-07-08 191606](https://github.com/user-attachments/assets/964a15a3-0c33-4aec-81d2-0369ea63d3c4)
![Screenshot 2025-07-08 191653](https://github.com/user-attachments/assets/5d02864b-598c-4a7d-83c5-156037826a7f)
![Screenshot 2025-07-08 191712](https://github.com/user-attachments/assets/08006276-3a66-4579-8bb1-a7652fd83b1b)
![Screenshot 2025-07-08 191730](https://github.com/user-attachments/assets/c1719c4e-0833-464d-8bc9-7847e2ac88c0)







---
## ✨ Future Enhancements

- 📊 Graphical analytics (bar/pie charts)
- 🧾 Export to CSV/PDF
- 🔐 User authentication
- ☁️ Cloud sync & backup support
- 📆 Monthly budgeting and category tracking

---

## 🙋‍♀️ Author

**Created with ❤️ by Pratiksha Singh**  
💼 Developer & Designer  
🔗 [LinkedIn](www.linkedin.com/in/pratiksha-singh-8b24a0221)  
🌐 [GitHub](https://github.com/singh-pratiksha/)

---

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## 🤝 Contributions

Contributions are welcome!  
Please open an issue or submit a pull request for any improvements or suggestions.

---

## 💬 Feedback

If you find this project useful, drop a ⭐️ and share your thoughts through issues or messages.
