# RetailPulse_AI
RetailPulse AI is an interactive AI-powered retail dashboard that uses machine learning and Gemini LLMs to deliver intelligent insights, predict churn, and forecast customer lifetime value.

---

## 🚀 Key Features

- 🤖 **AI Chat Agent** using Google Gemini to answer business questions like:
  - "Why are churn rates high in the South?"
  - "Top products by Lifetime Value?"
  - "Sales trend after Q3 product launch?"
- 📈 **Churn & Segmentation Analysis** with KMeans Clustering
- 🔮 **Lifetime Value Prediction** using Linear Regression
- 🌍 Region-wise insights for targeted marketing
- 📊 Interactive visualizations using Seaborn and Matplotlib
- 🧠 Explainable AI output embedded in UI
- 🔐 Modular design for enterprise extensibility

---

## 🧑‍💼 Industry Use Cases

| Sector             | Use Case |
|--------------------|----------|
| **Retail Chains**  | Reduce churn by identifying disengaged customers early |
| **E-commerce**     | Segment customers by behavior and optimize campaign ROI |
| **Consumer Brands**| Forecast Lifetime Value to adjust pricing and bundling |
| **CRM Teams**      | Identify peak times and preferred channels for engagement |

---

## 🗂️ Folder Structure

RetailPulse_AI/
├── backend/
│ ├── data_loader.py # Loads and preprocesses CSV data
│ ├── analytics.py # Churn prediction, segmentation, forecasting logic
│ ├── llm_agent.py # Gemini-based natural language query handler
│ ├── utils.py # API key loader, helper functions
├── frontend/
│ ├── styles.css # Custom CSS for styling Streamlit dashboard
├── models/
│ ├── kmeans_model.pkl # Pretrained KMeans model for segmentation
│ ├── regression_model.pkl # Pretrained regression model for LTV
├── data/
│ ├── retail_dataset.csv # Main retail customer transactional dataset
├── streamlit_app.py # Main Streamlit app
├── requirements.txt # Python dependencies
├── README.md # Project documentation





Sample Questions to Ask AI
"Show churn by region and suggest a retention strategy."
"List the top categories in summer season."
"Which segments have the highest predicted LTV?"
"Did the product launch impact customer engagement?"
"Analyze the time gap between purchases."


 Future Enhancement:
✨ Add sentiment analysis on product reviews
🔐 Role-based dashboards (Admin vs Executive)
📤 Email automation for churned customers
🌍 Integration with live retail APIs (Shopify, BigCommerce)


 Contact
Author: Venkata Surya Abburi
Email: suryanareshit@gmail.com
