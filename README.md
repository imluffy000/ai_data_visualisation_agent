# You can access this applicatiion using : https://datavisualize0.streamlit.app/

# 📊 AI Data Visualization Agent


An AI-powered data analysis and visualization application built with Streamlit, Together AI, and E2B Code Interpreter.

Upload a CSV dataset, ask questions in natural language, and let AI generate insights, charts, and visualizations automatically using Python.

---

## 🚀 Features

- 📁 Upload CSV datasets
- 🤖 Ask questions in natural language
- 📊 AI-generated visualizations
- 🐍 Automatic Python code generation and execution
- ☁️ Secure sandboxed execution with E2B
- 🧠 Multiple LLM support via Together AI
- 📈 Supports charts, tables, plots, and data analysis

---

## 🛠️ Tech Stack

- [Streamlit](https://streamlit.io/)
- [Together AI](https://www.together.ai/)
- [E2B Code Interpreter](https://e2b.dev/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Plotly](https://plotly.com/)
- [Pillow](https://python-pillow.org/)

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/ai-data-visualization-agent.git
cd ai-data-visualization-agent
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the App

Start the Streamlit application:

```bash
streamlit run app.py
```

---

## 🔑 Required API Keys

You need the following API keys:

### Together AI API Key
Get it from:
https://api.together.ai/signin

### E2B API Key
Get it from:
https://e2b.dev/docs/legacy/getting-started/api-key

Enter both keys in the Streamlit sidebar before analysis.

---

## 🧠 Supported AI Models

The application supports multiple models including:

- Meta-Llama 3.1 405B
- DeepSeek V3
- Qwen 2.5 7B
- Meta-Llama 3.3 70B

---

## 📁 Project Structure

```bash
ai-data-visualization-agent/
│
├── app.py
├── requirements.txt
├── README.md
└── assets/
```

---

## ⚙️ How It Works

1. Upload a CSV dataset
2. Ask a question about your data
3. Together AI generates Python analysis code
4. E2B sandbox securely executes the code
5. Results and visualizations are displayed instantly

---

## 📸 Example Queries

- Compare average sales across regions
- Show revenue trends over time
- Visualize correlations between columns
- Find top-performing categories
- Generate bar charts and scatter plots
- Analyze missing values

---

## 📊 Supported Outputs

- DataFrames
- Bar Charts
- Line Charts
- Scatter Plots
- Histograms
- Heatmaps
- Statistical Analysis
- Custom Python Outputs

---

## 🌍 Deployment Options

You can deploy the app on:

- Streamlit Community Cloud
- Render
- Railway
- Hugging Face Spaces
- AWS / GCP / Azure

---

## ⚠️ Limitations

- Currently supports CSV files only
- Large datasets may take longer to process
- AI-generated code may occasionally fail
- Requires active API keys

---

## 🔮 Future Improvements

- Excel and JSON support
- Dashboard generation
- AI-generated reports
- Downloadable charts
- Multi-file analysis
- SQL database support
- Chat history
- Authentication system

---

## 🤝 Contributing

Contributions are welcome!

Feel free to fork the project and submit pull requests.

---

## 📜 License

MIT License

---

## 💡 Author

Built with ❤️ using AI, Streamlit, Together AI, and E2B Sandbox.
