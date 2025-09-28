# Pokémon Data Analysis 📊
An exploratory data analysis (EDA) project on the classic Pokémon dataset. This repository contains a Jupyter Notebook that dives into the world of Pokémon, uncovering insights and patterns through data visualization and statistical analysis.

## About The Project
The goal of this project is to explore the characteristics of Pokémon from the first 6 generations. By analyzing their stats, types, and other attributes, we aim to answer questions like:
- What are the most common Pokémon types?
- Who are the strongest Pokémon based on their total stats?
- Is there a correlation between different stats (e.g., Attack and Defense)?
- How do Legendary Pokémon differ from regular ones?
- What is the distribution of stats like HP, Attack, Defense, etc.?

## Key Analysis & Visualizations
The analysis is performed in the Pokemon_Analysis.ipynb Jupyter Notebook and includes:
- Data Cleaning and Preprocessing: Handling missing values and preparing the data for analysis.
- Type Distribution: Visualizing the frequency of each Pokémon type (Primary and Secondary).
- Stat Distribution: Histograms and box plots to show the distribution of core stats (HP, Attack, Defense, Sp. Atk, Sp. Def, Speed).
- Strongest Pokémon: Identifying the top Pokémon by their "Total" stat value.
- Correlation Matrix: A heatmap to visualize the relationships between different numerical stats.
- Legendary vs. Non-Legendary: Comparing the stat distributions between Legendary and non-Legendary Pokémon to see what sets them apart.

## Dataset
This analysis uses the "Pokemon with stats" dataset, which is a popular dataset for beginners in data science. It contains information on 800 Pokémon, including:
- `Name`: The name of the Pokémon.
- `Type 1 & Type 2`: The primary and secondary elemental types.
- `Stats`: HP, Attack, Defense, Special Attack, Special Defense, and Speed.
- `Total`: The sum of all base stats.
- `Generation`: The generation number the Pokémon was introduced in.
- `Legendary`: A boolean indicating if the Pokémon is Legendary.
  
## 🛠️ Getting Started
To run this analysis on your local machine, follow these steps.

### Prerequisites
Ensure you have Python 3 and pip installed.

#### Installation

Clone the repository:
```bash
git clone [https://github.com/smusab9152/Pokemon_Data_Analysis.git]
```
Navigate to the project directory:
```bash
cd Pokemon_Data_Analysis
```
Install the required libraries:
(It is recommended to use a virtual environment.)
```bash
pip install pandas numpy matplotlib seaborn jupyterlab
```
Launch Jupyter:
```bash
jupyter lab
```
This will open a new tab in your browser. You can then open and run the Pokemon_Analysis.ipynb notebook.

## Tools & Libraries Used
- Python
- Jupyter Notebook
- Pandas: For data manipulation and analysis.
- NumPy: For numerical operations.
- Matplotlib & Seaborn: For creating insightful data visualizations.
