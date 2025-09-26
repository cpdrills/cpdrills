# commands

python -m venv venv

uvicorn cf_api_server:app --host 127.0.0.1 --port 8081

pip install -r requirements.txt

cd cpdrills
python manage.py runserver
