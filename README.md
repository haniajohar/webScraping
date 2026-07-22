# Notebook Project

This workspace contains a single Jupyter notebook, [webscraping.ipynb](webscraping.ipynb), that demonstrates three small Python workflows:

1. Basic dataset inspection with pandas.
2. Web scraping headings from the Bahria University website.
3. Web scraping headings from the Daraz Pakistan homepage.

## What the notebook does

The notebook loads a CSV dataset, prints a quick summary, and checks for missing values. It then uses `requests` and `BeautifulSoup` to collect `h1`, `h2`, and `h3` headings from two websites and saves the extracted data to CSV files.

## Requirements

Install the Python packages used by the notebook:

```bash
pip install pandas requests beautifulsoup4
```

## Notes

The first cell currently reads from `/content/index.csv`, which is a Colab-style path. If you want to run the notebook locally, update that path to point to your own CSV file.

## Generated files

Running the scraping cells creates these CSV files in the workspace:

- `bahria_university_headings.csv`
- `new1.csv`

These outputs are ignored by Git so the repository stays focused on the notebook itself.