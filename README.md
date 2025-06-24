# Road-Pavement-Compaction-Monitoring-Dashboard
This dashboard is a compaction monitoring dashboard that gives operators visualizations and analysis about the paving and compaction process.
This project is an interactive Dash-based web dashboard for analyzing road construction compaction data using temperature readings, GPS logs, and cooling curve profiles. It allows users to upload custom datasets, visualize spatial and temporal patterns, and perform cooling curve regression analysis to support construction quality assessment.

🚀 Features
📤 Upload temperature, GPS, and cooling curve datasets (CSV format)

📊 Automatically generate interactive plots:

    TCP and CCP maps with speed overlays
    
    Cooling curve regression fits (polynomial & exponential)
    
    Statistical Control charts for process monitoring


    
🗂️ Dashboard Features:
     Switch between projects and locations using tabs
     Dropdowns to choose the type of plot.
     interactive maps.
     toolbars to do actions on maps.
    (Optional) Integrate weather data for environmental context at compaction time
     Built with Python, Plotly Dash, and Pandas
     

📁 Project Structure
bash
Copy
Edit
project-root/
│
├── app.py                  # Main Dash app file
└── README.md              # This file


📦 Requirements
  Python 3.8+
  
    Dash
    
    Plotly
    
    Pandas
    
    NumPy
    

📂Install dependencies using:
    bash
    Copy
    Edit
    pip install -r requirements.txt
    Data Format (CSV Uploads)


🧪 Running the App
To start the dashboard locally:
    bash
    Copy
    Edit
    python app.py
    Then open your browser at:
    http://127.0.0.1:8081( or any other port number you use locally)
    

📈 Plot Types
    Cooling Curve Fit: Choose between polynomial or exponential regression
    
    TCP Map: Visualizes temperature and speed overlay on a geospatial map

    CCP map: defining nu,ber of passes roller takes for compaction.
    
    Control Charts: For tracking temperature consistency over time.
    

🛠️ Development Notes
    You can extend the app to support more locations, additional plot types, or use weather APIs like Open-Meteo or Met.no for real-time data.
    
    The app uses dcc.Store to hold uploaded datasets and ensure interactive callbacks work seamlessly.
