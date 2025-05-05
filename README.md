# ChartAI

ChartAI is an AI-powered analytics tool designed to help researchers, analysts, and businesses gain insights from structured data files like Excel, CSV, and TXT. It supports academic data analysis, business insights, and a wide range of visualizations.

## Features

- Upload Excel, CSV, or TXT files
- Descriptive and inferential statistics
- Regression and time series analysis (using Prophet)
- Sentiment analysis for text fields (e.g., feedback)
- Anomaly detection with Isolation Forest
- Multiple visualization options: Line, Bar, Box, Histogram, Heatmap
- Dashboard interface powered by Streamlit
- SEM and triangulation analysis (coming soon)

## How to Run

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the Streamlit app:
```bash
streamlit run app.py
```

3. Use the included `sample_data.csv` to test features immediately.

## Deployment

You can deploy ChartAI on [Streamlit Cloud](https://streamlit.io/cloud) by uploading this project folder to a GitHub repository and connecting it to Streamlit.

## License

MIT License
