# IPL 2022 Data Analysis 🏏

A comprehensive data analysis project exploring the Indian Premier League (IPL) 2022 season, uncovering insights about match outcomes, player performances, and team dynamics through statistical analysis and visualization.

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Analysis Overview](#analysis-overview)
- [Key Insights](#key-insights)
- [Installation & Usage](#installation--usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🎯 About the Project

The Indian Premier League (IPL) is a professional T20 cricket league in India, featuring franchises representing cities. This project analyzes IPL 2022 match-level data to derive meaningful insights about match outcomes, player performances, team dynamics, and venue statistics.

**Purpose:** Educational project to demonstrate data analysis skills using Python libraries for data manipulation, statistical analysis, and visualization.

## 📊 Dataset

The dataset contains IPL 2022 match information with the following key columns:

- **Match Details:** `match_id`, `date`, `venue`, `stage`
- **Team Information:** `team1`, `team2`, `match_winner`, `toss_winner`, `toss_decision`
- **Match Statistics:** `first_ings_score`, `second_ings_score`, `first_ings_wkts`, `second_ings_wkts`
- **Game Outcomes:** `won_by` (Runs/Wickets), `margin`
- **Performance:** `player_of_the_match`, `top_scorer`, `highscore`, `best_bowling`, `best_bowling_figure`

**Total Records:** 74 matches  
**Total Columns:** 20 columns

## 🛠️ Technologies Used

- **Python 3.x**
- **NumPy** - Numerical computing
- **Pandas** - Data manipulation and analysis
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization

## 📁 Project Structure

```
ipl-2022-analysis/
│
├── ipl-analysis.ipynb    # Main Jupyter notebook with analysis
├── IPL.csv              # Dataset containing IPL 2022 match data
└── README.md            # Project documentation
```

## 🔍 Analysis Overview

### 1. **Data Exploration & Cleaning**

- Loaded and inspected the dataset structure
- Checked for null values across all columns
- Validated data types and basic statistics
- Dataset info: 74 rows × 20 columns

### 2. **Basic Questions Analysis**

- **Team Performance:** Which team won the most matches?
- **Toss Trends:** Analysis of toss decision patterns (Bat vs Field)
- **Toss Impact:** Relationship between toss winners and match winners (~65% correlation)
- **Victory Patterns:** Distribution of wins by runs vs wickets (50% each)

### 3. **Key Player Performances**

- **Player of the Match Awards:** Top 5 players with most awards
  - Kuldeep Yadav (4 awards - leading performer)
  - Jos Buttler, Wanindu Hasaranga, Umesh Yadav, Quinton de Kock (2 awards each)

- **Top Scorers:** Highest run-scorers in IPL 2022
  - Jos Buttler (491 runs)
  - Quinton de Kock (372 runs)
  - Shubman Gill (288 runs)
  - Faf du Plessis (251 runs)
  - Shikhar Dhawan (257 runs)

### 4. **Bowling Excellence**

- **Top 10 Bowlers with Most Wickets:**
  - Yuzvendra Chahal (17 wickets - leading wicket-taker)
  - Jasprit Bumrah (11 wickets)
  - Kuldeep Yadav (11 wickets)
  - Rashid Khan (11 wickets)
  - Josh Hazlewood (10 wickets)
  - And 5 more players completing the top 10

### 5. **Venue Analysis**

- **Most Matches Played by Venue:**
  - Wankhede Stadium, Mumbai (21 matches)
  - Dr DY Patil Sports Academy, Mumbai (20 matches)
  - Brabourne Stadium, Mumbai (16 matches)
  - Maharashtra Cricket Association Stadium, Pune (13 matches)
  - Other venues with fewer matches

### 6. **Custom Insights**

- **Highest Margin Victory:** Chennai won by 91 runs against Delhi
- Team comparison and head-to-head statistics
- Stage-wise performance analysis (Group stage vs Playoffs)

## 💡 Key Insights

1. **Team Dominance:** Gujarat Titans emerged as the most successful team with 12 wins
2. **Toss Strategy:** 79.7% of teams chose to field first after winning the toss
3. **Toss Advantage:** Teams winning the toss had approximately 65% chance of winning the match
4. **Balanced Outcomes:** Victories were equally distributed between runs (50%) and wickets (50%)
5. **Consistent Performers:** Kuldeep Yadav dominated with most Player of the Match awards
6. **Batting Excellence:** Jos Buttler led the run charts with 491 runs
7. **Bowling Prowess:** Yuzvendra Chahal was the leading wicket-taker with 17 wickets
8. **Home Advantage:** Mumbai venues hosted the majority of matches

## 🚀 Installation & Usage

### Prerequisites

```bash
Python 3.x
Jupyter Notebook
```

### Installation Steps

1. Clone the repository

```bash
git clone https://github.com/MeetBataviya13/Python-Matplot-Seaborn-Projects.git
cd ipl-analysis
```

2. Install required packages

```bash
pip install numpy pandas matplotlib seaborn
```

3. Launch Jupyter Notebook

```bash
jupyter notebook ipl-analysis.ipynb
```

4. Run all cells to see the complete analysis

## 🤝 Contributing

This is an educational project, but contributions are welcome! If you have suggestions for improvements:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is created for educational purposes. Feel free to use it for learning and reference.

## 📧 Contact

**Meet Bataviya**

GitHub: [@MeetBataviya13](https://github.com/MeetBataviya13)

Project Link: [https://github.com/MeetBataviya13/Python-Matplot-Seaborn-Projects](https://github.com/MeetBataviya13/Python-Matplot-Seaborn-Projects)

---

⭐ If you found this project helpful, please consider giving it a star!

**Note:** This project is for educational and learning purposes only. The dataset represents IPL 2022 season data.
