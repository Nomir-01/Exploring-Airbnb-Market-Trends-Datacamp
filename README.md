# Exploring Airbnb Market Trends

An exploratory analysis of Airbnb listing and review data for New York City. The project combines data from multiple file formats to summarize review dates, room types, and listing prices in a compact market overview.

## Analysis questions

- What are the earliest and most recent review dates in the data?
- How many listings are private rooms?
- What is the average listing price?
- How can the derived values be combined into a concise summary table?

## Tools

- Python
- pandas and NumPy
- Jupyter Notebook

## Repository contents

- `notebook.ipynb` — data loading, cleaning, and analysis
- `data/` — CSV, TSV, and Excel source files
- `nyc.jpg` — project cover image
- `requirements.txt` — Python dependencies

## Run locally

```bash
python -m venv .venv
python -m pip install -r requirements.txt
jupyter lab notebook.ipynb
```

Run the notebook from the repository root so its relative paths resolve to the files in `data/`.

## Project context

This is a personal learning project completed as guided DataCamp coursework. It demonstrates loading heterogeneous data sources, cleaning text and dates, and producing summary statistics with pandas.
