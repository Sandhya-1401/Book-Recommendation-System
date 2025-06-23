# 🛠️ How to Use – Book Recommendation System

This guide will help you set up, run, and explore the Book Recommendation System on your local machine.

---

## 🗂️ Project Structure

```
Book-Recommendation-System/
├── app.py               # Main Python-Flask script
├── static/              # Static files (CSS, images)
├── templates/           # HTML templates
├── Preview/             # Screenshots & Demo video
├── book.pkl             # Book data matrix
├── popular.pkl          # Popular books data
├── pt.pkl               # Pivot table
├── similar_score.pkl    # Similarity scores (ML - Main File)
```

---

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

```bash
git clone https://github.com/Sandhya-1401/Book-Recommendation-System.git
cd Book-Recommendation-System
```

### 2️⃣ Create Virtual Environment (Optional but Recommended)

```bash
python -m venv env
```

- For **Windows**:
```bash
env\Scripts\activate
```

- For **Mac/Linux**:
```bash
source env/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Flask App

```bash
python app.py
```

### 5️⃣ Open in Browser

Visit:  
[http://localhost:5000](http://localhost:5000)

Now explore the interface and start getting book recommendations!

---

## 📦 `.pkl` Files – What They Are

This project uses several `.pkl` (Pickle) files to store data and models:

| File Name           | Purpose                        |
|---------------------|---------------------------------|
| `book.pkl`          | Pre-processed book data         |
| `popular.pkl`       | Most popular books              |
| `pt.pkl`            | Pivot table of user ratings     |
| `similar_score.pkl` | Precomputed similarity scores   |

These files **cannot be opened in GitHub directly**, but they are **used internally by the app**.

---

## 🙌 Contributing & Support  

If you encounter any issues or want to contribute, feel free to **raise an issue** or **submit a pull request**.  

---

## 📬 Contact

**Developed by:** Rana Sandhya  
**Email:** [ranasandhya093@gmail.com](mailto:ranasandhya093@gmail.com)  
**GitHub:** [github.com/Sandhya-1401](https://github.com/Sandhya-1401)  
**LinkedIn:** [linkedin.com/in/rana-sandhya1729](https://linkedin.com/in/rana-sandhya1729)  

---

**🙏 Thank You for Exploring This Project!**
