# Team #22 Project

## Team members
* Olga Ktytor
* Olha Zamohylna
* Sasini Munasinghe
* Yevheniia Shabalova

## Roles

## Description
This project aims to identify relationships between weekly sales and various factors using the Walmart dataset. We will explore how the following variables impact weekly sales:

Temperature
CPI
Unemployment Rate
Fuel Price
IsHoliday (whether the week is a special holiday week)
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
2. What impact does store size have on sales performance?
3. Is there a correlation between unemployment rate and sales?
4. How do holidays influence weekly sales patterns?
5. How do fuel prices impact weekly sales?

## Rules of engagement

- Regular updates
- Deadlines
- Support and asking for help when it is needed
- Visibility (Task logging on the Board)
- Feedback

## Conclusions

**Analysis of Relationship Between Weekly Sales and Fuel Prices**

From the model results, we can conclude that fuel prices do not have a statistically significant relationship with weekly sales. 
The R-squared score is very close to 0, which suggests that the independent variable does not significantly predict or explain the weekly sales based on the linear relationship we modelled. The p-value is 0.448, which is greater than the typical significance level of 0.05, so we can see that the model as a whole is not statistically significant. 
Therefore, other factors may be necessary to effectively predict weekly prices at Walmart stores.

## Suggestions

**Analysis of Relationship Between Weekly Sales and Fuel Prices**

Although, a fuel price may not directly impact sales, it could indirectly affect consumer behaviour in other ways. For instance, changes in fuel prices might influence consumer spending patterns or shopping frequency. Monitoring these behaviors could provide insights into how to adjust operations or marketing efforts accordingly.
Also, change in marketing strategies and product assortment, as well as new promotions, and customer experience improvements can help enhance sales performance.


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

