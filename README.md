# Analyzing U.S. Agriculture Imports and Exports with Mexico and Canada: Empowering Consumers to Make Informed Food Purchases

## Business Problem

Presidential changes bring about new policies and economic outlooks. Recently, tariffs have been a significant topic of discussion. This project aims to analyze imports and exports of crops specifically with Mexico and Canada over the past decade. By tracking and presenting this data in an easily understandable format, the goal is to enable the average grocery store shopper to understand the implications of trade policies and make informed choices regarding their food purchases.

## Datasets

- **US Food Imports Dataset**: Lists countries around the world, in categories, subcategories, commodities, values, and years for imports to the United States. For this project, Mexico and Canada were separated and analyzed as two separate datasets.
- **USDA Economic Research Service’s Foreign Agriculture Trade Dataset**: Filtered separately for Mexico and Canada to analyze top categories of imports from the U.S.

## Methods

- Summarized trade trends, identified patterns and changes over time.
- Assessed trade volumes and prices.
- Evaluated U.S. market share in key import and export markets.
- Visualized data using line charts and bar graphs.
- Utilized logistic websites and government websites for additional context.
- Applied SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous regressor) model to forecast future import values for top commodities.

## Analysis

### Imports from Mexico

- Top 3 imports: fruits, vegetables, beverages.
- Fruit imports: $11.2 billion, mainly fresh fruits like avocados, mangos, citrus, grapes.
- Vegetable imports: $9.8 billion, mainly fresh vegetables like tomatoes, garlic, onions.
- Beverages: $6.7 billion, mainly malt beer and liquors.
- Forecasted future values using SARIMAX model, indicating a positive increase.

### Imports from Canada

- Top 3 imports: grains, meats, fish.
- Grain imports: $19 billion, mainly cereals and bakery goods.
- Meat imports: $8.5 billion, mainly fresh or chilled red meats.
- Fish imports: $7 billion, mainly salmon, shrimp, lobster.
- Forecasted future values using SARIMAX model, indicating a slight positive trend.

### Exports to Mexico

- Top 3 exports: corn, wheat, sorghum.
- Corn exports: 24.5 million metric tons, $5.3 billion.
- Wheat exports: approximately 3.5 million metric tons.
- Sorghum exports: ceased.

### Exports to Canada

- Top 3 exports: corn, wheat, milled rice.
- Corn exports: 2.7 million metric tons, $671 million.
- Wheat exports: 300,000 metric tons.
- Milled rice exports: ceased in 2023.

## Assumptions

- The datasets are assumed to be representative of current market conditions.
- Merging datasets is assumed to return all locations.
- Market trends will continue consistently despite unforeseen disruptions.

## Limitations

- Analysis based on historical data may not fully predict future trends.
- Real estate markets can vary significantly within states, leading to misrepresentations.
- Missing information may impact analysis.
- Economic downturns, policy changes, and natural disasters are not accounted for.

## Challenges

- Merging datasets can lead to compatibility issues.
- Balancing model complexity with deviations at higher yields.
- Rapidly changing market conditions can impact accuracy and relevance.
