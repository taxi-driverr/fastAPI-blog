Project Setup Steps in your Local Environment:

Step 1: Set up a new Virtual Environment

First, they navigate into the project folder and create a fresh, clean virtual environment:
bash
```
python -m venv .venv
source .venv/Scripts/activate
```

Step 2: Run the Install Command

Once their virtual environment is active, they run this command to read your recipe list and download everything automatically:
bash
```
pip install -r requirements.txt
```
Step 3: Spin up the Project
```
fastapi dev main.py
```
