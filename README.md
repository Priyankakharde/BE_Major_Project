📊 Insightify – Smart Data Insights with Gemini AI 🧠
Welcome to Insightify, your AI-powered assistant for instantly visualizing and understanding your datasets! Built using Streamlit, Google Gemini API, and Plotly, this app transforms your CSV data into interactive and insightful visualizations – in seconds! 💡📈

🚀 Features
🔐 Secure Login System
Only authorized users can access the app using a simple username & password authentication.

📁 CSV Upload Support
Upload your dataset easily using the built-in uploader.

🧠 AI-Generated Insights with Gemini (Gemini 1.5 Flash)
Ask questions in natural language (e.g., "show correlation between age and income") and let Gemini generate:

📄 A brief insight summary

💻 Python visualization code using Streamlit & Plotly

📊 Interactive Visualizations
Uses Plotly for beautiful, zoomable, pan-enabled charts like:

Scatter plots

Histograms

Boxplots

Line graphs, and more!

💬 Chat Interface
Talk to your dataset! Each message adds to the context, creating a smart and seamless data conversation.

🔄 Session Memory
Keeps track of past user queries and model responses.

🔓 Logout Anytime
A sidebar logout button resets the session safely.

🛠️ How It Works
Login 🔑
Enter your username & password (stored securely in st.secrets)

Upload CSV 📄
Upload your dataset for analysis

Ask Questions 🤔
Type your query like:

“Show boxplot of income by gender”

AI Responds ⚡
Gemini provides:

Short analysis summary

Python + Streamlit + Plotly code

Visual Output 🖼️
The app runs the code and displays the chart right away

📦 Tech Stack
🐍 Python

🌐 Streamlit

📊 Plotly

🔐 HMAC for secure auth

🤖 Google Generative AI (Gemini 1.5 Flash)

🧼 Pandas, Seaborn, Matplotlib (for fallback support)

📌 Example Prompt
“Tell me a few lines about the dataset and show 4 different visualizations in a single layout.”

🧠 Gemini will analyze your data and return multiple interactive charts with explanations!

✅ Requirements
Python 3.8+

streamlit, pandas, plotly, google-generativeai, matplotlib, seaborn, scikit-learn

