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
1. **User Login Page:**
   - User enters medical details such as:
     - Blood Pressure
     - Diabetes status
     - Any other existing diseases
     - Allergies
     - Weight & Height
   - These values are **not predicted by the chatbot**—they are provided by the **doctor or medical expert**, and stored safely in the backend.

2. **Chatbot Interaction:**
   - Chatbot asks the user for symptoms
   - User responds in text form (chat interface)
   - Backend processes symptoms using **Decision-Tree logic**

3. **Disease Prediction:**
   - System predicts possible diseases based on:
     - User symptoms
     - Medical history (BP, diabetes, allergies, etc.)

4. **Output Displayed to User:**
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
