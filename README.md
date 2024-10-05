# 💸 **AI Financial Assistant**

---

## 📝 **Project Overview**

This project provides an **AI-powered financial assistant** that simplifies access to financial resources and predicts asset prices. It uses a **Streamlit**-based chatbot interface and integrates machine learning models for making financial predictions, offering users a streamlined way to get information on various financial instruments.

---

## 🎯 **Objectives**

- 💬 Create an intuitive chatbot for financial assistance.
- 📊 Provide users with asset price predictions, powered by machine learning models.
- 🛠️ Facilitate access to financial data for stocks, cryptocurrencies, and commodities.
- 📈 Build prediction dashboards for real-time financial insights.

---

## 📂 **Dataset**

The financial datasets used in this project are sourced from **Yahoo Finance** for assets like stocks (e.g., AAPL, AMZN), cryptocurrencies (e.g., BTC-USD, ETH-USD), and commodities (e.g., Gold, Natural Gas). Additionally, the **option chains** dataset is sourced from **Kaggle**.

⚠️ **Note:** If you wish to experiment with our results, you can simply run the app. The predictions can be visualized using the CSV files already included in the `docs` folder. However, if you want to test on different data, you will need to manually download the financial data from **Yahoo Finance** and the option chains data from **Kaggle**.

---

## 📊 **Model Implementation**

- **Chatbot**: Built using **Streamlit** and integrated with **Langchain** and **OpenAI** for natural language processing.
- **Prediction Models**: The project includes models for predicting asset prices, implemented in the `fingpt` folder.
- **Dashboards**: Streamlit dashboards for visualizing financial data and predictions, accessible through the `pages` folder.

---

## 🔐 **API Key Setup**

To use the chatbot feature, you will need to include a **`.env`** file in the project directory. This file should contain your **OpenAI API key**. Without this, the chatbot will not work.

1. Create a file named **`.env`** in the root of your project.
2. Inside the `.env` file, add the following line:
   ```
   OPENAI_API_KEY=your_openai_api_key_here
   ```

Replace `your_openai_api_key_here` with your actual OpenAI API key.

---

## 🔧 **Technologies Used**

- **Python**: Main programming language.
- **Streamlit**: For building interactive dashboards and chatbot interfaces.
- **Langchain & OpenAI**: For natural language processing in the chatbot.
- **Pandas**: For data manipulation.
- **Scikit-learn**: For implementing prediction models.
- **Matplotlib**: For visualizing data and predictions.

---

## 📂 **Installation**

1. Clone the repository:

   ```bash
   git clone https://github.com/MelikBLK/AI-Financial-Assistant.git
   ```

2. Install the required Python libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. To experiment with our results, run the app directly using the preloaded CSV files in the `docs` folder:

   ```bash
   streamlit run chatbot.py
   ```

4. If you want to experiment with your own data, manually download the datasets from **Yahoo Finance** and **Kaggle**.

---

## 📫 **Contact**

Feel free to reach out for any questions or suggestions:

- [LinkedIn](https://www.linkedin.com/in/melik-belkhiria)
- [Email](mailto:belkhiria.melik02@gmail.com)
