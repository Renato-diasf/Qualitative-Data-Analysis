# Qualitative Data Analysis

This repository contains a Python-based analysis of qualitative data, focusing on demographic and educational statistics. The dataset includes information about individuals' states, gender, age, ethnicity, years of education, income, and height. The analysis involves data visualization, frequency distribution, and cross-tabulation to explore patterns and trends.

---

## Features

- **Data Loading and Exploration**: Load and inspect the dataset using `pandas`.
- **Frequency Distribution**: Analyze the distribution of categorical variables like gender, ethnicity, and years of education.
- **Cross-Tabulation**: Explore relationships between variables, such as ethnicity distribution across states or years of education by ethnicity.
- **Data Visualization**: Create bar plots, line charts, and subplots using `matplotlib` and `seaborn` to visualize insights.

---

## Dataset Overview

The dataset (`dados.csv`) contains the following columns:

- **UF**: State code.
- **Sexo**: Gender (0: Male, 1: Female).
- **Idade**: Age.
- **Cor**: Ethnicity (0: Indigenous, 2: White, 4: Black, 6: Asian, 8: Mixed, 9: Undeclared).
- **Anos de Estudo**: Years of education.
- **Renda**: Income.
- **Altura**: Height.

---

## Key Analyses

1. **Gender Distribution**:
   - Frequency and percentage distribution of males and females.
   - Visualization using bar plots.

2. **State-wise Population Distribution**:
   - Frequency and percentage distribution of individuals across states.
   - Visualization using bar plots.

3. **Years of Education Distribution**:
   - Frequency and percentage distribution of years of education.
   - Visualization using bar plots.

4. **Ethnicity Distribution**:
   - Frequency and percentage distribution of ethnicities.
   - Visualization using bar plots.

5. **Cross-Tabulation**:
   - Ethnicity distribution by state.
   - Years of education distribution by state.
   - Ethnicity distribution by years of education.
