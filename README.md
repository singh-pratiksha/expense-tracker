
# 💰 Abstractive Expense Tracker By Pratiksha Singh

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

---

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

## ✨ Future Enhancements

- 📊 Graphical analytics (bar/pie charts)
- 🧾 Export to CSV/PDF
- 🔐 User authentication
- ☁️ Cloud sync & backup support
- 📆 Monthly budgeting and category tracking

---

## 🙋‍♀️ Author

**Pratiksha Singh**  
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
