# Make Learning Visible: Soccer Scouting Predictive Model

## 📌 Project Overview
This project utilizes machine learning to evaluate and predict professional soccer player performance, identifying optimal scouting targets. The goal is to provide data-driven insights into recruitment viability. 

You can view the full presentation of the findings here: https://github.com/jonahduffy/soccer-scouting-player-predictive-machine-learning-model/blob/main/MLV%20Presentation%20-%20A.I.%20in%20Scouting.pdf 

## 🛠️ Tools & Technologies
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib/Seaborn
* **Techniques:** Data Cleansing, Feature Engineering, Predictive Modeling

## 📂 Repository Contents
* `MLVpythoncode.ipynb`: The main notebook containing the data pipeline and machine learning model.
* `MLV Presentation - A.I. in Scouting.pdf`: The slide deck summarizing methodologies and business insights.
* `players_data-2024-2025.csv`: The underlying player statistics dataset.

## 📈 Key Findings
* The K-Nearest Neighbors (KNN) algorithm successfully identified undervalued talent by evaluating approximately 3,000 players across 14 distinct performance metrics.
* When using Erling Haaland (valued at $180 million) as the target player, the model identified Serhou Guirassy as a 78.9% statistical twin.
* Despite playing for different teams, the model found nearly an 80% like-for-like statistical replacement in key metrics (such as expected goals, shot-creating actions, and progressive carries) for roughly 20% of the market cost.
* The results demonstrate that an unsupervised machine learning algorithm can effectively bypass traditional human scouting biases to find top-tier performance metrics in overlooked markets.
