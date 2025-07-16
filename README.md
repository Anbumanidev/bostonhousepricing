
🏠 Boston House Pricing Prediction
End-to-end machine learning project to predict Boston house prices, built with Python, Flask, Docker, and deployed on Heroku.



📌 Project Overview
This project demonstrates a complete machine learning workflow:

Data analysis and preprocessing

Model training with Linear Regression

Model saving and serving with Flask

Containerization with Docker

CI/CD with GitHub Actions

Deployment to Heroku

Dataset used: BostonHousing.csv (included in the repository).

🧰 Technologies & Tools
Tool	Purpose
Python 3.7	Programming language
Scikit-learn	Machine learning modeling
Pandas & NumPy	Data manipulation and analysis
Flask	Web application framework
Docker	Containerization and portability
GitHub Actions	CI/CD automation
Heroku	Cloud deployment
VS Code	Source code editor
Git CLI	Version control

⚙️ Project Structure
bash
Copy
Edit
.
├── .github/workflows/              # GitHub Actions workflows
├── templates/                      # HTML templates for Flask
│   └── home.html
├── BostonHousing.csv               # Dataset
├── Dockerfile                      # Docker configuration
├── LICENSE                         # Project license (Apache 2.0)
├── Linear Regression ML Implementaton.ipynb  # Jupyter notebook with EDA & modeling
├── Procfile                        # For Heroku deployment
├── README.md                       # Project documentation
├── app.py                          # Flask application
├── regmodel.pkl                    # Saved regression model
├── scaling.pkl                     # Saved scaler for preprocessing
├── requirements.txt                # Python dependencies
└── .gitignore                      # Files/folders to be ignored by git
🚀 Setup & Installation
Clone the repo:

bash
Copy
Edit
git clone https://github.com/Anbumanidev/boston-house-price-prediction.git
cd boston-house-price-prediction
Create and activate environment:

bash
Copy
Edit
conda create -p venv python=3.7 -y
conda activate ./venv
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
🧪 Run Locally
bash
Copy
Edit
python app.py
Then, open your browser and navigate to:

cpp
Copy
Edit
http://127.0.0.1:5000/
🐳 Run with Docker
Build the Docker image:

bash
Copy
Edit
docker build -t boston-house-app .
Run the container:

bash
Copy
Edit
docker run -p 5000:5000 boston-house-app
🌐 Deployment
The project is configured to deploy on Heroku using:

Procfile

Docker (optional)

GitHub Actions for CI/CD

✅ Features
Linear Regression model trained to predict Boston house prices

Web interface built with Flask to take user inputs

Containerized using Docker for easy deployment

Automated CI/CD workflow with GitHub Actions

Live deployment to Heroku

📊 Model Details
Algorithm: Linear Regression

Libraries: scikit-learn, pandas, numpy

Saved as: regmodel.pkl

Scaler saved as: scaling.pkl

📄 License
This project is licensed under the Apache-2.0 License – see the LICENSE file for details.

✍️ Author
Anbumanidev

GitHub

⭐️ Contribute
Contributions, issues, and feature requests are welcome!
Feel free to fork this repository and submit a pull request.
