# Pokemon Data Analysis
This repository explores and analyzes a dataset of Pokémon attributes. The analysis includes data cleaning, exploratory data analysis (EDA), and visualizations to derive insights about Pokémon characteristics across generations and types.

## Overview
This project provides a comprehensive analysis of Pokémon data, focusing on:
- Statistical comparisons across generations
- Type-based performance analysis
- Legendary vs. non-Legendary Pokémon statistics
- Distribution and frequency of types and type combinations
- Correlations among key attributes
All analysis is performed in a Jupyter Notebook using Python libraries such as pandas, numpy, and matplotlib.

## Analysis Questions
The notebook addresses the following questions:
- **General Analysis**
  - How do the average stats (HP, Attack, Defense, Sp. Atk, Sp. Def, Speed) compare across generations?
  - Which Pokémon type has the highest and lowest average Attack stat?
  - Is there a significant difference in total stats between Legendary and non-Legendary Pokémon?
  - What is the distribution of Pokémon types and combinations?
- **Comparative and Relationship Analysis**
  - Is there a correlation between Speed and Attack?
  - How do stats compare between dual-type and single-type Pokémon?
  - Which Pokémon has the highest stat in each category?
- **Specific Analysis**
  - How many Pokémon are present in each generation?
  - What is the most common type combination?
  - How do average stats vary among Pokémon types?

## Dataset
The dataset (`pokemon_data.csv`) contains 800 Pokémon and the following attributes:
- Number, Name, Type 1, Type 2
- HP, Attack, Defense, Sp. Atk, Sp. Def, Speed
- Generation, Legendary status

## Project Structure
```
Pokemon_Data_Analysis/
│
├── Pokemon_Data_Analysis.ipynb  # Main analysis notebook
├── pokemon_data.csv             # Dataset file
└── README.md                    # Project documentation
```

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/smusab9152/Pokemon_Data_Analysis.git
   ```

2. **Install dependencies**
   - Python 3.x
   - Jupyter Notebook
   - pandas, numpy, matplotlib

   Install with pip:
   ```bash
   pip install pandas numpy matplotlib
   ```

3. **Open the notebook**
   ```bash
   jupyter notebook Pokemon_Data_Analysis.ipynb
   ```

## Key Insights

Some of the results from the analysis include:
- **Generational Stats:** Average stats vary across generations, with certain generations showing higher HP or Attack.
- **Type Analysis:** Dragon-type Pokémon have the highest average Attack; Bug-type Pokémon have the lowest.
- **Legendary Comparison:** Legendary Pokémon have significantly higher stats compared to non-Legendaries.
- **Type Frequency:** Water and Normal types are the most common; Flying and Fairy are among the least.
- **Stat Leaders:** Pokémon like Blissey, Mewtwo (Mega forms), and Deoxys hold records for highest individual stats.


## License

This project is licensed under the MIT License.
