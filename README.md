# What's the Most Common Genre on Netflix?

## 📊 Overview  
This project explores one focused question:  
**“Which genre appears most frequently in Netflix’s content catalog?”**

Using real-world data from Netflix’s global library, I applied Python and data visualization techniques to uncover insights about the most dominant genres on the platform. This is a starter data analytics project designed to demonstrate my ability to clean, manipulate, and visualize data using industry-relevant tools.

---

## 📁 Dataset  
[Kaggle: Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
- 8,000+ titles
- Includes: title, type (Movie/TV Show), director, cast, release year, rating, and genres (via `listed_in` column)

---

## 🛠 Tools Used  
- **Python** (Pandas, Matplotlib)  
- **Jupyter Notebook**  
- **Excel** (optional for alternative visualizations)  
- GitHub (for project versioning & publishing)

---

## 🧠 My Process

### 1. Data Exploration
- Loaded the dataset and examined missing values, column types, and key fields.

### 2. Data Cleaning
- Focused on the `listed_in` column (Netflix’s genre tags).
- Split multiple genre tags into individual entries for accurate counting.

### 3. Analysis
- Used `.explode()` in Pandas to unstack lists into rows.
- Counted and sorted the frequency of genres across all titles.

### 4. Visualization
- Built a **bar chart** of the top 10 most frequent genres using Matplotlib.

---

## 🔍 Key Insight  
> 📌 **"Dramas"** are the most common genre on Netflix, followed by **Comedies** and **Documentaries**. This insight reflects global content demand and user preferences on the platform.
