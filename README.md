# NBA Elite Player Analysis

An interactive data visualization dashboard analyzing NBA player performance through advanced analytics. Created as a final project for MATH 230: Data Visualization & Computing at Bucknell University.

## 🏀 Project Overview

This project explores the complex landscape of NBA player evaluation through advanced analytics, moving beyond traditional counting statistics to identify truly elite performers. The interactive dashboard combines multiple analytical frameworks to provide a comprehensive view of player value across scoring, efficiency, defense, and overall team impact.

## 🎯 Key Features

### Interactive Dashboard Sections
- **Overview**: Introduction to advanced NBA metrics and project methodology
- **Player Efficiency**: Analysis using Player Efficiency Rating (PER) with positional comparisons
- **Two-Way Analysis**: Evaluation of offensive and defensive contributions
- **Efficiency vs. Usage**: Examination of scoring efficiency relative to usage rate
- **About**: Project background and technical details

### Advanced Metrics Analyzed
- **Player Efficiency Rating (PER)**: Comprehensive per-minute statistical production
- **Value Over Replacement Player (VORP)**: Contribution relative to replacement-level players
- **Win Shares (WS)**: Individual contribution to team victories
- **True Shooting Percentage (TS%)**: Comprehensive scoring efficiency measure
- **Usage Rate**: Percentage of team plays used while on court
- **Offensive/Defensive Ratings**: Impact per 100 possessions

### Interactive Features
- Customizable filters for minimum games played, minutes per game, and positions
- Dynamic visualizations that update based on user selections
- Hover tooltips with detailed player information
- Position-based analysis with radar charts
- Multi-dimensional scatter plots for advanced comparisons

## 🛠️ Technical Stack

- **R**: Primary programming language
- **Shiny**: Interactive web application framework
- **flexdashboard**: Dashboard layout and structure
- **ggplot2 + plotly**: Interactive data visualizations
- **dplyr**: Data manipulation and filtering
- **RColorBrewer**: Custom color palettes
- **fmsb**: Radar chart generation

## 📊 Data Source

NBA player statistics from the 2023-24 regular season, including:
- Traditional box score statistics (points, rebounds, assists, etc.)
- Advanced calculated metrics (PER, VORP, Win Shares, etc.)
- Shooting efficiency data (field goal percentages, true shooting, etc.)
- Usage and pace-adjusted statistics

## 🚀 Live Demo

The interactive dashboard is deployed and accessible at:
**[https://ppc7dm-aiden-kim.shinyapps.io/Math-230-Final-Project/](https://ppc7dm-aiden-kim.shinyapps.io/Math-230-Final-Project/)**

## 📁 Project Structure

```
├── _site.yml                    # Site configuration
├── index.Rmd                   # Portfolio homepage with project preview
├── final_project.Rmd           # Final project page with embedded dashboard
├── Visualizations_Final.Rmd    # Main Shiny dashboard application
├── nba_data_processed.csv      # Processed NBA statistics dataset
└── docs/                       # Generated website files
    ├── index.html
    ├── final_project.html
    └── static visualizations/
```

## 🎨 Design Philosophy

The project employs a custom pastel color palette designed for accessibility and visual appeal. The interface prioritizes:
- Clean, modern design with intuitive navigation
- Responsive visualizations that work across devices
- Clear information hierarchy with contextual explanations
- Interactive elements that enhance rather than distract from analysis

## 🔍 Key Insights

The analysis reveals several fascinating trends in NBA player evaluation:

1. **Position Evolution**: Centers like Joel Embiid and Nikola Jokić are breaking traditional molds by excelling in scoring and playmaking
2. **Two-Way Excellence**: The most valuable players excel on both ends of the court, not just offensively
3. **Efficiency vs. Volume**: Elite scorers maintain high efficiency despite heavy usage, separating stars from volume scorers
4. **Statistical Completeness**: Modern NBA superstars display unprecedented breadth across statistical categories

## 👨‍🎓 About the Author

**Aiden Kim**  
Computer Science & Data Science Student  
Bucknell University  
GitHub: [@A319K](https://github.com/A319K)
