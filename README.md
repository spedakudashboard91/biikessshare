"WELCOME TO BIKE RENTAL DICODING ANALYSIS"

Dora Leonny Giselle

This repository contains the final project for the "Belajar Analisis Data Dengan Python" course on Dicoding, focusing on analysis and dashboard creation using the bike sharing dataset. The project involves data wrangling, exploratory data analysis (EDA), and data visualization techniques. Additionally, a dashboard was created using Streamlit, accessible via the provided link. htttps:://biikessshare-nrlbnj2vcp6c4xvwhaz6hw.streamlit.app/

File Structures
├── Dashboard
│   ├── dashboard_bike.py
│   └── day.csv
├── Dataset
│   ├── day.csv
│   ├── hour.csv
|   └── Readme.txt
├── README.md
├── notebook1.ipynb
└── requirements.txt

Setup Environment - Anaconda

conda create --name main-ds python=3.11
conda activate main-ds
pip install -r requirements.txt

Setup Environment - Shell/Terminal

mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt

Run steamlit app

streamlit run dashboard.py
