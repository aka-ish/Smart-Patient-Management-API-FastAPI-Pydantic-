# 🏥 Patient Management API (FastAPI)

A lightweight and efficient REST API built using FastAPI to manage hospital patient records.
This project demonstrates real-world backend concepts like CRUD operations, data validation, and computed health metrics.

---

## 🚀 Key Features

* Create, Read, Update, Delete (CRUD) patient records
* Input validation using Pydantic
* Automatic BMI calculation
* Health classification (Underweight, Normal, Overweight, Obese)
* Sorting patients by height, weight, or BMI
* JSON-based data storage (beginner-friendly approach)

---

## 🛠️ Tech Stack

* FastAPI
* Python
* Pydantic
* JSON

---

## 📊 Sample Data

```json
{
  "P001": {
    "name": "Akash",
    "city": "Delhi",
    "age": 24,
    "gender": "male",
    "height": 1.75,
    "weight": 70
  }
}
```

---

## ▶️ Run the Project

```bash
pip install fastapi uvicorn
uvicorn main:app --reload
```

---

## 🌐 API Highlights

* `GET /view` → View all patients
* `GET /patient/{id}` → Get patient details
* `POST /create` → Add new patient
* `PUT /edit/{id}` → Update patient
* `DELETE /delete/{id}` → Delete patient

---

## 💡 What I Learned

* Building REST APIs using FastAPI
* Data validation with Pydantic
* Working with HTTP methods & status codes
* Structuring backend applications

---

## 👨‍💻 Author

Akash Mohan
