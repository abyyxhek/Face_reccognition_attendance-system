 📸 Face Recognition Attendance System with Email Reporting

A Python-based attendance system that uses **face recognition** to automatically mark attendance and **send attendance reports via email**. Built using OpenCV, Tkinter, and Yagmail, this project is designed for educational institutions or workplaces to automate attendance tracking.

---

## 🔧 Features

- 👤 Real-time Face Detection and Recognition  
- ✅ Automatic Attendance Marking  
- 📧 **Auto Email of Attendance Report (Daily/Weekly)**  
- 🖥️ User-Friendly GUI (Tkinter) for Admin Panel  
- 🗃️ Attendance stored in CSV or SQLite database  
- 📅 Daily and custom date-based attendance reports

---

## 🛠️ Tech Stack

- **Language:** Python 3.x  
- **Libraries:** OpenCV, Numpy, Pandas, Tkinter, PIL, Yagmail  
- **Storage:** CSV / SQLite  
- **Email Service:** Gmail via Yagmail

- 
---

## 🖥️ GUI Preview

- Add Student  
- Train Model  
- Take Attendance  
- Send Email Report  

---

## ✉️ How Email Reporting Works

- Uses **Yagmail** to connect with Gmail
- Automatically composes and sends attendance for the day
- You can configure email recipients and customize the format

✅ Make sure to enable **"Less secure app access"** or use an **App Password** in Gmail settings.

---

## 🚀 How to Run

1. **Clone the Repository**
```bash
git clone https://github.com/your-username/face-attendance-email.git
cd face-attendance-email
pip install -r requirements.txt
python train.py
python main.py
Edit automail.py and set your Gmail credentials:


yag = yagmail.SMTP('your_email@gmail.com', 'your_app_password')
