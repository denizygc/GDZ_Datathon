# ⚡ GDZ Datathon Energy Forecasting Project

This project was originally developed as part of the **GDZ Elektrik Datathon**, a data science competition focused on forecasting **energy distribution** across network centers in İzmir and Manisa, Turkey. The goal is now to evolve the original model exploration into a functional and interactive **web application**.

---

## 🏁 Competition Overview

> Gdz Elektrik, serving the provinces of İzmir and Manisa, launched its second **Datathon** event aiming to drive innovation in energy forecasting using modern data science techniques and external datasets.

### Challenge Goal

Participants were tasked with developing a **forecasting approach** for predicting the energy distributed by network centers. Realization data (actuals) were provided to evaluate the performance of the models.

Additional external datasets could be integrated to improve performance, though some data limitations were in place due to company policy.

---

## Project Redesign & Web App Goals

After the competition, this project has been **redesigned and refactored** with the following goals in mind:

- Build a **modular and maintainable ML pipeline**
- Try both **LSTM ** and **scikit-learn models** 
- Develop a lightweight **Flask-based web app** to interactively explore predictions
- Follow SOLID principles and best practices for code structure

---

## Project Structure

GDZ_DATATHON/
├── notebooks/               # Exploratory notebooks and EDA
├── src/
│ ├── data/                  # Data loading & preparation scripts
│ ├── model/                 # Model definitions (LSTM, sklearn)
│ ├── preprocessing/         # Feature engineering and cleaning
│ ├── utils/                 # Helpers (e.g. logger, metrics)
│ ├── config.py              # Centralized configurations
│ └── main.py                # Entry point script
├── test/                    # Unit tests for core functions
├── venv-gdz/                # Virtual environment (excluded via .gitignore)
├── .gitignore               # Git exclusions
└── README.md                # Project description and goals