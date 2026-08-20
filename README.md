# Smart Library Project
# 📚 Library Management System

A web-based **Library Management System** built using **Python and Flask**. This application helps manage books, students, borrowing, returns, reservations, fines, recommendations, and library analytics.

The system provides separate features for **Students** and **Administrators**, making library operations easier and more organized.

---

## ✨ Features

### 👨‍🎓 Student Features

- Student registration and login
- Browse available books
- Search books
- Borrow books
- Return books
- View currently borrowed books
- View borrowing history
- Reserve books
- Manage book reservations
- Add books to a wishlist
- View fines
- Pay fines
- Personalized book recommendations
- Reading analytics
- Password reset functionality

### 👨‍💼 Admin Features

- Admin dashboard
- Add new books
- Update book information
- Delete books
- Manage book copies
- View registered students
- View borrowed books
- Manage reservations
- Manage student fines
- View library statistics
- View reading analytics
- Manage password reset requests

---

## 🛠️ Technologies Used

- **Python**
- **Flask**
- **Flask-SQLAlchemy**
- **SQLite**
- **HTML**
- **CSS**
- **Pandas**
- **NumPy**
- **Scikit-learn**

---

## 📂 Project Structure

```text
Library-Management/
│
├── app.py
├── config.py
├── requirements.txt
├── runtime.txt
├── Procfile
│
├── add_sample_data.py
├── add_more_sample_data.py
├── migrate_passwords.py
│
├── train_model.py
├── model.pkl
├── best_model.pkl
├── classification_report.txt
│
├── static/
│   └── style.css
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── admin.html
│   ├── admin_panel.html
│   ├── admin_management.html
│   ├── admin_fines.html
│   ├── admin_reservations.html
│   ├── student.html
│   ├── student_dashboard.html
│   ├── student_login.html
│   ├── student_signup.html
│   ├── add_book.html
│   ├── all_books.html
│   ├── search_books.html
│   ├── borrowed_books.html
│   ├── borrowing_history.html
│   ├── reserve_book_confirm.html
│   ├── my_reservations.html
│   ├── my_fines.html
│   ├── pay_fine.html
│   ├── my_recommendations.html
│   ├── reading_analytics.html
│   └── ...
│
└── README.md
