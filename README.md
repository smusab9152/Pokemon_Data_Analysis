# Data Analytics on Deepfake and Misinformation

[![Competition](https://img.shields.io/badge/VizQuest%203.0-IIM%20Nagpur-blue)](https://www.iimnagpur.ac.in/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An in-depth analysis of deepfake and misinformation trends, submitted for the **VizQuest 3.0 Data Analytics Competition** hosted by IIM Nagpur. This project explores a comprehensive dataset to uncover patterns in content, platform engagement, and regional distribution of flagged misinformation.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Dataset Highlights](#dataset-highlights)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Key Findings](#key-findings)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Overview

This repository contains our project for the **VizQuest 3.0-IIM Nagpur Data Analytics Competition 2024**. Our analysis focuses on understanding trends, patterns, and key insights from the provided deepfake and misinformation dataset. By leveraging data wrangling, statistical analysis, and advanced visualization techniques, we aim to provide actionable insights for combating the spread of false information.

## Key Features

-   **Data Wrangling**: Comprehensive cleaning, transformation, and normalization of raw data to prepare it for analysis.
-   **Engagement Analysis**: Measurement and interpretation of likes, shares, and comments to understand user behavior patterns.
-   **Correlation Studies**: Examination of the relationships between flagged content, platforms, regions, and detection methods.
-   **Actionable Insights**: Data-driven recommendations for platforms and policymakers to combat misinformation effectively.

## Dataset Highlights

-   **Content Types**: Analysis across Text, Images, and Videos.
-   **Platforms**: Covers major social networks including WhatsApp, Facebook, Reddit, Instagram, and YouTube.
-   **Regions**: Global scope with data from Asia, Europe, Africa, Oceania, North America, and South America.
-   **Metrics**: Includes engagement metrics (likes, shares, comments), spread rates, and various detection methods.

## Technology Stack

-   **Programming Language**: Python
-   **Core Libraries**: Pandas, NumPy, Scikit-learn
-   **Data Visualization**: Matplotlib, Seaborn
-   **Dashboarding Tools**: Tableau, Power BI
-   **Analytical Techniques**:
    -   Data Normalization (Min-Max Scaling)
    -   Heatmaps, Sankey Diagrams, and Contour Plots for visualization
    -   Regression and Correlation Analysis

## Installation

To get a local copy up and running, follow these simple steps.

1.  Clone the repo
    ```sh
    git clone https://github.com/smusab9152/Data_Analytics_on_Deepfake_and_Information_Dataset.git
    ```
2.  Install required packages
    ```sh
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

## Usage

The core analysis is contained within the Jupyter notebooks.

1.  Open the notebooks in a Jupyter environment.
2.  Run the cells sequentially to reproduce the analysis.
3.  The final datasets and visualizations are saved in the `output` directory.

## Key Findings

1.  **Platform Disparities**: WhatsApp, Reddit, and Facebook show the highest volume of flagged content.
2.  **Regional Hotspots**: Asia leads in the amount of flagged content, whereas Africa reports the least.
3.  **Content Engagement**: Videos generate the highest user engagement, while text-based content is the most frequently flagged.
4.  **Detection Methods**: AI-based detection is predominant but is associated with a significant number of false positives.
5.  **Topical Trends**: Climate change and celebrity-related news are the most flagged high-impact topics.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgements

-   IIM Nagpur for organizing the VizQuest 3.0 competition.
-   All data providers and sources that made this analysis possible.
