# Batting Intent Analysis in IPL 2025
 
*A data-driven analysis of batting strategies in IPL 2025*

---

## 📁 Dataset
- **File**: [`ipl_match_1473461_deliveries.csv`](ipl_match_1473461_deliveries.csv)  
- **Description**: Ball-by-ball delivery data for RCB vs DC match (IPL 2025), including:
  - Batter/bowler interactions
  - Runs scored (regular + extras)
  - Wicket details
  - Match phases (powerplay, death overs)

---

## 🧠 Key Analyses
| Analysis Area          | Metrics Used                          | Tools               |
|------------------------|---------------------------------------|---------------------|
| Batting Aggression     | Strike rate, boundary %               | Pandas, Matplotlib  |
| Bowler Impact          | Dot balls, economy rate               | Seaborn             |
| Match Phase Trends     | Powerplay vs death over comparisons  | Plotly (optional)   |

**Sample Insights**:
- 🔥 PD Salt's explosive start (SR 180+ in powerplay)
- 🎯 MA Starc's lethal yorkers (3 wickets in death overs)
- 📉 Middle-over slowdown (RCB's 8-15 over struggle)

---

## 🛠️ Tech Stack
```python
# Core Libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

# Optional
from plotly import express as px  # For interactive viz
🚀 Quick Start
Clone repo:

git clone https://github.com/your-username/ipl-batting-analysis.git
cd ipl-batting-analysis
Run analysis:

jupyter notebook Batting_Intent_Analysis_IPL_2025.ipynb
📊 Example Visualization
(Add a screenshot of your best chart here)

# Sample code to generate viz
sns.barplot(data=df, x='batter', y='strike_rate')
plt.title('Batting Strike Rates by Player')
