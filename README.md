## FIFA 24 Finishing Analysis

This project analyses FIFA 24 player attributes to explore which technical and physical attributes are most strongly associated with finishing ability.

### Dataset
FIFA 24 Player Stats dataset.
File located in `data/player_stats.csv`.

### Analysis Notebook
The full analysis is contained in:
- `notebooks/fifa24_finishing_analysis.ipynb`

### Methods
• Data inspection and cleaning  
• Standardising text fields and converting value to numeric  
• Removing goalkeepers to focus on outfield player attributes  
• Descriptive statistics and grouped summaries  
• Correlation analysis focused on finishing and related attributes  
• Visualisations including bar chart, histogram, scatter plot, and boxplot  
• Extra analysis including a technical skill feature and additional comparisons  

### Key Findings
• Finishing is most strongly correlated with technical shooting attributes such as long shots, shot power, and dribbling  
• Speed attributes show weaker relationships with finishing  
• Market value is influenced by a combination of attributes rather than one single metric  

### Tools
Python, pandas, numpy, matplotlib, seaborn
