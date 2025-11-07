# Design-and-development-of-cardless-ATM-system-using-python-and-django-using-IoT-device
Design and development of cardless ATM system using python and django using IoT device
# Cardless ATM System using Multi-Factor Biometric Authentication

## 📘 Project Overview

The **Cardless ATM System** is designed to eliminate the need for physical ATM cards by integrating **facial recognition**, **fingerprint authentication**, and **OTP verification** as a secure, multi-layered user authentication process. This system enhances both **security** and **user convenience**, ensuring that transactions are protected through biometric and encrypted verification methods.

The project demonstrates how artificial intelligence and embedded systems can be used together to provide next-generation banking solutions.

---

## ⚙️ System Requirements

**Hardware:**

* Windows system with minimum **8GB RAM** and **256GB SSD**
* **Raspberry Pi 5** (for hardware control and fingerprint module connection)
* **R307s Fingerprint Sensor Module**
* **Camera module** (for face detection and recognition)

**Software:**

* **Python 3.10+**
* **Django Framework**
* **OpenCV** (for image and face processing)
* **face_recognition** library (for biometric facial verification)
* **NumPy**, **Pandas**, and other dependencies

---

## 🧩 Installation Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/Cardless-ATM-System.git
   cd Cardless-ATM-System
   ```

2. **Create and Activate a Virtual Environment**

   ```bash
   python -m venv env
   source env/bin/activate   # for Linux/Mac
   env\Scripts\activate      # for Windows
   ```

3. **Install Required Libraries**

   ```bash
   pip install opencv-python
   pip install face_recognition
   pip install django
   pip install numpy pandas
   ```

4. **Run the Django Server**

   ```bash
   python manage.py runserver
   ```

---

## 🏗️ System Architecture

1. **Facial Recognition:** Captures user image through a camera and verifies identity against stored facial data using the `face_recognition` library.
2. **Fingerprint Authentication:** Uses the **R307s** module connected to **Raspberry Pi 5** for fingerprint matching.
3. **OTP Verification:** After biometric verification, the system sends an OTP to the registered mobile number for final confirmation.
4. **Transaction Execution:** Upon successful OTP validation, the transaction is processed securely.

---

## 🔐 Security Features

* Multi-factor authentication (Face + Fingerprint + OTP)
* Encrypted data storage and secure database communication
* Automatic account lockout after three consecutive failed attempts
* Continuous model improvement using authorized transaction data

---

## 💡 Future Enhancements

* Integration with **bank APIs** for real-time account validation
* Use of **AI-based spoof detection** to prevent facial or fingerprint forgery
* **Cloud-based data management** for scalability and distributed access

---

## 👨‍💻 Developed With

* **Python** — Core programming and data handling
* **OpenCV** — Facial detection and recognition
* **Django** — Web framework for backend logic and API endpoints
* **Raspberry Pi 5 + R307s** — Hardware integration for fingerprint authentication

---

## 📄 License

This project is developed for **academic and research purposes**. Modification and redistribution are permitted with appropriate credit to the authors.
