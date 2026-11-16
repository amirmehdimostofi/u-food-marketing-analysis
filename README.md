# U Food marketing analysis

Explore how U Food customers spend and respond to marketing campaigns, and which groups are most worth targeting.

## Data

`u_food_marketing.csv` has 1,843 customers, with income, household composition, spend by product category, purchase channel (web, catalog, store), campaign acceptance flags, age, and marital and education indicators.

## Method

`U Food Marketing Analysis.ipynb` is an exploratory analysis in Python (pandas). It reviews spending, campaign response, and demographics, then summarises practical targeting points.

## Findings

These points are taken from the notebook’s “Overall findings” section:

- Customers aged about 30–70 spent more, but were less likely to accept campaigns. Volume is still higher in this group.
- Catalog buyers were more likely to accept campaigns, while in-store spend was higher. The notebook recommends a channel split of about 40% catalog, 30% store, and 30% web.
- Households with no children (or fewer children) are a better focus.
- Education showed little impact on targeting.
- Marital status was not a major driver; married, single, and “together” customers spent more.
- For revenue, the notebook highlights middle-aged, higher-income customers with no children.
- For bringing in new spend through campaigns, it points to ages 21–30 and 70 and up, who accepted campaigns at a higher rate in this dataset.

## How to run

```bash
jupyter notebook "U Food Marketing Analysis.ipynb"
```
