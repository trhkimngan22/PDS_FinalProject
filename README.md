# 📊 Netflix Content Analysis Project

## 🎯 Overview
A comprehensive data analysis project examining Netflix's content library to uncover trends, patterns, and strategic insights about the streaming platform's content evolution. This project analyzes various aspects of Netflix's catalog including content types, genres, international diversity, and creator collaboration strategies.

## 📁 Project Structure
```
PDS_FinalProject/
│
├── data/
│   ├── netflix_titles.csv              # Original dataset
│   └── netflix_titles_cleaned.csv       # Cleaned dataset
│
├── data_collection/
│   └── data_collection.ipynb            # Data collection & documentation
│
├── data_exploration/
│   └── data_exploration.ipynb           # Data exploration & preprocessing
│
├── data_questions/
│   ├── knhung_question1.ipynb          # Question 1: Content & genre changes
│   ├── kngan_question2.ipynb           # Question 2: International content trends
│   └── TGia_question3.ipynb            # Question 3: Director/cast collaboration
│
└── README.md                            # Project documentation
```

## 📊 Dataset Information

### Source
- **Platform**: Kaggle.
- **Original Source**: (#Netflix Movies and TV Shows)[!https://www.kaggle.com/datasets/rahulvyasm/netflix-movies-and-tv-shows]
- **License**: CC0: Public Domain.
- **Size**: 8,809 records.

### Features
The dataset contains the following columns:
- `show_id`: Unique identifier for each title.
- `type`:  The category of the title, which is either 'Movie' or 'TV Show'.
- `title`: Name of the content.
- `director`: Director(s) of the content. (Contains null values for some entries, especially TV shows where this information might not be applicable.)
- `cast`: Cast members. (Some entries might not have this information.)
- `country`: Country/countries of production.
- `date_added`: Date added to Netflix.
- `release_year`: Year of original release.
- `rating`: Content rating (PG, TV-MA, etc.)
- `duration`: Duration (minutes for movies, seasons for TV shows).
- `listed_in`: Genres/categories.
- `description`: Content description.

## 🔍 Research Questions

### Question 1: Content Volume & Genre Evolution
**Research Focus**: How have the quantity and genre distribution of Netflix content changed over the years?

**Key Analysis**:
- Total content additions per year (Movies vs TV Shows).
- Genre distribution trends over time.
- Strategic shifts in content production priorities.

**Benefits**: 
- Understand Netflix's content expansion strategy.
- Identify genre preferences and their evolution.
- Recognize strategic shifts in content development.

---

### Question 2: International Content Diversification  
**Research Focus**: What are the trends in Netflix's international vs domestic content diversification?

**Key Analysis**:
- Ratio of international vs domestic (US) content over time.
- Countries with significant content production growth.
- Collaborative productions between countries.

**Benefits**:
- Analyze Netflix's global expansion strategy.
- Identify emerging international content markets.
- Understand global content distribution patterns.

---

### Question 3: Creator Collaboration Strategy
**Research Focus**: Is Netflix changing its collaboration strategy with prominent directors and cast members by genre and time?

**Key Analysis**:
- Director and cast appearance frequency by genre over time.
- Relationship between creators and content genres.
- Evolution of partnerships with established vs emerging talent.

**Benefits**:
- Understand Netflix's talent acquisition strategy.
- Identify preferred creators by genre.
- Recognize shifts in production partnerships.

## 🛠️ Technologies Used

### Programming Language
- Python 3.x

### Libraries & Tools
- **Data Manipulation**: `pandas`, `numpy`.
- **Data Visualization**: `matplotlib`, `seaborn`.
- **Development Environment**: Jupyter Notebook.

## 📈 Key Findings

### Content Growth
- Analysis of Netflix's exponential content growth patterns.
- Identification of peak content addition periods.
- Evolution from movie-focused to balanced content strategy.

### International Expansion
- Significant increase in international content production.
- Emergence of key content-producing countries beyond the US.
- Growth in cross-country collaborative productions.

### Genre Trends
- Evolution of genre preferences over time.
- Identification of dominant and emerging genres.
- Strategic genre diversification patterns.

### Creator Partnerships
- Analysis of long-term vs project-based collaborations.
- Genre-specific creator preferences.
- Balance between established and new talent.

## 🚀 Getting Started

### Prerequisites
```bash
# Install required packages
pip install pandas numpy matplotlib seaborn jupyter
```

### Running the Analysis

1. **Data Collection & Documentation**
   ```bash
   jupyter notebook data_collection/data_collection.ipynb
   ```

2. **Data Exploration & Preprocessing**
   ```bash
   jupyter notebook data_exploration/data_exploration.ipynb
   ```

3. **Research Question Analysis**
   ```bash
   # Question 1: Content & Genre Evolution
   jupyter notebook data_questions/knhung_question1.ipynb
   
   # Question 2: International Content Trends
   jupyter notebook data_questions/kngan_question2.ipynb
   
   # Question 3: Creator Collaboration Strategy
   jupyter notebook data_questions/TGia_question3.ipynb
   ```

## 📝 Methodology

### 1. Data Collection
- Dataset acquired from Kaggle platform.
- Comprehensive documentation of data source and licensing.
- Verification of data collection methodology.

### 2. Data Exploration & Preprocessing
- Initial data quality assessment.
- Handling missing values and duplicates.
- Data type validation and conversion.
- Feature engineering for analysis.

### 3. Analysis & Visualization
- Statistical analysis of trends.
- Time-series analysis of content evolution.
- Comparative analysis across categories.
- Interactive visualizations for insights.

### 4. Interpretation & Insights
- Pattern identification.
- Trend analysis.

## 💡 Insights & Applications

### For Content Creators
- Understanding genre demand trends.
- Identifying collaboration opportunities.
- Recognizing international market potentials.

### For Business Analysts
- Strategic planning insights.
- Market expansion opportunities.
- Content investment prioritization.

### For Researchers
- Entertainment industry trends.
- Digital content consumption patterns.
- Global media distribution strategies.

## 📄 License

This project is for educational purposes. The dataset is licensed under CC0: Public Domain.

---

**Note**: This project was completed as part of a data science course focusing on practical data analysis and visualization skills using real-world datasets.

## 🏆 Achievements

- Comprehensive data cleaning and preprocessing pipeline.
- Multi-dimensional analysis of Netflix content strategy.
- Professional data visualizations and insights.
- Collaborative team project with distinct research questions.
- Reproducible analysis with clear documentation.

---

*Last Updated: December 2024*