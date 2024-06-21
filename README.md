# Team #22 Project

## Team members & Roles
* Olga Ktytor - Data Analyst
* Olha Zamohylna - Data Analyst
* Sasini Munasinghe - Data Analyst
* Yevheniia Shabalova - Data Analyst

## Description
This project aims to identify relationships between weekly sales and various factors using the Walmart dataset. We will explore how the following variables impact weekly sales:

* Temperature
* CPI
* Unemployment Rate
* Fuel Price
* IsHoliday (whether the week is a special holiday week)

Our goal is to analyze these factors comprehensively and derive insights that could potentially help optimize sales strategies and operations.


## Decision-Making and Collaboration

**How will you select your dataset?** - We collectively decided to use the Walmart dataset due to its relevance to retail sales and availability of diverse variables that could impact sales performance.

**How will you make sure all team members can contribute to the project?** - we established regular syncs in our chat and also regular meetings within live sessions.

**How will you make decisions?** - Decisions are made through consensus during team meetings. We prioritize open communication and value input from all members to ensure well-informed and collaborative decisions.

**What is the question you're trying to answer through your data analysis?** - The primary question we aim to answer through our data analysis is: "What factors most significantly influence weekly sales at Walmart?"

**What tasks need to be completed to get to your final output?** - Tasks have been allocated based on our expertise. These include data cleaning, exploratory data analysis, model selection, and interpretation of results.

**What is the primary focus within the dataset?** - The primary focus within the dataset is to understand the relationships between various predictor variables (like temperature, CPI, unemployment rate, fuel price, and holidays) and weekly sales.

**What are potential relationships in the data that you could explore?** - Potential relationships we aim to explore include how changes in temperature, economic indicators (like unemployment rate and fuel price), and holiday seasons impact weekly sales.

**What are key questions your project could answer?** - 

Key questions our project aims to answer include:

1. How does temperature affect weekly sales?
2. What impact does prevailing consumer price index (CPI) have on sales performance?
3. Is there a correlation between unemployment rate and sales?
4. How do holidays influence weekly sales patterns?
5. How does fuel price affect weekly sales?

## Rules of engagement

- Regular updates
- Deadlines
- Support and asking for help when it is needed
- Visibility (Task logging on the Board)
- Feedback

## Conclusions

**Analysis of temperature impact on weekly sales**

Overall, OLS regression results shows that temperature has a statistically significant but weak relationship with weekly sales.

Significance of Variables: Both the intercept and the temperature coefficient are statistically significant, as indicated by their p-values (both are < 0.05).

Effect Size: The negative coefficient for Temperature suggests that higher temperatures are associated with lower weekly sales. For each one-degree increase in Temperature, weekly sales decreases by approximately 1493 units, on average.

Model Fit: The very low R-squared value (both on training and test data) indicates that temperature explains only a very small fraction of the variance in weekly sales. This suggests that other factors not included in the model might be more important in predicting weekly sales.

## Suggestions

1. Exploring Additional Variables (seasonality, competitor activity, store characteristics, customer segments,  etc.)
2. Targeted Promotions: Use the insights to plan promotions and marketing campaigns more effectively. For example, if certain products sell better at specific temperatures, target promotions accordingly.
3. Inventory Management: Adjust inventory levels based on temperature forecasts to ensure adequate stock of weather-sensitive items.
4. Staffing Adjustments: Plan staffing levels according to expected sales patterns influenced by weather conditions and other factors.

## Video recordings

## Repository
https://github.com/yevheniia-shabalova/team_project

## Link to the Board
https://github.com/users/yevheniia-shabalova/projects/1/views/1


## Links to the video recordings

## Folder Structure

### Project 1
```markdown
|-- data
|---- processed
|---- raw
|---- sql
|-- reports
|-- src
|-- README.md
|-- .gitignore
```

### Project 2
```markdown
|-- data
|---- processed
|---- raw
|---- sql
|-- experiments
|-- models
|-- reports
|-- src
|-- README.md
|-- .gitignore
```

* **Data:** Contains the raw, processed and final data. For any data living in a database, make sure to export the tables out into the `sql` folder, so it can be used by anyone else.
* **Experiments:** A folder for experiments
* **Models:** A folder containing trained models or model predictions
* **Reports:** Generated HTML, PDF etc. of your report
* **src:** Project source code
* README: This file!
* .gitignore: Files to exclude from this folder, specified by the Technical Facilitator

