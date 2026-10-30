# Electric-Vehicle-Market-Entry-Consumer-Preference-Study


## Project Overview

This project investigates the pricing challenges and consumer willingness to pay for premium electric vehicles (EVs) in the Indian market. It focuses on how customers evaluate competing EV brands, battery range, and vehicle prices when considering a purchase.

The study uses conjoint analysis and regression analysis to explore the trade-offs consumers make between product attributes and to estimate which vehicle profiles are more appealing.

The project was completed as part of the MBA – Data Science programme at FHM Berlin.

## Business Problem

The Indian electric vehicle market has growth potential, but premium EV adoption can be affected by factors such as:

- High upfront vehicle prices.
- Differences in brand reputation and customer trust.
- Battery range and perceived convenience.
- The availability and maturity of charging infrastructure.

For a new or expanding market entrant such as Tesla, understanding how customers value these factors is important when developing a competitive pricing and market-entry strategy.

## Research Question

**What price will customers accept for a new premium electric vehicle, such as Tesla, compared with existing competitors in the Indian market?**

## Project Objectives

- Explore consumer preferences for premium electric vehicles in India.
- Compare selected EV brands and models.
- Understand the influence of battery range and ex-showroom price on customer preferences.
- Estimate the relative utility of different product profiles.
- Use the results to discuss potential pricing and positioning decisions.

## Attributes and Levels

The conjoint study evaluates three product attributes:

| Attribute | Levels |
|---|---|
| Brand and model | Tesla Model Y, Volvo EX60, BMW iX7 |
| Battery range | 622 km, 656 km, 700 km |
| Ex-showroom price | €70,999, €74,999, €78,999 |

*Note: The vehicle models, specifications and prices are the alternatives used in this academic research exercise. They should not be interpreted as verified current Indian-market specifications or retail prices.*

## Research Methodology

The project follows a quantitative research approach.

1. **Problem identification:** Defined the challenge of premium EV market entry and pricing in India.
2. **Literature review:** Reviewed relevant research on the Indian EV market, consumer preferences, pricing and adoption challenges.
3. **Research design:** Considered alternative study designs and selected a survey-based approach supported by experimental choice modelling.
4. **Sampling:** Used convenience sampling to reach accessible respondents.
5. **Survey design:** Created product profiles using three attributes and their respective levels.
6. **Data collection:** Collected respondent evaluations through an online survey.
7. **Data preparation:** Converted categorical product attributes into binary/dummy variables for analysis.
8. **Statistical analysis:** Used Excel regression output and conjoint part-worth utilities to examine preferences.
9. **Interpretation:** Compared baseline and alternative product profiles and discussed their implications for pricing and positioning.

## Tools and Techniques

- **Microsoft Excel:** Data organization, dummy-variable preparation, regression analysis, utility calculations and charts.
- **Google Forms:** Survey creation and response collection.
- **Conjoint analysis:** Evaluation of consumer trade-offs across brand, battery range and price.
- **Multiple regression:** Examination of the relationship between product attributes and survey ratings.
- **Data visualization:** Presentation of part-worth utilities and attribute importance.

## Key Analysis and Findings

The workbook includes the following analytical components:

- Raw survey response data and adjusted data using dummy variables.
- Regression output and an interpretation of the model statistics.
- Part-worth utility estimates for the selected attribute levels.
- A comparison of baseline and ideal product profiles.
- Utility-based predictions for three alternative EV product profiles.
- Charts showing part-worth utilities and relative attribute importance.

### Illustrative utility comparison

The workbook reports the following profile utilities:

| Product profile | Estimated utility |
|---|---:|
| Baseline: Volvo EX60, 656 km, €78,999 | 4.01 |
| Ideal profile: Volvo EX60, 656 km, €70,999 | 4.23 |
| Tesla Model Y, 700 km, €70,999 | 3.81 |
| Volvo EX60, 622 km, €74,999 | 3.98 |
| BMW iX7, 656 km, €70,999 | 3.89 |

Within the model, the ideal profile combines the Volvo EX60 with a 656 km range and the lower price level. The comparison illustrates how a price reduction can improve the estimated utility of a product profile.

The workbook's part-worth table also indicates that brand/model has the largest reported utility range among the three attributes, followed by price and battery range. This suggests that brand perception may be an important consideration in the profiles evaluated.

**Important interpretation note:** These are outputs from the project workbook and should be treated as exploratory results from the collected survey data, not as representative estimates of the entire Indian EV market. The reported regression fit is low (the workbook reports an R-squared of approximately 0.04–0.05), so the model explains only a small proportion of variation in survey ratings. The findings should therefore be interpreted cautiously.

## Business Implications

The analysis provides several considerations for an EV company planning to enter or expand in the Indian premium market:

- **Brand positioning matters:** Brand familiarity and trust may influence customer preferences alongside technical specifications.
- **Pricing needs careful consideration:** A more competitive price can improve a product profile's estimated attractiveness.
- **Range should be evaluated with price:** Customers may assess battery range in relation to the overall cost rather than as an isolated feature.
- **Customer research is valuable:** Companies should validate pricing and product positioning with larger and more representative samples before making market decisions.

## Project Structure

The main project file is:

```text
├── README.md
└── Pradyumna Urkude Final Project GTM-13.xlsx
```

The Excel workbook is organized into sections covering:

- Problem identification and literature review
- Research question and study design
- Sampling design and conjoint attributes
- Experimental design and survey form
- Raw and adjusted survey data
- Regression output and interpretation
- Baseline and ideal product profiles
- Charts and consumer-choice predictions

## Limitations

- Convenience sampling may introduce selection bias.
- The sample may not represent the diversity of Indian EV buyers.
- The low reported R-squared indicates limited explanatory power in the regression model.
- Survey-based preferences may differ from actual purchasing behaviour.
- The model considers only three attributes; factors such as charging access, maintenance costs, incentives, resale value and after-sales service are not fully represented.
- The vehicle prices and specifications are research input levels, not verified current market quotations.

## Future Improvements

- Collect a larger and more diverse sample across Indian cities and income groups.
- Include additional attributes such as charging infrastructure, maintenance cost, warranty and government incentives.
- Improve the statistical model and validate it using a separate dataset.
- Compare stated preferences with real purchase behaviour where data is available.
- Extend the analysis using Python, SQL and Power BI for reproducible analysis and interactive reporting.

## Author

**Pradyumna Urkude**  
MBA – Data Science  
FHM Berlin

---

*Academic research project exploring consumer preferences and pricing considerations for premium electric vehicles in India.*
