# 🌍 World Happiness Analysis (2015-2024)

A comprehensive data science project analyzing the World Happiness Report dataset to uncover insights about global well-being and the factors that contribute to national happiness levels.

## 📊 Project Overview

This project explores a decade of happiness data from 150+ countries, investigating relationships between happiness scores and various socioeconomic indicators including GDP, life expectancy, social support, freedom, and trust levels.

### Key Questions Explored
- Which countries consistently rank highest and lowest in happiness?
- How has global happiness evolved over the past decade?
- What factors correlate most strongly with national happiness?
- Do wealthier countries always have happier populations?
- Which countries achieve high happiness despite lower GDP?

## 🗂️ Project Structure

```
world-happiness-analysis/
├── data/
│   ├── raw/                    # Original dataset
│   ├── processed/              # Cleaned data
│   └── external/               # Additional datasets
├── notebooks/                  # Jupyter analysis notebooks
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_correlation_analysis.ipynb
│   ├── 04_country_comparisons.ipynb
│   └── 05_time_trends.ipynb
├── src/                        # Reusable Python modules
├── outputs/                    # Generated visualizations & reports
│   ├── figures/
│   ├── reports/
│   └── tables/
└── requirements.txt
```

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- Git (for cloning the repository)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/world-happiness-analysis.git
   cd world-happiness-analysis
   ```

2. **Create and activate virtual environment**
   ```bash
   python -m venv happiness_env

   # Windows (Git Bash)
   source happiness_env/Scripts/activate

   # macOS/Linux
   source happiness_env/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

5. **Start with the exploration notebook**
   Open `notebooks/01_data_exploration.ipynb` to begin the analysis

## 📈 Dataset Information

**Source**: [World Happiness Report 2015-2024 (Kaggle)](https://www.kaggle.com/datasets/yadiraespinoza/world-happiness-2015-2024)

**Key Variables**:
- **Happiness Score**: Life satisfaction rating (0-10 scale)
- **GDP per Capita**: Economic prosperity indicator
- **Social Support**: Strength of social networks
- **Healthy Life Expectancy**: Health and longevity measure
- **Freedom**: Freedom to make life choices
- **Generosity**: National donation behavior
- **Trust**: Perceptions of corruption (government & business)

**Coverage**: 150+ countries | 2015-2024 | 1,500+ observations

## 🔍 Key Findings

> **Note**: Add your findings here as you complete the analysis

### Top Insights
- [ ] Nordic countries consistently rank in top 10 for happiness
- [ ] GDP correlates with happiness but shows diminishing returns
- [ ] Social support and freedom are stronger predictors than wealth alone
- [ ] Global happiness trends reveal...

### Interesting Discoveries
- [ ] Countries that "punch above their weight" in happiness
- [ ] Regional patterns and cultural influences
- [ ] Impact of major global events on happiness trends

## 📊 Visualizations

Key charts and graphs generated in this analysis:

- **Happiness Distribution**: Global happiness score distribution over time
- **Correlation Matrix**: Relationships between all happiness factors
- **Country Rankings**: Top and bottom performers by year
- **Regional Comparisons**: Happiness patterns by continent
- **Trend Analysis**: Decade-long happiness trajectories
- **GDP vs Happiness**: Economic wealth and well-being relationship

## 🛠️ Technologies Used

- **Python 3.9+**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib & Seaborn**: Data visualization
- **Plotly**: Interactive visualizations
- **Jupyter Notebook**: Interactive development environment
- **Scikit-learn**: Statistical analysis and modeling

## 📋 Analysis Workflow

1. **Data Exploration** (`01_data_exploration.ipynb`)
   - Dataset overview and structure
   - Missing value analysis
   - Basic statistical summaries

2. **Data Cleaning** (`02_data_cleaning.ipynb`)
   - Handle missing values
   - Standardize country names
   - Data type conversions

3. **Correlation Analysis** (`03_correlation_analysis.ipynb`)
   - Factor correlation matrix
   - Identify key happiness drivers
   - Statistical significance testing

4. **Country Comparisons** (`04_country_comparisons.ipynb`)
   - Top/bottom country rankings
   - Regional analysis
   - Outlier identification

5. **Time Trends** (`05_time_trends.ipynb`)
   - Decade-long happiness evolution
   - Country trajectory analysis
   - Global trend patterns

## 🔮 Future Enhancements

- [ ] Add population and demographic data
- [ ] Include geographic mapping visualizations
- [ ] Implement predictive modeling
- [ ] Integrate economic crisis impact analysis
- [ ] Create interactive dashboard with Streamlit/Dash

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **World Happiness Report Team** for collecting and publishing this valuable dataset
- **Kaggle Community** for hosting and maintaining the dataset
- **Our World in Data** for additional context and insights

## 📞 Contact

**Ashutosh Bikram Thakur** -  aswat0thama@gmail.com.com

Project Link: [https://github.com/ashu-tagore/world-happiness-analysis](https://github.com/ashu-tagore/World_Happiness_Analysis)

---

⭐ If you found this project helpful, please give it a star!
