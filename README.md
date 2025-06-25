# 🛍️ Flash_Ecommerce - Flask E-Commerce Website

A modern and responsive e-commerce website built using **Flask**, **HTML**, **CSS**, and **JavaScript**. This project showcases a clean frontend design integrated with Flask as a lightweight backend for dynamic routing and asset management.

---

## 🚀 Features

- 🖼️ Responsive homepage with promotional banners
- 🛒 Product listings with categories like clothes, shoes, watches, accessories, and more
- 📱 Mobile-friendly navigation and menu
- 📧 Newsletter subscription modal
- 💡 Clean UI with organized sections (new arrivals, top rated, trending)
- 🌐 Static files served using Flask `url_for('static', ...)`
- 🔒 Ready to integrate authentication and cart system

---

## 🗂️ Project Structure

Flash_Ecommerce/
├── app.py                     ✅ Main Flask file
├── requirements.txt           ✅ List of Python packages
├── Procfile                   ✅ For Render to run your app
├── templates/                 ✅ HTML files here
│   └── index.html, ...
├── static/                    ✅ CSS, JS, images, etc.
│   ├── css/
│   ├── js/
│   └── images/



---

## 🧰 Tech Stack

- **Backend**: Python (Flask)
- **Frontend**: HTML, CSS, JavaScript
- **Deployment**: Render

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Flash_Ecommerce.git
cd Flash_Ecommerce
exit
---
Create a Virtual Environment (Optional)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate    # macOS/Linux
venv\Scripts\activate       # Window
---
 Install Requirements
bash
Copy
Edit
pip install -r requirements.txt
---
4. Run the Flask App
bash
Copy
Edit
python app.py
Go to: http://localhost:5000
---
🌍 Deployment on Render
Make sure you have requirements.txt and Procfile.

Steps:
Push the code to GitHub

Go to https://render.com

Create a new Web Service

Connect your GitHub repository

Fill in:

Setting	Value
Build Command	(leave blank)
Start Command	gunicorn app:app
Runtime	Python
Publish Dir	(leave blank)
---
Click "Create Web Service"
---
Your website will go live shortly 🚀

🙌 Acknowledgements
Inspired by modern UI/UX e-commerce designs

Icons and assets used are from royalty-free resources
---
Author: Rakesh Rocky
📧 Email: rakeshthangaraj89@gmail.com

⭐ Star this repo if it helped you!

yaml
Copy
Edit

---

Let me know if you'd like this version saved as a `.md` file or need it auto-added to your repo!








