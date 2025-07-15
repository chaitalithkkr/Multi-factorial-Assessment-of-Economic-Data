# Multi-factorial Assessment of Economic Data
This project explores how various economic indicators, like minimum wage, interest rates, inflation, housing prices, and employment rates, interact with each other. The goal is to better understand the ripple effects of policy decisions in a real-world, data-driven context.

## Project Overview

Economic policies aren’t made in isolation, and their impacts rarely follow a straight line. With this analysis, I wanted to uncover how interconnected factors shape the economy over time, especially in the context of minimum wage changes. The study pulls in a wide range of indicators to build a more holistic view of macroeconomic dynamics.

**Core questions explored:**
- What’s the relationship between minimum wage and employment, housing, or inflation?
- How do interest rate changes influence broader economic stability?
- Can we find patterns that inform better policy decisions?

## Methodology

**Data Sourcing & Preprocessing**  
Collected public data from government and research sources. Cleaned and explored it using correlation maps, scatter plots, and summary statistics to get a clear initial view.

**Modeling Approach**  
Tried out multiple models—Linear Regression, Random Forest, Lasso, Ridge—with cross-validation.  
Linear Regression stood out for its performance in this case (lowest mean squared error).

**Time Series Analysis**  
Used time-based visualizations to track trends and policy impacts across decades.

**Multicollinearity Handling**  
Dropped highly correlated variables (like StateMinimumWage and FederalMinimumWage) to avoid redundancy and improve model clarity.

## Key Insights

- Interest rate hikes often precede a drop in unemployment—supporting some classic economic theories.
- Inflation (CPI) has been steadily rising despite GDP growth, pointing to underlying imbalances.
- Minimum wage increases don't always cause immediate housing or employment shifts, suggesting other mediating variables are at play.

## Why This Project

A lot of economic analysis focuses on isolated variables. This project leans into the complexity, looking across multiple dimensions at once to offer a fuller picture. The goal wasn’t to prove a single point, but to uncover relationships that might otherwise be missed.

---

If you’d like to dive deeper or explore the code, feel free to reach out or fork the repo. Always open to feedback and collaborations.
