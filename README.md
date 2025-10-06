# 🌍 World Happiness Analysis (2015-2024)

A comprehensive data science project analyzing the World Happiness Report dataset to uncover insights about global well-being and the factors that contribute to national happiness levels.

## 📊 Project Overview

This project explores a decade of happiness data from 150+ countries, investigating relationships between happiness scores and various socioeconomic indicators including GDP, life expectancy, social support, freedom, and trust levels.

### Key Questions Explored

* Which countries consistently rank highest and lowest in happiness?
* How has global happiness evolved over the past decade?
* What factors correlate most strongly with national happiness?
* Do wealthier countries always have happier populations?
* Which countries achieve high happiness despite lower GDP?

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

* Python 3.8 or higher
* Git (for cloning the repository)

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

* **Happiness Score**: Life satisfaction rating (0-10 scale)
* **GDP per Capita**: Economic prosperity indicator
* **Social Support**: Strength of social networks
* **Healthy Life Expectancy**: Health and longevity measure
* **Freedom**: Freedom to make life choices
* **Generosity**: National donation behavior
* **Trust**: Perceptions of corruption (government & business)

**Coverage**: 150+ countries | 2015-2024 | 1,500+ observations

---

## 🔍 Key Findings

### 🧠 Top Insights

* **Nordic countries (Finland, Denmark, Iceland, Norway, Sweden)** consistently rank in the global top 10 for happiness from 2015–2024.
* **GDP per capita** shows a **strong positive correlation (r ≈ 0.78)** with happiness, but **diminishing returns** beyond a certain income level.
* **Social support** and **freedom to make life choices** are **stronger predictors of happiness** than economic wealth alone.
* **Trust in government** and **low corruption levels** significantly enhance national well-being, especially in developed economies.
* **Healthy life expectancy** is a key long-term contributor to sustained happiness, particularly in high-income nations.
* Countries with **economic volatility** (e.g., Venezuela, Lebanon) show sharp happiness declines, while those with **stable governance** (e.g., Finland, Switzerland) remain resilient.

### 🌍 Interesting Discoveries

* **Costa Rica** and **Uruguay** “punch above their weight” — achieving high happiness scores despite mid-level GDPs.
* **Sub-Saharan African nations** consistently rank lowest, but a few (like **Mauritius**) demonstrate gradual upward trends.
* **Post-pandemic years (2020–2022)** saw **global dips in happiness**, followed by recovery driven by increased **social cohesion**.
* **Asian countries** such as **Singapore** and **Japan** show moderate happiness despite high GDP — reflecting cultural and work-life balance influences.
* **Trust and generosity** factors weakened in correlation strength after 2020, possibly due to shifts in social priorities.
* **Regional clustering** of happiness scores suggests cultural and governance models play a large role beyond pure economics.

### 📈 Time Trends

* Global average happiness **plateaued between 2018–2024**, indicating possible saturation effects in developed nations.
* **Eastern Europe and Latin America** show steady improvement; **North America and Western Europe** remain stable but stagnating.
* **Happiness inequality** between top and bottom quartiles has widened slightly since 2019.
* **Environmental factors** (like pollution and safety) began correlating more strongly with happiness in recent years.

---

## 📊 Visualizations

Key charts and graphs generated in this analysis:

* **Happiness Distribution**: Global happiness score distribution over time
* **Correlation Matrix**: Relationships between all happiness factors
* **Country Rankings**: Top and bottom performers by year
* **Regional Comparisons**: Happiness patterns by continent
* **Trend Analysis**: Decade-long happiness trajectories
* **GDP vs Happiness**: Economic wealth and well-being relationship

## 🛠️ Technologies Used

* **Python 3.9+**: Core programming language
* **Pandas**: Data manipulation and analysis
* **NumPy**: Numerical computing
* **Matplotlib & Seaborn**: Data visualization
* **Plotly**: Interactive visualizations
* **Jupyter Notebook**: Interactive development environment
* **Scikit-learn**: Statistical analysis and modeling

## 📋 Analysis Workflow

1. **Data Exploration** (`01_data_exploration.ipynb`)

   * Dataset overview and structure
   * Missing value analysis
   * Basic statistical summaries

2. **Data Cleaning** (`02_data_cleaning.ipynb`)

   * Handle missing values
   * Standardize country names
   * Data type conversions

3. **Correlation Analysis** (`03_correlation_analysis.ipynb`)

   * Factor correlation matrix
   * Identify key happiness drivers
   * Statistical significance testing

4. **Country Comparisons** (`04_country_comparisons.ipynb`)

   * Top/bottom country rankings
   * Regional analysis
   * Outlier identification

5. **Time Trends** (`05_time_trends.ipynb`)

   * Decade-long happiness evolution
   * Country trajectory analysis
   * Global trend patterns

## 🔮 Future Enhancements

* [ ] Add population and demographic data
* [ ] Include geographic mapping visualizations
* [ ] Implement predictive modeling
* [ ] Integrate economic crisis impact analysis
* [ ] Create interactive dashboard with Streamlit/Dash

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

* **World Happiness Report Team** for collecting and publishing this valuable dataset
* **Kaggle Community** for hosting and maintaining the dataset
* **Our World in Data** for additional context and insights

## 📞 Contact

**Ashutosh Bikram Thakur** -  [aswat0thama@gmail.com](mailto:aswat0thama@gmail.com)

Project Link: [https://github.com/ashu-tagore/world-happiness-analysis](https://github.com/ashu-tagore/World_Happiness_Analysis)

⭐ If you found this project helpful, please give it a star!
