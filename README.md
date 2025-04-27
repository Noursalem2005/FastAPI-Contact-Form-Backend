# FastAPI Contact Form Backend

This backend service is built using **FastAPI** to handle **contact form** and **user-submitted** data.  
It includes features like **CORS support**, **JSON data storage**, and **email notifications** for submitted forms.

---

## 📚 Overview

This FastAPI project provides endpoints to:
- Handle **form submissions** via POST requests.
- Save the submitted data to local **JSON files**.
- **Send email notifications** with the form data using Gmail's SMTP server.

It allows users to submit forms with their details, including **medical issues**, **preferred contact methods**, and **personal messages**. The data is then stored and sent as an email notification to a specified address.

---

## 🌟 Key Features

- **FastAPI** backend for efficient form handling.
- **CORS** enabled for cross-origin requests.
- Saves form data in **JSON** format.
- Sends email notifications using **SMTP** (via Gmail).
- Secure email sending using **Gmail App Password**.
- Two types of forms: **General User Form** and **Contact Form**.

---

## 🗂️ Project Structure

| Folder / File          | Purpose                                  |
|------------------------|------------------------------------------|
| `main.py`              | Contains the backend logic with FastAPI endpoints. |
| `requirements.txt`     | Lists dependencies (e.g., FastAPI, smtplib, etc.). |
| `vercel.json`          | Configuration file for Vercel deployment (optional). |
| `README.md`            | Project documentation.                  |

---

## 🚀 How to Run Locally

1. **Clone the repository**  
   👉 [GitHub Repository Link](https://github.com/Noursalem2005/FastAPI-Contact-Form-Backend)

   ```bash
   git clone https://github.com/Noursalem2005/FastAPI-Contact-Form-Backend
   cd your-repository-name
