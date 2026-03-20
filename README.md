# sales-intelligence-ai-dashboard
An end-to-end data and AI pipeline that analyzes enterprise sales data, 
forecasts revenue using Machine Learning, and answers business questions 
in plain English using a Large Language Model.

#working of the project
Analyzes 2823 rows of real enterprise sales data
1. Identifies key business insights across products, countries and time
2. Predicts future sales with 88% accuracy using Random Forest
3. Answers business questions in plain English using an LLM (Groq API)

#Technologies used:
Python 
pandas and numpy (data cleaning and analysis)
SQLite & SQL (database layer)
Scikit-learn (machine learning)
Groq LLM API (GenAI analyst)
 jupyter Notebook
 
#Project Structure
1. `sales_intelligence_dashboard.ipynb` - Main notebook with all code
2.`sales_intelligence.db` - SQLite database
3.`sales_dashboard.png` - Analytics dashboard chart
4.`feature_importance.png` - ML feature importance chart

#How to run
1. Clone this repository
2. Install dependencies
3. pip install pandas numpy matplotlib scikit-learn groq jupyter
4. Add your Groq API key in Cell 8
5. Run all cells in order
