# 🛠️ How to Use – Book Recommendation System

This guide will help you set up, run, and explore the Book Recommendation System on your local machine.

---

## 🗂️ Project Structure

Book-Recommendation-System/
├── app.py # Main Python-Flask script
├── static/ # Static files (CSS, images)
├── templates/ # HTML templates
├── Preview/ # Screenshots & Demo video
├── book.pkl # Book data matrix
├── popular.pkl # Popular books data
├── pt.pkl # Pivot table
├── similar_score.pkl # Similarity scores (ML- Main File)

## 🧾 Prerequisites

Before starting, make sure you have:

- ✅ Python 3.7 or higher installed
- ✅ pip (Python package installer)
- ✅ Git installed (for cloning the repo)

Optional but recommended:
- ✅ A virtual environment tool like `venv` or `conda`

---

## 🚀 Setup Instructions

### 1️⃣ Clone the Repository

git clone https://github.com/Sandhya-1401/Book-Recommendation-System.git
cd Book-Recommendation-System

### 2️⃣ Create Virtual Environment (Optional but Good Practice)

python -m venv env
source env/bin/activate     # For Linux/Mac
env\Scripts\activate        # For Windows

### 3️⃣ Install Dependencies

pip install -r requirements.txt

### 4️⃣ Run the Flask App

python app.py

### 5️⃣ Open in Browser

http://localhost:5000

Now explore the interface and start getting book recommendations!

--- 

## 📦 .pkl Files – What They Are

This project uses several .pkl (Pickle) files to store data and models:

| File Name           | Purpose                       |
| ------------------- | ----------------------------- |
| `book.pkl`          | Pre-processed book data       |
| `popular.pkl`       | Most popular books            |
| `pt.pkl`            | Pivot table of user ratings   |
| `similar_score.pkl` | Precomputed similarity scores |

These files cannot be opened in GitHub directly but will be loaded automatically in the app.

---

## 🙌 Contributing & Support  
If you encounter any issues or want to contribute, feel free to **Raise an issue** or **Submit a pull request**  <br>

### **📬 Contact**<br>

**Developed by:** Rana Sandhya <br>
**Email:** ranasandhya093@gmail.com <br>
**GitHub:** [Click Here](github.com/Sandhya-1401)<br>
**LinkedIn:** [Click Here](linkedin.com/in/rana-sandhya1729)<br>

**Thank You**
