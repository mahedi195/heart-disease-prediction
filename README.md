# Navigate to your project directory
cd /path/to/your/project

# Step 1: Create a virtual environment
python -m venv venv

# Step 2: Activate the virtual environment
# On Windows:
venv\Scripts\activate

# Step 3: Install required dependencies
# pip install streamlit numpy joblib
pip install -r requirements.txt

# Step 4: Run the Streamlit app
streamlit run app.py

# dockerization
docker build -t heart_disease_project .

docker info
docker run -p 8501:8501 heart_disease_project
'''
git hub upload
git status
git add .
git commit -m "Initial commit"
git push -u origin main

# streamlit link
https://heart-disease-predictioon.streamlit.app/
