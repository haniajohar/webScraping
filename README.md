# webScraping

This repository contains a single Jupyter notebook, [webscraping.ipynb](webscraping.ipynb), that combines basic data inspection with simple web scraping examples.

## Project Overview

The notebook demonstrates three tasks:

1. Inspecting a CSV dataset with `pandas`.
2. Scraping heading tags from the Bahria University website.
3. Scraping heading tags from the Daraz Pakistan homepage.

The scraping cells collect `h1`, `h2`, and `h3` elements, store the results in a dataframe, and export the output to CSV files.

## Requirements

Install the Python packages used in the notebook:

```bash
pip install pandas requests beautifulsoup4
```

## How To Run

1. Open `webscraping.ipynb` in VS Code or Jupyter.
2. Update the dataset path in the first cell if needed.
3. Run the notebook cells in order.

## Notes

The first cell currently reads from `/content/index.csv`, which is a Colab-style path. If you are running this locally, replace it with the path to your own CSV file.

## Output Files

Running the scraping cells generates these files in the project folder:

- `bahria_university_headings.csv`
- `new1.csv`

These files are ignored by Git so the repository stays focused on the notebook source.