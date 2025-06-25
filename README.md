# 🛍️ Flash_Ecommerce - Flask E-Commerce Website

A modern and responsive e-commerce website built using **Flask**, **HTML**, **CSS**, and **JavaScript**. This project showcases a clean frontend design integrated with Flask as a lightweight backend for dynamic routing and asset management.

---

## 🚀 Features

- 🖼️ Responsive homepage with promotional banners
- 🛒 Product listings with categories like clothes, shoes, watches, accessories, and more
- 📱 Mobile-friendly navigation and menu
- 📧 Newsletter subscription modal
- 🌐 Static files served using Flask `url_for('static', ...)`
- 💡 Clean and modern UI layout

---

## 🗂️ Project Structure



## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Flash_Ecommerce.git
cd Flash_Ecommerce
```

### 2. Create & Activate Virtual Environment

```bash
python -m venv venv
```

**Activate the environment:**

```bash
# macOS / Linux
source venv/bin/activate

# Windows
venv\Scripts\activate
```

---

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

---

### 4. Run the Flask App Locally

```bash
python app.py
```

Then open your browser at:

```
http://localhost:5000
```

---

## 🌍 Deployment on Render

> Make sure your project includes both `requirements.txt` and `Procfile`.

### Steps:

1. Push your project to GitHub  
2. Go to [https://render.com](https://render.com)  
3. Click **"New + → Web Service"**  
4. Connect your GitHub repository  

### Fill in the deploy form:

| Setting          | Value               |
|------------------|---------------------|
| Build Command    | *(leave blank)*     |
| Start Command    | `gunicorn app:app`  |
| Runtime          | Python              |
| Publish Directory| *(leave blank)*     |

---

Click **"Create Web Service"**

🚀 Your website will go live shortly!

---

## 🙌 Acknowledgements

- Inspired by modern UI/UX e-commerce designs
- Icons and assets are from royalty-free sources

---

## 👤 Author

**Rakesh Rocky**  
📧 rakeshthangaraj89@gmail.com

---

## ⭐ Support

If you found this project helpful, please ⭐ star the repository!
