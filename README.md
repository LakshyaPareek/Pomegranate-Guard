PomegranateGuard 🛡️
PomegranateGuard is an AI-powered Full-Stack Web Application developed for the detection and diagnosis of diseases affecting pomegranate fruits. The system leverages advanced Deep Learning techniques, including Convolutional Neural Networks (CNNs) and Transformer-based architectures, to deliver accurate and efficient disease classification and analysis.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🚀 Key Features
• Image-Based Disease Detection
Upload an image of a pomegranate fruit to receive an instant AI-generated diagnosis.
• Symptom Checker
Analyze diseases through natural language symptom descriptions using intelligent text-based processing.
• Disease Information Library
Access detailed information regarding symptoms, causes, prevention methods, and treatment recommendations for common pomegranate diseases.
• Secure Authentication System
Integrated user registration and login functionality for secure access and personalized interaction.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🛠️ Technology Stack
Frontend
• HTML5
• CSS3
• JavaScript
Backend
• Flask (Python)
Database
• SQLite
• SQLAlchemy ORM
Artificial Intelligence
• TensorFlow
• Keras
Deep Learning Models
• Convolutional Neural Networks (CNN)
• Hybrid HBO-Optimized Models
• Transformer Architectures
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📥 Installation & Setup Guide
1️⃣ Clone the Repository
git clone https://github.com/Prosquries/PomegranateGuard_1B.git
cd PomegranateGuard_1B
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📦 Model Files Information
Model Files link: https://drive.google.com/drive/u/1/folders/1oFR9ssk2eakVTN3HyXgg7X1zCOUfcb-F
The trained model files (.h5) are included within the repository.
Note: Some model files exceed GitHub’s standard file size limits and therefore require Git LFS (Large File Storage) for proper handling and version control.
Install Git LFS before cloning the repository to ensure all model files download correctly.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📂 Dataset Download (Optional)
The raw dataset is hosted externally due to its large size.
The dataset used for training and evaluation is publicly available to ensure research reproducibility and transparency.
•	Dataset Title: PomegranateGuard: Agricultural Disease Dataset 
•	Source: Kaggle 
•	License: Attribution 4.0 International (CC BY 4.0) 
•	Format: Image-based classification dataset (JPEG/PNG) 
Dataset Link:
https://www.kaggle.com/datasets/aaravmathur2005/pomegranateguard-agricultural-disease-dataset
Download the dataset folder from the Google Drive project directory if you plan to retrain or fine-tune the models.

Dataset Folder:
https://drive.google.com/drive/u/1/folders/1oFR9ssk2eakVTN3HyXgg7X1zCOUfcb-F
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
⚙️ Environment Setup
🐧 Linux / 🍎 macOS
It is recommended to use Python 3.12.
Create Virtual Environment
python3.12 -m venv venv
Activate Environment
source venv/bin/activate
Install Dependencies
pip install -r app/requirements.txt
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🪟 Windows
Create Virtual Environment
python -m venv venv
Activate Environment
.\venv\Scripts\activate
Install Dependencies
python -m pip install -r app/requirements.txt
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🤖 Model Linking
The application expects the trained models to be accessible inside the app directory.
Linux/macOS
ln -s ../model ./app/model
Windows
mklink /D app\model ..\model
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
▶️ Running the Application
Navigate to the application directory and start the Flask server.
cd app
python app.py
After successful startup, access the application using:
http://127.0.0.1:5000
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🐳 Docker Deployment
Build Docker Image
docker build -t pomegranate-guard .
Run Docker Container
docker run -p 5000:5000 pomegranate-guard
Access the application at:
http://localhost:5000
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🧪 Testing
Functional Unit Testing
cd app
pytest tests/
UI Automation Testing
Requires Selenium and a compatible WebDriver installation.
pytest "Testing Automation/test_PomegranateGuard.py"
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📊 Dataset Evaluation & Performance
The project includes a complete evaluation framework containing:
• Classification Reports
• Confusion Matrices
• Training & Validation Curves
• Accuracy and Loss Analysis
All evaluation resources are available in the evaluation/ directory.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🛠️ Troubleshooting
Missing Model Files
Ensure Git LFS is installed before cloning the repository. Missing .h5 files may cause model loading failures.
Database Errors
If database initialization fails:
Delete:
app/instance/site.db
Restart the application.
The database schema will be recreated automatically.
Port Conflict
If port 5000 is already in use, modify the port configuration inside:
app/app.py
Example:
app.run(port=5001)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📜 License
This project is intended for educational, academic, and research purposes only.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
👨‍💻 Developer
Created by Lakshya Pareek
GitHub: https://github.com/Lakshya-Pareek-1
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
PomegranateGuard — Intelligent AI-Based Disease Detection for Pomegranate Crops 🛡️

