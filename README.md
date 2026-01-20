# Fortune Company Financial Analysis
Statistical analysis of Fortune 500/1000 company data (2023-2024) examining relationships between financial metrics and market capitalization.

## Overview
This project analyzes Fortune magazine's largest American companies by revenue, exploring how profits, revenue, assets, and economic sector relate to market value. The analysis uses linear regression modeling on data from 2023 (top 1000) and 2024 (top 500) Fortune lists.

## Key Features
- Data wrangling and cleaning of Fortune 2023 and 2024 datasets
- Classification of companies into four economic sectors (primary, secondary, tertiary, quaternary)
- Visual exploration of revenue distribution, CEO demographics, and financial relationships
- Linear regression modeling to predict market capitalization
- Model assumption checking and validation
- Market value prediction with confidence intervals

## Technologies Used
- R Markdown
- Libraries: tidyverse, ggplot2, knitr, kableExtra, gridExtra, flextable, bookdown

## Key Findings
- Linear model explains ~44-47% of variance in market capitalization
- Economic sector (particularly quaternary/technology) is a strong predictor
- Assets and revenue show significant positive relationships with market value
- Employment increased across most sectors from 2023 to 2024
- Female CEO representation remained low (~10%)
