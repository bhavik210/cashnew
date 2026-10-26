Bhavik Desk (Hisab) - Streamlit Cloud deployment

1. Upload both main.py and requirements.txt to the same root folder in your GitHub repository.
2. Confirm Streamlit Cloud is configured to use this repository and the main.py file.
3. Commit the changes and reboot/redeploy the app.
4. Streamlit Cloud installs packages listed in requirements.txt.

Note: SQLAlchemy is required because main.py imports create_engine and text from sqlalchemy.
