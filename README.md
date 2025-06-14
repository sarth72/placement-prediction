📘 Placement Prediction Web Application
A machine learning–based web application that predicts the top 3 companies a student is most likely to get placed in, based on their resume, CGPA, skills, certifications, aptitude score, GATE score, and college tier.
Built as a final year project for Savitribai Phule Pune University (SPPU) – B.E. (Computer Engineering).

🔍 Features
📄 Resume and Certificate PDF parsing (using PyMuPDF)

🧠 ML model using TF-IDF + scaled numeric features

📊 Inputs: CGPA, skills, aptitude, college tier, GATE score, experience

🧪 Built-in aptitude test with auto-score injection

🏆 Predicts top 3 company placement probabilities

💾 Data saved via SQLAlchemy (SQLite DB)

🔐 Admin and student login system

🎨 Responsive frontend with custom CSS and background video

🛠️ Technologies Used
Frontend	Backend	Machine Learning	Utilities
HTML, CSS, JS	Flask (Python)	scikit-learn	PyMuPDF (fitz)
Bootstrap	SQLAlchemy	TF-IDF, LabelEncoder, LogisticRegression	SQLite

⚙️ How to Run Locally
Clone the repository

bash
Copy code
git clone https://github.com/sarth72/placement-prediction.git
cd placement-prediction
Install dependencies

bash
Copy code
pip install -r requirements.txt
Run the app

bash
Copy code
python app.py
Open in your browser:
http://127.0.0.1:5000

🧠 ML Model
Model: Trained on a dataset of student profiles and placement outcomes

Inputs: Resume vector (TF-IDF), CGPA, experience

Output: Top 3 matching companies with probability scores

Preprocessing: Feature scaling, label encoding

Files:

hiring_model.pkl

tfidf_vectorizer.pkl

feature_scaler.pkl

📄 Project Details
🏫 Submitted To: Savitribai Phule Pune University (SPPU)

👨‍🏫 Guide: Prof. Vaishali Warake

🧑‍💻 Team Members:

Sarthak Ashok Gore

Rameshwar Babasaheb Patare

Samiksha Sunil Kanawade

Sanika Anil Gurde

📍 Institute: P.K. Technical Campus, Pune

📅 Academic Year: 2024–2025

📰 Research Publication
📘 Published in IRJMETS (Volume 06, Issue 11 – Nov 2024)

🧾 ISSN: 2582-5208

🏆 Impact Factor: 8.187

📎 www.irjmets.com

📸 Screenshots (Add Yours Here)
Add image files in /screenshots/ and link them below:

scss
Copy code
![Input Form](screenshots/input_form.png)
![Result Page](screenshots/result_page.png)
💡 Future Improvements
Add live deployment (Render, Replit)

Improve model accuracy with real training data

ATS score calculation and resume rating

Admin panel with dashboard analytics

📬 Contact
GitHub: sarth72

LinkedIn: [Add your LinkedIn URL here]