# Stock Data Analysis — Jupyter Notebooks

## Included files

- `Stock_Data_Analysis_Questions_1_to_6.ipynb` — complete notebook covering Questions 1–6.
- `Question_3_GME_Stock_Data.ipynb` — standalone notebook for Question 3.
- `Question_4_GME_Revenue_Web_Scraping.ipynb` — standalone notebook for Question 4.
- `Question_5_Tesla_Stock_Graph.ipynb` — standalone notebook for Question 5.
- `Question_6_GameStop_Stock_Graph.ipynb` — standalone notebook for Question 6.

## How to run

1. Open a notebook in Jupyter, JupyterLab, or Google Colab.
2. Run cells from top to bottom.
3. The first code cell installs the required packages.
4. Internet access is needed for Yahoo Finance and Stock Analysis data retrieval.

## Data sources

- Stock prices: Yahoo Finance via `yfinance`.
- Annual revenue: Stock Analysis HTML revenue-history pages, parsed with `pandas.read_html`.

Revenue values are normalized to USD millions before plotting.

## Important

The notebooks contain executable source code and instructions, not fabricated outputs. Run them to generate real results and screenshots. Websites can change their HTML structure or rate-limit automated requests; if scraping fails, inspect the page tables and update the scraper's column selection.
