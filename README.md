# Devangi
git clone https://github.com/your_username/zomato-rating-prediction.git

# Navigate into the repository directory
cd zomato-rating-prediction

# Create a virtual environment
python -m venv zomato_env

# For Windows
zomato_env\Scripts\activate

# For macOS/Linux
source zomato_env/bin/activate

pip install pandas numpy scikit-learn matplotlib seaborn flask cassandra-driver logging

zomato-rating-prediction/
│
├── data/                 # Directory for storing data files
├── notebooks/            # Jupyter notebooks for EDA and model building
├── scripts/              # Python scripts for data processing and model training
├── models/               # Directory to save trained models
├── logs/                 # Directory for log files
├── README.md             # Project description and instructions
├── requirements.txt      # List of required Python libraries
├── .gitignore            # Git ignore file

pip freeze > requirements.txt

# Initialize git (if not already initialized)
git init

# Add all files to the staging area
git add .

# Commit the changes
git commit -m "Initial project setup"

# Push the changes to GitHub
git push origin main
