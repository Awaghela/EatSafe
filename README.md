# EatSafe 🍽️🔍

**Your True Food Companion**

EatSafe is a web-based application that makes food label reading **fast, easy, and safe** by automatically extracting ingredients from food labels and flagging **toxic ingredients** and **dietary restriction violations**. Built for everyone—from fitness enthusiasts to people with allergies—EatSafe helps users make informed food choices, one scan at a time.

---

## What is EatSafe?

- 📷 Scan food label images
- 🔍 Extract ingredients using OCR
- ⚠️ Instantly flag toxic or unsafe ingredients
- 🥗 Check against dietary restrictions
- 🌍 Designed for everyday users and health-conscious individuals

---

## Tech Stack

### Frontend

- HTML
- CSS
- Bootstrap

### Backend

- Python
- Flask

### Cloud & Infrastructure

- Google Cloud Platform
- Docker

### Database

- SQLite (via SQLAlchemy)

### OCR

- Google Cloud Vision API

---

## System Architecture

EatSafe follows a modular architecture:

1. User uploads a food label image via the web interface
2. The backend sends the image to the OCR service
3. Extracted text is processed to identify ingredients
4. Ingredients are analyzed against known toxic items and dietary rules
5. Results are displayed clearly to the user

---

## Local Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/eatsafe.git
cd eatsafe
```

### 2️⃣ Create Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Configure Environment Variables

Create a `.env` file:

```env
FLASK_SECRET_KEY=your-secret-key
```

### 5️⃣ Run the Application

```bash
python app.py
```

Access the app at: **http://127.0.0.1:5000**

---

## Demo

The application demonstrates:

- Image upload
- OCR-based ingredient extraction
- Clear warnings for unsafe ingredients
- Simple and intuitive UI

---

## Challenges Faced

- OCR inaccuracies with low-quality images
- Standardizing ingredient naming conventions
- Mapping ingredients to dietary rules reliably

---

## Future Scope

- ML-based ingredient classification
- Nutrition scoring and insights
- Multi-language food label support
- User profiles and scan history
- Mobile application

## Thank You

EatSafe — Enhancing lives (and snacks) one scan at a time.
