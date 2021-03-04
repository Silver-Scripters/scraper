# scraper

Repo for NBA game data webscrapers for use in training models.

## Index

1. `lines-scraper.ipynb` scrapes theScore betting odds (spread, total, final points).
   See `lines.csv` for the output format as of 3/2/2021.

2. ` ` scrapes basketball-reference for player stats and team stats

## How to run the scrapers

1. Make sure to have Jupyter Notebook installed.

2. Enter a python virtual environment using `python3 -m venv venv`.

3. Activate the virtual environment using `source venv/bin/activate`

4. Install the dependencies from the `requirements.txt`: `pip3 install -r requirements.txt`. (Additionally, make sure to `pip freeze > requirements.txt` anytime you introduce new dependencies)

5. Follow the Jupyter notebook instructions on what constants to set and run the cells.
