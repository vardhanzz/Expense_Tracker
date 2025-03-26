# Expense_Tracker
Expense Tracker App 

Overview 

The Expense Tracker App is a Flask-based web application that helps users manage their expenses and income efficiently.  It provides a dashboard with daily spending analysis using graphs and an AI Insights feature powered by Llama 3 via Ollama.  This AI feature evaluates savings and spending patterns, offering insightful financial suggestions.

Features 

Add Expenses & Income: Manually enter transactions categorized under food, clothes, transportation, and more. 

Daily Graphical Analysis: Visual representation of expenses and income trends on the dashboard. 

AI Insights: Analyze financial data with Llama 3 through Ollama to get spending summaries and suggestions. 

Installation 

Prerequisites 

Ensure you have Python installed on your system. Then, install the necessary packages using pip: 

pip install flask
pip install ollama
pip install SQLAlchemy
pip install wtforms

Running the Application 

Once the dependencies are installed, run the application with: 

python run.py

Then open your browser and visit: 

http://127.0.0.1:5000/



AI Insights Feature 

The AI Insights button fetches all financial data and evaluates savings versus spending trends using Llama 3 integrated with Ollama.  This feature provides: 

Monthly spending summaries 

Suggestions for better money management 

Future investment recommendations 




License 

This project is open-source and free to use. 

Contribution 

Feel free to contribute by submitting a pull request or reporting issues. 
