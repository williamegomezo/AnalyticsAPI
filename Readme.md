Create virtual environment:
`python3 -m venv ~/.virtualenvs/analytics`

Activate environment:
`source ~/.virtualenvs/analytics/bin/activate`

Install python packages:
`pip install -r requirements.txt`

Download a client secrets and place in project folder:
`./client_secrets.json`

Copy .env template and set in the file, the View ID value:
`cp .env.template .env`

Run:
`python fetch_api.py`