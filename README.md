🚗 Vehicle Registration Dashboard

This is a dark-themed, interactive dashboard made with Streamlit that shows trends in vehicle registrations in India.
The goal was to take Vahan Dashboard public data, process it, and present it in a clean, easy-to-read way for investors.

🎯 What This Project Does

Lets you see how many vehicles were registered in India — broken down by:

Vehicle Type: 2-Wheelers, 3-Wheelers, 4-Wheelers

Manufacturer

Shows Year-over-Year (YoY) and Quarter-over-Quarter (QoQ) growth

Gives an investor-friendly view with charts, KPIs, and filters

Makes it super easy to spot trends like which category is growing fastest

✨ Main Features

Dark mode and mobile-friendly design

Choose date range and filter by vehicle type or manufacturer

KPI cards showing % growth (YoY & QoQ)

Interactive charts with Plotly (line, bar, and growth rate graphs)

Download data as CSV

Button to refresh and pull latest data

📊 Data Details

Source: Vahan Dashboard (publicly available data)

If live scraping fails, the dashboard loads from a sample CSV included in the repo

Missing values are treated as 0 when calculating growth

🛠 Tools Used

Python 3.10+

Streamlit for the UI

Pandas for data cleaning & processing

Plotly for charts

Requests + BeautifulSoup for scraping

⚡ How to Run

Clone the repo

git clone https://github.com/yourusername/vehicle-dashboard.git
cd vehicle-dashboard


Set up virtual environment

python -m venv venv
venv\Scripts\activate      # Windows
source venv/bin/activate   # Mac/Linux


Install requirements

pip install -r requirements.txt


Run the app

streamlit run app.py

📈 Some Insights I Found

4-Wheelers grew by 15% YoY — demand for passenger cars is up.

Electric 2-Wheelers are booming, with 40% YoY growth — EV market is hot.

3-Wheelers saw a small drop QoQ, possibly due to competition from ride-sharing apps.

📹 Demo Video

🎥 Video walkthrough link → [Insert your YouTube/Drive link here]

🚀 Next Steps (If I Continue This)

Add state/city level filters

Forecast future registrations using ML models

Include real-time industry news sentiment

Add Hindi/English language toggle
