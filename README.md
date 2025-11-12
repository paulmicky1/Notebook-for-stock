# 📈 Notebook for Stock Analysis

A comprehensive collection of Jupyter notebooks for analyzing various stocks, cryptocurrencies, and financial instruments. This project provides data-driven insights through visualizations, statistical analysis, and presentation materials.

## 🌟 Features

- **Multiple Stock Analyses**: In-depth analysis of major stocks and indices
- **Data Visualization**: Interactive charts and graphs using Matplotlib and Seaborn
- **Statistical Analysis**: Comprehensive statistical metrics and insights
- **Presentation Materials**: PowerPoint presentations for each analysis
- **Web Scraping Capabilities**: Tools for gathering financial data
- **Organized Datasets**: Structured data storage for reproducibility

## 📊 Analyses Included

### Stock Market Indices
- **CAC40 Stock Analysis** (`CAC40_stock_analysis.ipynb`)
  - Analysis of French stock market index CAC40
  - Historical data from 2010-2023
  - Multiple datasets including preprocessed data

### Individual Stocks
- **Nike Stock Analysis** (`nike_stock_analysis.ipynb`)
  - Historical performance analysis
  - Trend identification and forecasting

- **NVIDIA Stock Analysis** (`nvidia_stock_analysis.ipynb`)
  - Comprehensive NVIDIA stock history
  - Performance metrics and visualizations

- **Walt Disney Company Stock Analysis** (`walt_disney_stock_analysis.ipynb`)
  - Disney stock performance analysis
  - Historical trend analysis

### Commodities & Crypto
- **Gold Price Analysis** (`gold_stock_analysis.ipynb`)
  - Gold price trends and analysis
  - Historical price data visualization

- **Cryptocurrency Analysis** (`crypto_stock_analysis.ipynb`)
  - Cryptocurrency market analysis
  - Multiple crypto assets comparison

### Additional Analysis
- **Random Stock Market Analysis** (`random_stock_market_analysis.ipynb`)
  - General stock market trends
  - Broader market analysis

## 🚀 Getting Started

### Prerequisites

- Python >= 3.14
- [uv](https://github.com/astral-sh/uv) package manager (recommended) or pip

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Notebook-for-stock
   ```

2. **Install dependencies using uv** (recommended)
   ```bash
   uv sync
   ```

   Or using pip:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Notebooks

1. **Launch JupyterLab**
   ```bash
   jupyter lab
   ```

2. **Open any notebook** from the file browser and run the cells sequentially

3. **View presentations** - Each analysis has a corresponding PowerPoint presentation in the root directory

## 📁 Project Structure

```
Notebook-for-stock/
├── datasets/                          # Data storage
│   ├── cac40 stock/                  # CAC40 stock data
│   ├── crypto stock/                 # Cryptocurrency data
│   ├── gold stock/                   # Gold price data
│   ├── nike stock/                   # Nike stock data
│   ├── nvidia_stock/                 # NVIDIA stock data
│   ├── random_Stock_market/          # General stock market data
│   └── walt_disney_company stock/    # Disney stock data
├── CAC40_stock_analysis.ipynb        # CAC40 analysis notebook
├── crypto_stock_analysis.ipynb       # Crypto analysis notebook
├── gold_stock_analysis.ipynb         # Gold analysis notebook
├── nike_stock_analysis.ipynb         # Nike analysis notebook
├── nvidia_stock_analysis.ipynb       # NVIDIA analysis notebook
├── random_stock_market_analysis.ipynb # General market analysis
├── walt_disney_stock_analysis.ipynb  # Disney analysis notebook
├── *.pptx                            # Presentation files
├── main.py                           # Main entry point
├── pyproject.toml                    # Project configuration
└── README.md                         # This file
```

## 🛠️ Technologies & Libraries

### Data Analysis & Visualization
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** - Data visualization
- **seaborn** - Statistical data visualization
- **scikit-learn** - Machine learning and statistical modeling

### Web Scraping
- **scrapy** - Web scraping framework
- **selenium** - Browser automation
- **beautifulsoup4** - HTML/XML parsing
- **scrapy-playwright** - Modern web scraping

### Development Tools
- **jupyter** - Interactive notebook environment
- **jupyterlab** - Advanced Jupyter interface
- **ipykernel** - Jupyter kernel

### Big Data
- **pyspark** - Large-scale data processing
- **findspark** - Spark integration

### Presentation
- **python-pptx** - PowerPoint generation

## 📈 Usage Examples

### Loading and Analyzing Stock Data

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Load stock data
df = pd.read_csv('datasets/nike stock/Nike_historical_data.csv')

# Basic analysis
print(df.describe())
print(df.info())

# Visualization
plt.figure(figsize=(12, 6))
plt.plot(df['Date'], df['Close'])
plt.title('Nike Stock Price History')
plt.xlabel('Date')
plt.ylabel('Price')
plt.show()
```

## 📊 Data Sources

Each dataset in the `datasets/` folder contains historical financial data for the respective stock or asset. The data includes:
- Opening prices
- Closing prices
- High/Low prices
- Trading volume
- Date information

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License
Copyright (c) 2025 PAUL MICKY D COSTA
```

## 👤 Author

**PAUL MICKY D COSTA**

## 📝 Notes

- Ensure all datasets are present in the `datasets/` folder before running analyses
- Each notebook is self-contained and can be run independently
- PowerPoint presentations provide summary insights for each analysis
- The project uses modern Python (3.14+) features and dependencies

## 🔮 Future Enhancements

- [ ] Real-time data fetching
- [ ] Automated report generation
- [ ] Machine learning predictions
- [ ] Interactive dashboards
- [ ] API integration for live data
- [ ] Additional stock analyses

---

**Happy Analyzing! 📊✨**

