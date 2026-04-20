# 🏃 Ultramarathon Race Performance Analysis

An exploratory data analysis (EDA) project examining two centuries of ultramarathon race data, with a focus on athlete performance across 50km and 50-mile events.

---

## 📊 Dataset

**Source:** `Two_Centuries_Races.csv` — downloaded from [Kaggle: Two Centuries of UM Races](https://www.kaggle.com/datasets/fatihyavuzz/two-centuries-of-um-races)

The dataset spans multiple decades of ultramarathon events and includes the following fields:

| Column | Description |
|---|---|
| `Year of event` | Year the race took place |
| `Event dates` | Specific date of the event |
| `Event name` | Name and country of the race |
| `Event distance/length` | Race distance (e.g., 50km, 50mi) |
| `Event number of finishers` | Total finishers in the event |
| `Athlete performance` | Finishing time |
| `Athlete club` | Athlete's running club |
| `Athlete country` | Athlete's country of origin |
| `Athlete year of birth` | Used to derive athlete age |
| `Athlete gender` | M / F |
| `Athlete age category` | Age bracket (e.g., M35, W50) |
| `Athlete average speed` | Average speed in km/h |
| `Athlete ID` | Unique identifier per athlete |

---

## 🔍 Analysis Questions Explored

- **Gender speed gap** — What is the difference in average speed between male and female athletes in 50km and 50-mile races?
- **Top performing age groups** — Which age groups perform best in 50-mile races? (minimum 20 races)
- **Worst performing age groups** — Which age groups perform worst in 50-mile races? (minimum 10 races)
- **Seasonal effect** — Do athletes run slower in summer compared to winter?

---

## 📈 Visualizations

- **Distribution plot** — Speed distribution for 50-mile athletes
- **Violin plot** — Speed comparison by race length and gender
- **Linear regression plot** — Relationship between athlete age and average speed, split by gender

---

## 🛠️ Tools & Libraries

- **Python 3**
- **Pandas** — Data loading, cleaning, and transformation
- **NumPy** — Numerical operations
- **Seaborn** — Statistical data visualization
- **Google Colab** — Development environment

---

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/adewalehenry14/ultramarathon-race-analysis.git
   ```

2. Open the notebook in Google Colab:
   - Go to [colab.research.google.com](https://colab.research.google.com)
   - File → Open notebook → GitHub tab → Search for this repo

3. Download the dataset:
   - Download `Two_Centuries_Races.csv` from [Kaggle](https://www.kaggle.com/datasets/fatihyavuzz/two-centuries-of-um-races)
   - Upload it to the `/content/` directory in Colab

4. Run all cells sequentially.

---

## 📁 Project Structure

```
├── Python_Project.ipynb   # Main analysis notebook
└── README.md
```

---

## 👤 Author

**Adewale Adetunji**
