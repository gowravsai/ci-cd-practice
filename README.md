# ci-cd-practice

A tiny Flask API used to practice Git and CI/CD.

## Setup (VS Code terminal, inside this folder)

Create the virtual environment:

    python -m venv venv

Activate it:

- Windows PowerShell: `venv\Scripts\Activate.ps1`
- Windows cmd: `venv\Scripts\activate`
- Mac/Linux: `source venv/bin/activate`

Install dependencies:

    pip install -r requirements.txt

## Run checks

    pytest
    flake8 app.py test_app.py

## Run the app

    flask --app app run

Then open http://127.0.0.1:5000/health
