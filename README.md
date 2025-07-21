🌦️ WeatherApp AI — Real-Time Forecasting Dashboard
A sleek Streamlit web app that delivers real-time weather data, interactive heatmaps, and AI-powered 7-day temperature forecasts — all based on any city input by the user.

🚀 Features
🌍 City-Based Input: Type in any city and get instant weather updates

🔁 Real-Time Data: Powered by OpenWeatherMap API for live readings

🧠 AI Forecasting: Custom-trained ML model to predict 7-day temperature trends

🗺️ Dynamic Heatmap: Interactive map of temperature intensity (Folium + OpenStreetMap)

📊 Weather Metrics: Humidity, wind speed, pressure, visibility & more

🎨 Modern UI: Clean layout, dark mode support, responsive charts

📷 Demo Preview

🔧 Tech Stack
Frontend: Streamlit

Data: OpenWeatherMap API

Mapping: Folium

Machine Learning: sklearn-trained regression model

Backend Logic: Python, Pandas, Numpy

📈 AI Model
The app uses a custom-trained machine learning model to forecast future temperatures based on:

Day & month

Current temperature

Humidity

Wind speed

Visibility

Pressure

You can easily swap out the model or retrain it on your own dataset for more accuracy.

🛠️ Installation
Clone the repo

bash
Copy
Edit
git clone https://github.com/yourusername/weatherapp-ai.git
cd weatherapp-ai
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the app

bash
Copy
Edit
streamlit run app.py
🔑 API Key
To use live weather data, sign up at OpenWeatherMap and add your API key to your .env or directly inside the script:

python
Copy
Edit
API_KEY = "your_api_key_here"
📂 File Structure
bash
Copy
Edit
weatherapp/
│
├── app.py                  # Main Streamlit app
├── model.pkl               # Pretrained forecasting model
├── requirements.txt        # Python dependencies
├── README.md               # Project overview
└── screenshot.png          # Sample forecast chart
💡 Future Ideas
Weather-based clothing suggestions

Icon-based conditions (☀️ 🌧️ 🌩️)

User location auto-detect

Hourly forecast support

🧠 Author
Built with ❤️ and a curious mind by Nihat
If you like the project or want to contribute — feel free to open a pull request or reach out.
