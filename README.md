# Financial News Sentiment and Stock Market Analysis

## Overview 
This project focuses on analyzing a large corpus of financial news data to identify correlations between news sentiment and stock market movements. The project enhances skills in **Data Engineering (DE)**, **Financial Analytics (FA)**, and **Machine Learning Engineering (MLE)**.

The primary objective is to demonstrate how news sentiment influences stock price changes, ultimately offering actionable insights for predictive investment strategies.

---

## **Business Objective**  
The project aligns with **Nova Financial Solutions'** goal of improving financial forecasting accuracy and operational efficiency. The analysis is two-fold:  
1. **Sentiment Analysis**: Perform NLP-based sentiment analysis on financial news headlines.  
2. **Correlation Analysis**: Establish statistical relationships between sentiment scores and stock price movements to develop predictive insights.  

---

## **Tasks and Deliverables**

### **Task 1: Git and Exploratory Data Analysis (EDA)**  
**Description**: Setting up the environment, version control, and conducting data exploration.  

**Key Activities**:  
- Environment setup and GitHub repository initialization.  
- Perform EDA to uncover insights.  

**Deliverables**:  
- Basic statistics (e.g., headline length, article counts by publisher).  
- Time-series trends (e.g., publishing frequency patterns).  
- Sentiment analysis and topic modeling.  

**KPIs**:  
- Clean and reproducible setup.  
- Comprehensive EDA using statistical plots and distributions.  

**Folder Structure**:  
```plaintext
├── .vscode/
│   └── settings.json
├── .github/
│   └── workflows/
│       ├── unittests.yml
├── .gitignore
├── requirements.txt
├── README.md
├── src/
│   ├── __init__.py
├── notebooks/
│   └── eda_notebook.ipynb
├── tests/
│   └── test_analysis.py
└── scripts/
    └── data_preparation.py
```

---

### **Task 2: Quantitative Analysis with PyNance and TA-Lib**  
**Description**: Conduct technical analysis and visualize stock performance using finance libraries.  

**Key Activities**:  
- Load stock price data (Open, High, Low, Close, Volume).  
- Apply technical indicators (e.g., Moving Averages, RSI, MACD).  
- Use **PyNance** for financial metrics.  

**Deliverables**:  
- Stock indicator visualizations.  
- Insights from technical analysis.  

**KPIs**:  
- Accurate calculation of financial indicators.  
- Clear, insightful visualizations.  

**Tools Used**:  
- **TA-Lib**  
- **PyNance**  
- **Matplotlib/Seaborn**  

---

### **Task 3: Correlation Between News Sentiment and Stock Movements**  
**Description**: Analyze the relationship between news sentiment and stock price changes.  

**Key Activities**:  
- **Sentiment Analysis**: Quantify sentiment scores using libraries like `TextBlob` or `NLTK`.  
- **Daily Stock Returns**: Calculate percentage changes in stock closing prices.  
- **Correlation Analysis**: Align news and stock data by dates, compute correlation coefficients (e.g., Pearson).  

**Deliverables**:  
- Sentiment scores and stock return calculations.  
- Correlation analysis results.  

**KPIs**:  
- Accuracy of sentiment analysis.  
- Strength and interpretation of correlation findings.  

---

## **Dataset Overview**  
The **Financial News and Stock Price Integration Dataset (FNSPID)** is used for this analysis:  

| Field       | Description                                                                 |
|-------------|-----------------------------------------------------------------------------|
| **headline**| Title of the news article, often highlighting key financial events.         |
| **url**     | Link to the full article.                                                   |
| **publisher**| The source/author of the article.                                          |
| **date**    | Publication date and time (UTC-4 timezone).                                 |
| **stock**   | Stock ticker symbol (e.g., AAPL for Apple).                                 |

---

## **Technologies Used**  
The project leverages the following tools and libraries:  

- **Programming Language**: Python  
- **Version Control**: Git, GitHub  
- **Libraries**:  
  - **NLP**: `NLTK`, `TextBlob`, `spaCy`  
  - **EDA**: `Pandas`, `Matplotlib`, `Seaborn`  
  - **Finance**: `TA-Lib`, `PyNance`  
  - **Correlation**: `SciPy`, `NumPy`  
- **Environment**: Jupyter Notebooks, VSCode  

---

## **Installation and Setup**  
Follow these steps to set up the project on your local machine:  

1. Clone the repository:  
   ```bash
   git clone https://github.com/Tewodros-agegnehu/stock-market-data-analysis.git
   cd stock-market-data-analysis
   ```  

2. Create a virtual environment and install dependencies:  
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```  

3. Run notebooks and scripts:  
   - Use `notebooks/eda_notebook.ipynb` for EDA tasks.  
   - Run scripts from the `scripts` folder for data preparation and analysis.  

---

## **Project Workflow**  
1. **Branching Strategy**:  
   - `main`: Production-ready code.  
   - `task-1`, `task-2`, `task-3`: Feature branches for development.  

2. **Workflow**:  
   - Create new branches for tasks.  
   - Commit changes frequently with descriptive messages.  
   - Merge feature branches using Pull Requests (PRs).  

Example:  
```bash
git checkout -b task-1
# Commit changes
git add .
git commit -m "Added EDA for publisher analysis"
git push origin task-1
```

---

## **Results and Insights**  
The project delivers:  
- Sentiment analysis results of financial news headlines.  
- Stock performance trends derived from technical indicators.  
- Correlation coefficients linking sentiment scores to stock movements.  

These insights help demonstrate the predictive value of financial news sentiment in stock market forecasting.

---

## **Future Improvements**  
- Incorporate deep learning models (e.g., LSTM) for better sentiment prediction.  
- Add intraday stock price data for more granular analysis.  
- Develop a dashboard to visualize real-time sentiment trends and stock predictions.  

---

## **Contributing**  
Contributions are welcome! If you'd like to improve or add features to this project:  
1. Fork the repository.  
2. Create a new branch for your feature.  
3. Submit a Pull Request (PR).  

---

## **License**  
This project is licensed under the MIT License.  


