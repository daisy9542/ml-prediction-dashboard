# ML Prediction Dashboard

A comprehensive machine learning prediction dashboard built with Streamlit. This application provides advanced data analysis, model training, and prediction capabilities with an intuitive web interface.

## Features

- 📊 **Data Analysis**: Upload CSV files and perform comprehensive data analysis
- 🤖 **ML Models**: Support for Random Forest, LightGBM, and XGBoost
- 📈 **Visualizations**: Interactive charts and plots using Plotly and Altair
- 🔍 **SHAP Analysis**: Model interpretability with SHAP values
- 📧 **Email Reports**: Send prediction reports via email
- 💾 **Model Persistence**: Save and load trained models
- 🗄️ **Database Support**: SQLAlchemy integration for data storage

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/ml-prediction-dashboard.git
cd ml-prediction-dashboard
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
streamlit run app.py
```

## Usage

1. Open your browser and navigate to `http://localhost:8501`
2. Upload your CSV dataset
3. Configure model parameters
4. Train and evaluate models
5. Make predictions and analyze results

## Deployment

### Streamlit Cloud
1. Push this repository to GitHub
2. Visit [share.streamlit.io](https://share.streamlit.io)
3. Connect your GitHub repository
4. Deploy with one click!

### Local Development
```bash
streamlit run app.py
```

## Requirements

- Python 3.8+
- See `requirements.txt` for package dependencies

## License

MIT License