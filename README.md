# Stembureau meting
Dit project heeft als doel de stemlokalen van de gemeenteraadsverkiezingen van 2022 te analyseren. Het wordt uitgevoerd door Open State Foundation in opdracht van het ministerie van Binnenlandse Zaken en Koninkrijksrelaties.

# Vereisten
De analyse wordt uitgevoerd via Python code in een Jupyter Notebook. De meeste informatie kun je direct bekijken op https://github.com/openstate/stembureau-meting/blob/main/jupyter/stembureau_data.ipynb.

Als je de code zelf wilt uitvoeren of aanpassen, installeer dan [Jupyter Notebook](https://docs.jupyter.org/en/latest/install/notebook-classic.html):
- Of door [Anaconda te installeren](https://www.anaconda.com/products/distribution) (dit is een grote installatie waarmee je ook Python installeert)
- Of als je al Python hebt op bv. een systeem dat Linux draait:
    - `pip3 install --upgrade pip`
    - `pip3 install jupyter`
    - `pip3 install -r requirements.txt`
    - `python3 -m notebook` hiermee start je de Notebook

# Data
Het opgeschoonde databestand met de 8582 stemlokalen op basis van de [Waar is mijn stemlokaal](https://waarismijnstemlokaal.nl/) data is te vinden in [data/export/full_export.csv](https://github.com/openstate/stembureau-meting/blob/main/data/export/full_export.csv) (rechtermuis-klik de 'Download'-knop en selecteer de optie om de link op te slaan).
