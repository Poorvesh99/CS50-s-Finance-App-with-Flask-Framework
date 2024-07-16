# CS50-s-Finance-App-with-Flask-Framework

## Description
The Stock Portfolio Manager is a web application built with Flask that allows users to manage their stock portfolio. Users can register, log in, buy and sell stocks, and view their current holdings and cash balance. The application uses the Yahoo Finance API to fetch current stock prices.

## Features
- User Registration and Login
- Buy and Sell Stocks
- View Portfolio with Real-Time Stock Prices
- Track Cash Balance
- History of Transactions

## Installation

1. **Clone the repository:**
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
2. **Set up a virtual environment:**
   python3 -m venv venv
   source venv/bin/activate
3. **Install the required packages:**
    python3 -m venv venv
    source venv/bin/activate
4.** Set up the database:**
   export FLASK_APP=app.py
   flask db init
   flask db migrate -m "Initial migration."
   flask db upgrade
5.**Run the application:**
   flask run


