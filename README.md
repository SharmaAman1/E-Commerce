# E-Commerce Analysis

Brief exploratory analysis and visualizations of the "Sample - Superstore" dataset using a Jupyter notebook.

## Files
- [E-Commerce/E-commerce Project.ipynb](E-Commerce/E-commerce Project.ipynb) — main analysis notebook (defines variables such as [`EcommerceProject.data`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.sales_by_Month`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.sales_by_category`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.sales_by_subcategory`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.Monthly_profit_Analysis`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.profit_by_category`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.profit_by_subcategory`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.sales_profit_by_segment`](E-Commerce/E-commerce Project.ipynb))
- [E-Commerce/Sample - Superstore.csv](E-Commerce/Sample - Superstore.csv) — source dataset (CSV)

## Overview
The notebook performs:
- Data loading and inspection (uses the `data` DataFrame).
- Date conversion and feature extraction (Order Month, Year, Day of week).
- Monthly sales and profit analyses.
- Category / Sub-category sales and profit breakdowns.
- Segment-level sales vs. profit comparison.
- Interactive visualizations via Plotly.

Referenced notebook variables: [`EcommerceProject.data`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.sales_by_Month`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.sales_by_category`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.sales_by_subcategory`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.Monthly_profit_Analysis`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.profit_by_category`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.profit_by_subcategory`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.sales_profit_by_segment`](E-Commerce/E-commerce Project.ipynb).

## Requirements
- Python 3.8+
- Jupyter / JupyterLab or VS Code with Jupyter support
- Required Python packages:
  - pandas
  - plotly

Install dependencies:
```sh
pip install pandas plotly
```

## How to run
1. Open the notebook [E-Commerce/E-commerce Project.ipynb](E-Commerce/E-commerce Project.ipynb) in VS Code or Jupyter.
2. Ensure [E-Commerce/Sample - Superstore.csv](E-Commerce/Sample - Superstore.csv) is in the same folder.
3. Run cells top-to-bottom to reproduce the analysis and visualizations.

Notes:
- The notebook reads the CSV with encoding `latin-1` to avoid encoding issues.
- Plotly figures are shown inline; VS Code's notebook viewer or Jupyter will render them interactively.

## Contact / Next steps
- Add additional analyses (geographic mapping, time-series forecasting, cohort analysis).
- Export cleaned datasets or charts if needed.

```// filepath: E-Commerce/README.md
# E-Commerce Analysis

Brief exploratory analysis and visualizations of the "Sample - Superstore" dataset using a Jupyter notebook.

## Files
- [E-Commerce/E-commerce Project.ipynb](E-Commerce/E-commerce Project.ipynb) — main analysis notebook (defines variables such as [`EcommerceProject.data`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.sales_by_Month`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.sales_by_category`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.sales_by_subcategory`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.Monthly_profit_Analysis`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.profit_by_category`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.profit_by_subcategory`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.sales_profit_by_segment`](E-Commerce/E-commerce Project.ipynb))
- [E-Commerce/Sample - Superstore.csv](E-Commerce/Sample - Superstore.csv) — source dataset (CSV)

## Overview
The notebook performs:
- Data loading and inspection (uses the `data` DataFrame).
- Date conversion and feature extraction (Order Month, Year, Day of week).
- Monthly sales and profit analyses.
- Category / Sub-category sales and profit breakdowns.
- Segment-level sales vs. profit comparison.
- Interactive visualizations via Plotly.

Referenced notebook variables: [`EcommerceProject.data`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.sales_by_Month`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.sales_by_category`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.sales_by_subcategory`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.Monthly_profit_Analysis`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.profit_by_category`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.profit_by_subcategory`](E-Commerce/E-commerce Project.ipynb), [`EcommerceProject.sales_profit_by_segment`](E-Commerce/E-commerce Project.ipynb).

## Requirements
- Python 3.8+
- Jupyter / JupyterLab or VS Code with Jupyter support
- Required Python packages:
  - pandas
  - plotly

Install dependencies:
```sh
pip install pandas plotly
```

## How to run
1. Open the notebook [E-Commerce/E-commerce Project.ipynb](E-Commerce/E-commerce Project.ipynb) in VS Code or Jupyter.
2. Ensure [E-Commerce/Sample - Superstore.csv](E-Commerce/Sample - Superstore.csv) is in the same folder.
3. Run cells top-to-bottom to reproduce the analysis and visualizations.

Notes:
- The notebook reads the CSV with encoding `latin-1` to avoid encoding issues.
- Plotly figures are shown inline; VS Code's notebook viewer or Jupyter will render them interactively.

## Contact / Next steps
- Add additional analyses (geographic mapping, time-series forecasting, cohort analysis).
- Export cleaned datasets or charts if needed.
