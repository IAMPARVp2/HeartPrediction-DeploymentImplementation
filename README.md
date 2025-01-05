# Heart Disease Prediction - Deployment 🚀

This project predicts the likelihood of heart disease using machine learning models. Built with Flask for the backend and deployed using **Docker containers** and **AWS** for scalable and efficient hosting.

---

## 🌟 Features
- Predict heart disease probability using pre-trained ML models.
- User-friendly web interface for data input and predictions.
- Fully containerized with **Docker** for portability.
- Deployment-ready for **AWS** or other cloud platforms.

---

## 🔧 Tech Stack
- **Python 3.12**
- **Flask** - Web framework
- **scikit-learn** - ML model training and prediction
- **Docker** - Containerization
- **AWS** - Cloud deployment
- **HTML/CSS/JavaScript** - Frontend

---

## 🗃️ Project Structure

```plaintext
Heart-Disease-Prediction-Deployment/
├── app.py                 # Main Flask app
├── prediction.py          # ML model prediction logic
├── model.pkl              # Trained ML model
├── heart_cleveland_upload.csv # Dataset for heart disease
├── templates/             # HTML templates for UI
├── static/                # Static files (CSS, JS)
├── requirements.txt       # Python dependencies
├── Dockerfile             # Docker setup for the app
├── README.md              # Project documentation
└── Untitled.ipynb         # Jupyter Notebook (training)
```

---

## 🚀 Deployment Options

### 1. Run Locally
```bash
# Step 1: Clone the repository
git clone https://github.com/<your-username>/Heart-Disease-Prediction-Deployment.git
cd Heart-Disease-Prediction-Deployment

# Step 2: Create a virtual environment
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate

# Step 3: Install dependencies
pip install -r requirements.txt

# Step 4: Run the Flask app
python app.py
```

### 2. Run with Docker
```bash
# Build Docker image
docker build -t heart-disease-prediction .

# Run the container
docker run -p 5000:5000 heart-disease-prediction
```

### 3. Deploy on AWS
- Use **Elastic Beanstalk**, **ECS**, or **Lightsail** to deploy the Dockerized app.
- Set environment variables if needed in your deployment platform.

---

## 📊 Dataset

The project uses the **Heart Disease Cleveland Dataset** to train and test the machine learning model. The dataset contains information such as age, sex, blood pressure, cholesterol, and other attributes to predict heart disease risk.

For more details, visit the dataset source: [Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease).

---

## 🎯 Future Enhancements
- Add CI/CD pipelines for automated deployments.
- Use Kubernetes for managing containers at scale.
- Add more machine learning models for comparison and analysis.
- Implement a mobile-friendly UI.
- Provide an API for third-party integrations.

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork this repository, create a branch, and submit a pull request.

### Steps to Contribute
1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push to your branch:
   ```bash
   git add .
   git commit -m "Added new feature"
   git push origin feature-name
   ```
4. Submit a pull request.

---

## 📧 Contact
For any questions or feedback, feel free to reach out:

- **Email**: jainv1071@gmail.com 
- **GitHub**: [IAMPARVp2](https://github.com/IAMPARVp2)
