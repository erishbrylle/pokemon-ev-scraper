# Pokémon EV Scraper

A Python web scraper to collect Pokémon EV yields from [PokémonDB](https://pokemondb.net).  
The scraper extracts EV yields for all Pokémon, including special cases like Nidoran♀/♂, Farfetch'd, and Mr. Mime, and saves them into a CSV with numeric columns for each stat.

## Features
- Scrapes all Pokémon from the National Dex
- Handles Pokémon with special characters in names
- Returns EV yields in numeric columns: HP, Attack, Defense, Sp. Atk, Sp. Def, Speed
- Optional `limit` parameter for testing a subset of Pokémon

## Usage
Open scraper.ipynb
Run the cells to scrape Pokémon EVs
Results will be saved as pokemon_ev_yields.csv
