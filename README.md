
# SD Invoice Python V1

Python Flask + SQLite version of SD Invoice.

## Login
Super Admin:
- User ID: superadmin
- Password: admin123

Demo Client:
- Email: demo@sdinvoice.com
- User ID: admin
- Password: 1234

## Run locally
```bash
pip install -r requirements.txt
python app.py
```

Open:
http://localhost:5000

## Render deploy
Build Command:
```bash
pip install -r requirements.txt
```

Start Command:
```bash
gunicorn app:app
```
