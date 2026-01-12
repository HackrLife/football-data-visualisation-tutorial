# football-data-visualisation-tutorial
# 🔵🔴 Football Data Visualization Tutorial

## Creating Professional Football Visualizations with Python

**Learn to build 20 stunning data visualizations using Barcelona La Liga 2025-26 data.**

---

## 📁 Files Included

| File                                 | Description                                                    |
| ------------------------------------ | -------------------------------------------------------------- |
| `barca_visualization_tutorial.ipynb` | Complete Jupyter/Colab notebook with all code and explanations |
| `Barca_La_Liga_2025-26.csv`          | Raw data from FBref used in the tutorial                       |
| `README.md`                          | This file — setup instructions and overview                    |

---

## 🚀 Quick Start (Google Colab)

### Option 1: Upload to Colab (Recommended)

1. Go to [Google Colab](https://colab.research.google.com)
2. Click **File → Upload notebook**
3. Upload `barca_visualization_tutorial.ipynb`
4. Click **Runtime → Run all** (or run cells one-by-one with Shift+Enter)

### Option 2: Open from GitHub

If you've hosted these files on GitHub:
1. Go to [Google Colab](https://colab.research.google.com)
2. Click **File → Open notebook → GitHub**
3. Paste your repository URL

---

## 📊 What You'll Build

### Bar Charts (5)

| \\# | Visualization                   | Purpose                             |
| --- | ------------------------------- | ----------------------------------- |
| 1   | Team xAG Pie Chart              | Show chance creation distribution   |
| 2   | Creative Output Stacked Bar     | Compare xAG vs actual assists       |
| 3   | xAG per 90 Bar                  | Rank players by creation quality    |
| 4   | Assists per 90 Bar              | Rank players by assists             |
| 5   | Progressive Actions Grouped Bar | Compare passes, carries, receptions |

### Player Profiles (10)

| \\#   | Player          | Charts        |
| ----- | --------------- | ------------- |
| 6-7   | Lamine Yamal    | Radar + Pizza |
| 8-9   | Pedri           | Radar + Pizza |
| 10-11 | Raphinha        | Radar + Pizza |
| 12-13 | Marcus Rashford | Radar + Pizza |
| 19-20 | Fermín López    | Radar + Pizza |

### Comparison & Analysis (5)

| \\# | Visualization                | Purpose                |
| --- | ---------------------------- | ---------------------- |
| 14  | Head-to-Head Bar             | Compare top 5 creators |
| 15  | Creator vs Finisher Scatter  | Dual threats analysis  |
| 16  | Expected vs Actual Scatter   | Over/underperformance  |
| 17  | Progression Style Scatter    | Passers vs carriers    |
| 18  | Volume vs Efficiency Scatter | Minutes vs output      |

---

## 📚 What You'll Learn

- ✅ Loading and cleaning FBref data with Pandas
- ✅ Creating pie charts with `matplotlib`
- ✅ Building horizontal bar charts with value labels
- ✅ Making grouped bar charts for multi-metric comparison
- ✅ Creating radar charts for player profiles
- ✅ Building pizza/percentile charts
- ✅ Making scatter plots with quadrant analysis
- ✅ Applying custom color palettes (Blaugrana theme)
- ✅ Adding annotations and styling
- ✅ Saving high-quality PNG exports

---

## 🛠 Requirements

The notebook uses standard Python data science libraries that come pre-installed in Google Colab:

```python
pandas       # Data manipulation
matplotlib   # Visualization
numpy        # Numerical operations
```

No additional installation required!

---

## 📖 How to Use This Tutorial

### For Learning (Recommended)

1. Run each cell one-by-one (Shift + Enter)
2. Read the markdown explanations before each code block
3. Look at the output and understand what each line does
4. Experiment by changing values (colors, players, metrics)

### For Quick Results

1. Click **Runtime → Run all**
2. Scroll through to see all 20 visualizations
3. Download any charts you want to use

---

## 🎨 Color Palette Used

| Color           | Hex Code  | Usage                  |
| --------------- | --------- | ---------------------- |
| Barça Blue      | `#004D98` | Primary                |
| Barça Red       | `#A50044` | Secondary              |
| Gold            | `#EDBB00` | Accent                 |
| Dark Background | `#1a1a2e` | Chart backgrounds      |
| Fermín Green    | `#00C853` | Fermín López highlight |

Feel free to customize these for your own team!

---

## 📊 Data Source

Data is from [FBref.com](https://fbref.com) — Barcelona La Liga 2025-26 season through Matchday 19.

### How to Get Your Own Data

1. Go to [FBref.com](https://fbref.com)
2. Navigate to your team's page
3. Find the stats table you want
4. Click **"Share & Export"** → **"Get table as CSV"**
5. Save and upload to Colab

---

## 💡 Tips for Customization

### Change Teams
Replace the data in Section 4 with your team's stats.

### Change Colors
Update the color constants in Section 2:
```python
BARCA_BLUE = '#004D98'  # Change to your team's color
BARCA_RED = '#A50044'   # Change to your team's color
```

### Add More Players
Add names to the `TOP5_CREATORS` list and update `PLAYER_COLORS` dictionary.

### Different Metrics
FBref has many more stats! Try:
- Defensive: tackles, interceptions, blocks
- Passing: pass completion %, key passes
- Shooting: shots, xG, shot accuracy

---

## 🙏 Credits

**Created by:** HackrLife  
**Newsletter:** [Barça Futbol](https://barcafutbol.substack.com)  
**Data Source:** [FBref.com](https://fbref.com)

---

## 📬 Get More Content

For weekly tactical analysis, data visualizations, and Barcelona insights:

**Subscribe to Barça Futbol** → [barcafutbol.substack.com](https://barcafutbol.substack.com)

---

## 📄 License

This tutorial is provided free for educational purposes. Feel free to:
- ✅ Use for personal learning
- ✅ Modify for your own projects
- ✅ Share with attribution

Please credit **HackrLife** and **Barça Futbol** if you share or republish.

---

*Visca el Barça! 🔵🔴*
