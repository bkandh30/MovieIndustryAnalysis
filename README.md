# 🎬 Movie Industry Data Analysis

This project performs exploratory data analysis (EDA) on a dataset of movies to uncover insights into factors influencing movie success such as revenue, popularity, genres, and production trends.

## 📁 Dataset

- **Source**: `movies.csv` – Contains information about 4,800+ movies including:
  - Title, Genre(s), Release Date
  - Revenue, Budget, Popularity
  - Runtime, Production Companies
  - Vote Average, Vote Count

## 📊 Key Analysis Performed

- **Data Preprocessing**:
  - Handled null values and data type inconsistencies.
  - Cleaned and parsed multi-valued columns (e.g., genres, production companies).

- **Exploratory Analysis**:
  - Identified trends in movie production and popularity by year.
  - Analyzed correlation between **budget**, **revenue**, and **popularity**.
  - Found most profitable genres and most active production companies.
  - Determined which factors contribute most to movie revenue.

- **Visualizations**:
  - Used `Matplotlib` and `Seaborn` to visualize:
    - Top grossing movies
    - Genre-wise revenue breakdown
    - Revenue vs Popularity scatter plots
    - Yearly trends in production and revenue

## 🛠️ Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/bkandh30/MovieIndustryAnalysis.git
   cd movie-industry-analysis
   ```

2. Open the notebook:
   ```bash
   jupyter notebook MovieIndustryData.ipynb
   ```

## 📌 Future Work

- Apply machine learning to predict revenue based on budget, genre, and cast.
- Analyze impact of director/lead actor on movie success.
- Integrate additional metadata like IMDb ratings or streaming release performance.

## 🧾 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
