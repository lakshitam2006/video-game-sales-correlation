# Global Video Game Market Correlation Analysis

## Project Overview
This data analytics project evaluates historical sales records for over 16,000 video games to identify regional consumer purchasing trends and market drivers. By applying various statistical correlation methods (Pearson, Spearman, Kendall) and data visualization techniques in Python, this analysis maps out how regional distribution channels interact with overall global success.

## Core Analytical Steps Taken
- **Data Cleansing & Type Integrity**: Handled structural missing values within chronological records and normalized decimal metrics into production-ready integer data types using Pandas.
- **Outlier Detection**: Utilized boxplot visualization to isolate high-impact market outliers (blockbuster titles like *Wii Sports*) and established a professional business framework for keeping them within the study scope.
- **Multi-Method Correlation Evaluation**: Computed Pearson linear metrics alongside Spearman/Kendall rank order coefficients to ensure calculations remained robust against extreme hit-driven data skewing.
- **Data Visualization**: Designed clear, custom Seaborn heatmaps and regression plots to simplify complex trend vectors for non-technical stakeholders.

## Key Business Insights
1. **Western Market Primacy**: North American (`NA_Sales`) and European (`EU_Sales`) market numbers display a powerful positive linear correlation (~0.94) with total worldwide performance, serving as definitive indicators for global project scaling.
2. **Japanese Market Divergence**: The Japanese sector (`JP_Sales`) exhibits a significantly lower correlation profile (~0.61) relative to Western trends. This underscores distinct, localized consumer preferences (such as long-term historical shifts toward handheld or specific regional genres) that require unique corporate distribution strategies instead of an automated global launch.
