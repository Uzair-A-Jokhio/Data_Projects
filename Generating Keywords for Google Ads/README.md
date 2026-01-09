# Generating Keywords for Google Ads

This project is a prototype for generating a set of targeted keywords for a Google Ads campaign. The scenario is for a digital marketing agency working with a massive online furniture retailer.

## Project Brief

The client is a low-cost furniture retailer and wants to create search campaigns for their sofas section. The target audience is price-sensitive customers.

### Products
- Sofas
- Convertible sofas
- Love seats
- Recliners
- Sofa beds

### Campaign Goals
- Focus on keywords related to low cost, promotions, and discounts.
- Avoid luxury-related keywords.
- Use 'Exact' and 'Phrase' match types for keywords to maintain a tight budget.

## Process

The notebook `notebook.ipynb` implements a script to:
1. Define a list of products.
2. Define a list of words that are relevant to the target audience (e.g., 'buy', 'prices', 'cheap', 'discount').
3. Combine the product list and the word list to generate a comprehensive list of keywords.
4. Structure the output into a pandas DataFrame with the following columns: 'Campaign', 'Ad Group', 'Keyword', and 'Criterion Type'.

## Dependencies
- `pandas`

## Usage
Open and run the `notebook.ipynb` in a Jupyter environment to see the keyword generation process.
