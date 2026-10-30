# Smart India Hackathon Workshop
# Date:30-10-2026
## Register Number:26009701
## Name:KAMALINI V
## Problem Title
SIH 25010: Smart Crop Advisory System for Small and Marginal Farmers
## Problem Description
A majority of small and marginal farmers in India rely on traditional knowledge, local shopkeepers, or guesswork for crop selection, pest control, and fertilizer use. They lack access to personalized, real-time advisory services that account for soil type, weather conditions, and crop history. This often leads to poor yield, excessive input costs, and environmental degradation due to overuse of chemicals. Language barriers, low digital literacy, and absence of localized tools further limit their access to modern agri-tech resources.

Impact / Why this problem needs to be solved

Helping small farmers make informed decisions can significantly increase productivity, reduce costs, and improve livelihoods. It also contributes to sustainable farming practices, food security, and environmental conservation. A smart advisory solution can empower farmers with scientific insights in their native language and reduce dependency on unreliable third-party advice.

Expected Outcomes

• A multilingual, AI-based mobile app or chatbot that provides real-time, location-specific crop advisory.
• Soil health recommendations and fertilizer guidance.
• Weather-based alerts and predictive insights.
• Pest/disease detection via image uploads.
• Market price tracking.
• Voice support for low-literate users.
• Feedback and usage data collection for continuous improvement.

Relevant Stakeholders / Beneficiaries

• Small and marginal farmers
• Agricultural extension officers
• Government agriculture departments
• NGOs and cooperatives
• Agri-tech startups

Supporting Data

• 86% of Indian farmers are small or marginal (NABARD Report, 2022).
• Studies show ICT-based advisories can increase crop yield by 20–30%.

## Problem Creater's Organization
Government of Punjab

## Theme
Agriculture, FoodTech & Rural Development

## Proposed Solution
A mobile-first AI platform for small/marginal farmers, providing personalized crop recommendations, pest alerts, and yield forecasts via app, SMS, or voice in local languages.

## Technical Approach
 Modular stack with React Native frontend (mobile app/SMS via Twilio), Node.js/Flask backend, MongoDB/PostgreSQL data layer, and AWS/Google Cloud for hosting. Offline sync using IndexedDB/Service Workers.
Data Pipeline: Ingest farmer inputs (GPS, soil metrics) + external APIs (OpenWeatherMap for $r, t$; ISRO Bhuvan for imagery). ETL with Apache Airflow for cleaning and feature engineering (e.g., NPK levels, rainfall $r > 500$ mm).
## Feasibility and Viability
Supervised learning (e.g., Random Forest or XGBoost) for crop recommendation. For instance, train on datasets like historical yield data from FAO or national agricultural boards.
## Impact and Benefits
A multi-criteria decision model (e.g., Analytic Hierarchy Process) combines factors like climate match, soil compatibility, and economic viability.


## Research and References
A multi-criteria decision model (e.g., Analytic Hierarchy Process) combines factors like climate match, soil compatibility, and economic viability.
