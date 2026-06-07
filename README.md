# Echo-AI
# 1. Enter the folder
cd echo-python

# 2. Create virtual environment
python -m venv venv

# 3. Activate it
source venv/bin/activate        # Mac/Linux
# venv\Scripts\activate         # Windows

# 4. Install packages
pip install -r requirements.txt

# 5. Set up .env and start
cp .env.example .env
# → open .env, fill in ANTHROPIC_API_KEY, MONGODB_URI, JWT_SECRET_KEY
python server.py
