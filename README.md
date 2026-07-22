# Energy-Supply-Chain
Project AEGIS is an AI-powered Decision Intelligence Platform designed to strengthen India's energy security by enabling proactive, data-driven decisions across the crude oil supply chain. Instead of reacting to geopolitical crises after they occur, AEGIS continuously monitors global events, shipping activity, commodity markets, weather conditions, and logistics networks to predict potential disruptions and recommend the best course of action before they escalate.

With India importing nearly 88% of its crude oil, even a single disruption—such as the closure of the Strait of Hormuz, geopolitical conflicts, economic sanctions, or severe weather—can significantly impact fuel prices, transportation, industrial production, and the national economy. Project AEGIS addresses this challenge by combining Artificial Intelligence, Machine Learning, Large Language Models (LLMs), and Decision Intelligence to provide actionable recommendations in real time.

🚀 Key Features
🌍 Real-Time Geopolitical Intelligence – Detects wars, sanctions, port closures, and political instability from global news and government advisories.
🚢 Shipping Intelligence – Tracks vessel movements, estimates delays, and identifies disruptions in maritime routes.
📈 Commodity Intelligence – Monitors Brent crude prices, currency exchange rates, and market trends to forecast procurement costs.
🧠 AI Risk Scoring Engine – Quantifies supply chain risks using multiple real-time data sources.
🔄 Route Optimization – Recommends the safest, fastest, and most cost-effective shipping routes using graph algorithms.
🤝 Supplier Recommendation Engine – Ranks suppliers based on price, availability, geopolitical stability, shipping time, and historical reliability.
⛽ Strategic Petroleum Reserve Management – Suggests optimal reserve utilization during emergencies.
📊 Executive Dashboard – Presents AI-driven insights, KPIs, alerts, and recommendations through an intuitive interface.



🏗️ System Architecture
News APIs + Government Advisories + Shipping Data + Weather + Oil Prices
                                │
                                ▼
                    Data Ingestion & Processing
                                │
                                ▼
                  NLP • LLM • RAG • Knowledge Graph
                                │
                                ▼
                Multi-Agent AI Decision Intelligence
      ┌──────────────┬──────────────┬──────────────┐
      │              │              │              │
 Geopolitical   Shipping AI   Commodity AI   Demand Forecasting
      │              │              │              │
      └──────────────┴──────────────┴──────────────┘
                                │
                                ▼
                Risk Scoring & Recommendation Engine
                                │
                                ▼
                   Executive Dashboard & AI Assistant


                   
🛠️ Technology Stack
Frontend
React.js
Tailwind CSS
Leaflet / Mapbox
Chart.js / Recharts
Backend
FastAPI
Python
PostgreSQL
Artificial Intelligence
Google Gemini / OpenAI GPT
LangChain
FAISS / ChromaDB (RAG)
Scikit-learn
Pandas
NetworkX
APIs & Data Sources
NewsAPI / GDELT
OpenWeather API
Brent Crude Price API
AIS Shipping Data
Government Advisories


📌 Workflow
Collect real-time news and logistics data.
Extract critical geopolitical events using LLMs.
Assess disruption risk through AI-based risk scoring.
Analyze shipping routes and supplier availability.
Forecast crude oil prices and demand.
Generate procurement, routing, and reserve recommendations.
Display insights through an executive dashboard.


🎯 Use Case

Scenario: The Strait of Hormuz is closed due to escalating geopolitical tensions.

Project AEGIS automatically:

Detects the disruption from global news.
Calculates the supply chain risk score.
Estimates inventory coverage.
Identifies alternative crude oil suppliers.
Optimizes shipping routes.
Recommends Strategic Petroleum Reserve utilization.
Predicts procurement cost increases.
Estimates the economic impact.
Generates executive recommendations within minutes.


💡 Impact
⏱️ Faster crisis response and decision-making.
💰 Reduced procurement and logistics costs.
📉 Lower economic losses from supply disruptions.
🛡️ Enhanced national energy resilience.
📊 AI-driven strategic planning for government agencies and energy companies.
🔮 Future Scope
Natural Gas Supply Chain Intelligence
Coal Logistics Optimization
Food Supply Chain Risk Prediction
Pharmaceutical Supply Chain Monitoring
National Disaster Logistics & Emergency Response
Carbon Emission-Aware Route Optimization


🤝 Contributing

Contributions are welcome! Feel free to fork the repository, submit issues, or create pull requests to improve Project AEGIS.

📜 License

This project is developed for educational, research, and hackathon purposes. Please review the repository license before commercial use.

Project AEGIS

Predict. Prepare. Protect.

Turning real-time geopolitical signals into intelligent, actionable decisions for a resilient energy future.
