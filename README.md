<h1 align="center">🏏 IPL Match & Performance Analysis</h1>

<p align="center">
  <b>A Data-Driven Study of Indian Premier League Matches Using Data Science</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-green?style=for-the-badge&logo=pandas" />
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-orange?style=for-the-badge&logo=numpy" />
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Plots-purple?style=for-the-badge" />
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
This project performs a comprehensive analysis of the Indian Premier League (IPL)
using match-level and ball-by-ball datasets. The objective is to uncover
meaningful insights related to batting performance, bowling efficiency,
toss impact, venue influence, seasonal trends, and death-over performance.
</p>

<p>
The project applies Data Science techniques such as:
</p>

<ul>
  <li>Data Cleaning</li>
  <li>Data Wrangling</li>
  <li>Feature Engineering</li>
  <li>Statistical Analysis</li>
  <li>Data Visualization</li>
  <li>Pattern Discovery</li>
</ul>

<hr>

<h2>🎯 Objectives</h2>

<ul>
  <li>Analyze batting and bowling performance across IPL seasons.</li>
  <li>Identify the top run scorers and most economical bowlers.</li>
  <li>Understand the impact of toss decisions on match outcomes.</li>
  <li>Study seasonal scoring trends in IPL.</li>
  <li>Evaluate venue-based winning patterns.</li>
  <li>Analyze death-over performance of IPL teams.</li>
</ul>

<hr>

<h2>📂 Dataset Information</h2>

<h3>1️⃣ matches.csv</h3>

<p>Contains match-level information:</p>

<ul>
  <li>Season</li>
  <li>Date</li>
  <li>Venue</li>
  <li>Toss Winner</li>
  <li>Toss Decision</li>
  <li>Winner</li>
  <li>Player of Match</li>
</ul>

<h3>2️⃣ deliveries.csv</h3>

<p>Contains ball-by-ball information:</p>

<ul>
  <li>Batter</li>
  <li>Bowler</li>
  <li>Runs Scored</li>
  <li>Extras</li>
  <li>Wickets</li>
  <li>Dismissal Type</li>
</ul>

<hr>

<h2>⚙️ Technologies Used</h2>

<ul>
  <li><b>Python</b></li>
  <li><b>Pandas</b></li>
  <li><b>NumPy</b></li>
  <li><b>Matplotlib</b></li>
  <li><b>Seaborn</b></li>
  <li><b>Jupyter Notebook</b></li>
</ul>

<hr>

<h2>🔄 Project Workflow</h2>

<h3>Phase 1 — Data Loading & Understanding</h3>

<ul>
  <li>Loaded IPL datasets</li>
  <li>Inspected dataset structure</li>
  <li>Analyzed data types and missing values</li>
</ul>

<h3>Phase 2 — Data Cleaning</h3>

<ul>
  <li>Handled missing values</li>
  <li>Checked duplicates</li>
  <li>Validated cricket-specific columns</li>
</ul>

<h3>Phase 3 — Feature Engineering</h3>

<ul>
  <li>Created Total Runs feature</li>
  <li>Created Boundary Classification</li>
  <li>Created Over Phase Classification</li>
  <li>Extracted Year and Month features</li>
</ul>

<h3>Phase 4 — Statistical Analysis</h3>

<ul>
  <li>Top 5 Run Scorers</li>
  <li>Bowler Economy Analysis</li>
  <li>Season-wise Win Percentage Analysis</li>
</ul>

<h3>Phase 5 — Visualization & Pattern Discovery</h3>

<ul>
  <li>Toss Impact Analysis</li>
  <li>Top Run Scorers</li>
  <li>Dismissal Pattern Analysis</li>
  <li>Seasonal Batting Trends</li>
  <li>Venue Analysis</li>
  <li>Death Over Analysis</li>
</ul>

<hr>

<h2>📊 Key Findings</h2>

<ul>
  <li>🏏 Virat Kohli emerged as the highest run scorer.</li>
  <li>🎯 Anil Kumble was among the most economical bowlers.</li>
  <li>📈 IPL scoring rates have increased over time.</li>
  <li>🏟️ Certain venues demonstrate strong home advantage.</li>
  <li>⚡ Death-over performance significantly impacts match outcomes.</li>
  <li>🎲 Teams choosing to field first often achieve better results.</li>
</ul>

<hr>

<h2>📈 Visualizations Included</h2>

<ul>
  <li>Toss Impact Bar Chart</li>
  <li>Top 10 Run Scorers Chart</li>
  <li>Dismissal Pattern Analysis</li>
  <li>Seasonal Batting Trend Plot</li>
  <li>Regression Trend Analysis</li>
  <li>Venue Heatmap</li>
  <li>Death Over Performance Box Plot</li>
</ul>

<hr>

<h2>💡 Strategic Recommendation</h2>

<p>
Based on the analysis, teams should prioritize chasing whenever pitch
conditions are stable. Additionally, investment in specialist death-over
batters and bowlers can significantly improve match-winning probability.
</p>

<hr>

<h2>📁 Project Structure</h2>

<pre>
IPL_Match_Performance_Analysis/
│
├── matches.csv.xls
├── deliveries.csv.xls
│
├── IPL_Analysis.ipynb
│
├── IPL_Final_Report.docx
│
├── README.md
│
└── images/
    ├── toss_impact.png
    ├── top_batsmen.png
    ├── venue_analysis.png
    └── death_over_analysis.png
</pre>

<hr>

<h2>🏆 Conclusion</h2>

<p>
This project demonstrates how Data Science techniques can transform raw cricket
data into actionable insights. By combining data cleaning, feature engineering,
statistical analysis, and visualization, meaningful trends in player performance,
team strategy, and match outcomes were successfully identified.
</p>

<hr>

<p align="center">
  ⭐ If you found this project useful, consider giving it a star!
</p>

<p align="center">
  Made with ❤️ by <b>Aryan Dhiman</b>
</p>
