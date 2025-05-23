# AI Workforce Disparity Analysis
## Project Overview

This project examines the intersection of artificial intelligence adoption and workforce equity by analyzing millions of AI conversations alongside demographic employment data. Through comprehensive data analysis and visualization, the project reveals concerning patterns about which workers and ethnic groups are benefiting from AI tools versus those at risk of being left behind in the technological revolution.

## Tools & Packages Used

- **Python** and **pandas** for data processing and merging
- **Matplotlib** and **Seaborn** for statistical analysis and visualization
- **NumPy** for numerical computations
- **Jupyter Notebook** for exploratory data analysis
- **HTML/CSS** for web presentation and responsive design
- **Git** for version control and project management

## Data Collection & Processing

### Datasets
The analysis centered on three key datasets: Anthropic's Economic Index data containing task mappings from millions of Claude AI conversations, the U.S. Bureau of Labor Statistics Tables 8 and 18 (May 2023) providing occupational employment and earnings data by ethnicity, and the O*NET database offering detailed occupational classifications and task descriptions. The Anthropic data reveals which economic tasks are being performed with AI assistance, while the BLS data provides crucial demographic context about workforce composition across different occupations.

### Further Analysis
Using data merging and cross-tabulation techniques, I created unified occupational categories that could be analyzed across both AI usage patterns and demographic distributions. This involved mapping O*NET Standard Occupational Classification (SOC) codes to both the AI conversation data and BLS employment statistics, scaling percentages appropriately to reflect realistic conversation volumes, and developing income bracket classifications to examine disparities across economic levels.

## Visualizations

1. **Top Occupations by AI Usage Chart**: A horizontal bar chart showing which specific job titles have the highest AI adoption rates, revealing the dominance of technical professions like computer programming and web development.

2. **AI Usage by Major Occupational Groups**: A bar chart displaying AI adoption across broad occupational categories, showing Computer and Mathematical fields leading with nearly 8% of conversations.

3. **AI Usage by Income Level and Ethnicity**: A grouped bar chart examining the intersection of income and race in AI adoption, revealing persistent disparities across all economic levels.

4. **Ethnic Distribution by Occupation Category**: A stacked horizontal bar chart showing workforce composition across different professional fields, highlighting varying levels of diversity.

## Key Findings

- **Technical professions dominate AI usage**: Computer programmers, web developers, and software engineers account for a disproportionate share of AI conversations relative to their workforce size
- **Persistent racial disparities**: White workers consistently show higher AI usage rates than non-white workers across all income levels, suggesting barriers beyond economic factors
- **Income correlation with access**: Higher-earning occupations demonstrate greater AI adoption, potentially compounding existing economic advantages
- **Occupational segregation patterns**: Fields with the highest AI usage tend to be less ethnically diverse, while more diverse professions show minimal AI integration

## Implementation

The analysis combines quantitative data processing with clear visual storytelling to communicate complex workforce patterns. All charts were designed with accessibility in mind, using colorblind-friendly palettes and clear labeling. The accompanying web article presents findings in journalistic format to reach broader audiences beyond academic circles.

## Limitations

- The AI conversation data represents current usage among those already accessing advanced AI tools, potentially missing communities with limited technological access
- BLS employment data relies on self-reported racial and ethnic identification, which can be nuanced and imperfect
- The analysis reflects patterns from May 2023 and may not capture rapidly evolving AI adoption trends
- Occupational mapping between different classification systems required approximations that may introduce minor inaccuracies
- The study cannot establish causation, only correlation, between demographic factors and AI usage patterns

## About
Project 2 of my Data Studio class, examining economic and social implications of AI technology adoption across diverse workforce populations.

## Data Sources
- [Anthropic Economic Index](https://github.com/anthropics/economic-index) - AI task mapping and conversation analysis
- [Bureau of Labor Statistics Table 8](https://www.bls.gov/cps/cpsaat08.htm) - Occupations by ethnicity (May 2023)
- [Bureau of Labor Statistics Table 18](https://www.bls.gov/cps/cpsaat18.htm) - Earnings by ethnicity (May 2023)
- [O*NET Database](https://www.onetonline.org/) - Occupational classifications and task descriptions
