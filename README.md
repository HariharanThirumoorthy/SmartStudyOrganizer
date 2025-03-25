# Smart Study Organizer

The **Smart Study Organizer** is an AI-powered real-time object detection system that helps recognize and categorize study-related items on your desk. Built with **YOLOv5**, **OpenCV**, and integrated into a lightweight **Flask web app**, this project aims to enhance productivity by assisting students and professionals in organizing their workspace.

---

## 🎯 Goal

To automate the process of desk organization by identifying commonly used study objects (e.g., notebooks, pens, laptops, textbooks) in real-time using object detection.

---

## 🔧 Technologies Used

- Python
- YOLOv5
- OpenCV
- Flask
- HTML/CSS (for web frontend)
- TensorFlow (optional for extensions)

---

## 📌 Features

- 🧠 **YOLOv5-based real-time object detection**
- 🖥️ **Web interface built with Flask**
- 🧾 **Customizable detection labels for study-related objects**
- 📷 **Webcam integration for live workspace scanning**
- 🧹 Encourages **clean and organized study environments**

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/smart-study-organizer.git
cd smart-study-organizer
2. Install Dependencies
bash
Copy
pip install -r requirements.txt
3. Download YOLOv5 Weights
Go to YOLOv5 releases

Download yolov5s.pt and place it in the weights/ directory.

4. Run the Flask App
bash
Copy
python app.py
Open your browser and navigate to http://127.0.0.1:5000

Start detecting objects live via webcam

📷 Demo
Live Detection	Detected Items
🗂 Project Structure
cpp
Copy
smart-study-organizer/
├── app.py
├── detect.py
├── weights/
│   └── yolov5s.pt
├── templates/
│   └── index.html
├── static/
├── data/
├── requirements.txt
└── README.md
📄 License
This project is licensed under the MIT License – feel free to use, modify, and distribute.

🙌 Acknowledgements
YOLOv5 by Ultralytics






