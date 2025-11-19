# MediGuide – Healthcare Chatbot

## 📌 Overview
MediGuide is a **Java-based Healthcare Chatbot** designed to assist users with preliminary medical guidance. Through a conversational interface, the chatbot collects symptoms, analyzes them using **decision-tree logic**, and predicts possible diseases. It then provides recommended medicines, precautions, and diet suggestions.

This project aims to improve accessibility to basic medical knowledge and reduce dependency on frequent doctor visits for minor health concerns.

---

## 🚀 Features
- Interactive **chat-based symptom input**
- Disease prediction using **Decision Tree logic**
- Provides:
  - Suggested medication
  - Precautionary measures
  - Food & diet recommendations
- Simple and user-friendly console interface
- Fully implemented in **Java**
- Modular and easy-to-understand code structure

---

## 🛠️ Tech Stack
- **Backend Framework:** Spring Boot
- **Web Layer:** Spring Web MVC
- **Database Layer:** Spring Data JPA
- **Database:** MySQL
- **Build Tool:** Maven
- **Frontend:** HTML5, CSS3, JavaScript (for login and chatbot UI)
- **Architecture:** Layered Architecture (Controller → Service → Repository)
- **Version Control:** Git & GitHub

---

## 📁 Project Structure
```
MediGuide/
│
├── src/
│   ├── Main.java
│   ├── Chatbot.java
│   ├── DiseasePredictor.java
│   ├── SymptomsDatabase.java
│   └── Utils.java
│
├── assets/
│   └── screenshots/
│
└── README.md
```

---

## ▶️ How to Run
1. Clone this repository:
```
git clone https://github.com/your-username/MediGuide-Healthcare-Chatbot.git
```

2. Navigate to the project folder:
```
cd MediGuide-Healthcare-Chatbot
```

3. Compile the Java files:
```
javac src/*.java
```

4. Run the chatbot:
```
java src.Main
```

---

## 🧠 How It Works
1. **Phase 1 – Basic User Login & Profile Setup:**
- User enters initial personal details:
- Name
- Age
- Gender
- Weight & Height (BMI auto-calculated)
- These basic details help personalize predictions and build the foundation of the user's health profile.


2. **Phase 2 – Medical Information Entry:**
- After basic details, the system collects medically relevant information such as:
- Blood Pressure
- Diabetes status
- Any other existing diseases
- Chronic Conditions (long-term illnesses)
- Allergies
- Pregnancy Status (for female users)
- Recent Surgeries or Hospitalization
- These values are **not predicted by the chatbot**—they are provided by a **doctor or medical expert**, and safely stored in the backend.


3. **Chatbot Interaction:**
- The chatbot asks the user for symptoms
- User responds in chat-based text format
- Backend processes symptoms using **Decision-Tree logic** integrated with medical history


4. **Disease Prediction Engine:**
- The system predicts possible diseases based on:
- User symptoms
- Complete health profile (BP, diabetes, surgeries, BMI, allergies, chronic conditions, pregnancy, etc.)


5. **Output Displayed to User:**
- Remedies
- Medicines
- Precautions
- Diet recommendations

---

---

## 📚 Future Enhancements
- Integration of real-time medical databases
- Mobile app/GUI interface
- Machine Learning–based prediction model
- Voice-based interaction
- Multi-language support

---

## 👨‍💻 Authors
- Harshkumar Bhamare

---

## 📄 License
This project is licensed under the **MIT License**.

Feel free to contribute or open issues! 
