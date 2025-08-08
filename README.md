# Travel-Planner-Agent
AI-Powered Travel Planner Agent helps users plan trips effortlessly by suggesting destinations, creating itineraries, estimating budgets, and providing live weather, currency, and event updates. Supports multilingual interaction and uses AI + real-time APIs for personalized, accurate travel planning worldwide.
# 🗺️ AI-Powered Travel Planner Agent

The **Travel Planner Agent** is an AI-powered assistant designed to make trip planning effortless and personalized.  
It can suggest destinations, create detailed itineraries, estimate budgets, and recommend transport, accommodation, and activities based on your preferences.  
With real-time data integration, you get up-to-date weather, currency exchange rates, and local event suggestions — all in one place.  
The agent also supports **multilingual interactions**, making it useful for travelers worldwide.

---

## ✨ Features

- 🏖 **Destination Suggestions** – Get travel ideas based on season, budget, and interests.
- 📅 **Itinerary Generation** – Day-by-day travel plans with activities and timings.
- 💰 **Budget Planning** – Estimated costs with clear breakdowns.
- 🌤 **Live Data Integration** – Weather forecasts, currency rates, and transport info.
- 🌍 **Multilingual Support** – Plan trips in your preferred language.
- 🧳 **Packing List Recommendations** – Based on destination weather and trip type.

---

## 🛠 Tech Stack

- **Frontend:** Streamlit / React (optional)
- **Backend:** Python, Flask / FastAPI
- **AI & NLP:** IBM watsonx.ai / GPT-based LLMs
- **APIs Used:**
  - Google Places API (for attractions & restaurants)
  - OpenWeather API (for weather forecasts)
  - ExchangeRate API (for currency conversion)
- **Deployment:** IBM Cloud / Docker

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/travel-planner-agent.git
cd travel-planner-agent
2️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Set Up API Keys
Create a .env file in the root directory and add:

ini
Copy
Edit
GOOGLE_API_KEY=your_google_places_api_key
OPENWEATHER_API_KEY=your_openweather_api_key
EXCHANGE_RATE_API_KEY=your_exchange_rate_api_key
WATSONX_API_KEY=your_watsonx_api_key
4️⃣ Run the App
bash
Copy
Edit
python app.py
or (if using Streamlit)

bash
Copy
Edit
streamlit run app.py
💡 Example Usage
User Query:

Plan a 5-day trip to Paris in October for two people with a budget of ₹1,00,000, including cultural activities and vegetarian food options.

Agent Output:

Suggested destinations & attractions

Day-by-day itinerary

Budget breakdown

Live weather updates

Packing recommendations

📌 Future Improvements
Integration with flight & hotel booking APIs

Offline trip planning mode

AI-based photo recommendations for destinations

Social sharing of itineraries
📌Screenshot's 
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/d9baaad3-f144-4179-a1f1-7e4c9db70364" />

📄 License
This project is licensed under the MIT License.

🤝 Contributing
Contributions are welcome!
Please fork the repo, create a feature branch, and submit a pull request.

Created with ❤️ by [Jaya Priya]
