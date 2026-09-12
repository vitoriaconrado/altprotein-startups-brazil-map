# Alt Protein Startups Brazil Map

A public-facing snapshot of Brazil's emerging alternative protein ecosystem.

This project maps startup activity across cultivated meat, fermentation, and plant-based food innovation to make the ecosystem more visible and easier to explore.

## Live map

The project is currently published here:

https://vitoriaconrado.github.io/projects/startups_map.html

## Why this project exists

Brazil is becoming an increasingly relevant market for alternative proteins, with startups, researchers, and entrepreneurs building across food innovation, biotech, and ingredient development. This map helps surface that activity in a visual, accessible format for public discovery.

## What is included

The map highlights startup locations and category groupings across the Brazilian alt-protein landscape, including:

- Cultivated meat / cellular agriculture
- Fermentation-based innovation
- Plant-based food startups

## Project status

This repository is a public prototype and data exploration project. It includes a curated dataset and a Folium-based map that visualizes the current ecosystem footprint in Brazil.

## Quick start

### 1. Create a virtual environment

```bash
python -m venv .venv
.venv\Scripts\activate
```

### 2. Install dependencies

```bash
pip install pandas folium
```

### 3. Generate the map

```bash
python map.py
```

This produces an HTML file such as:

```bash
startups_map.html
```

## Data profile

The current dataset includes a curated selection of Brazilian startup locations and category labels. Marker colors help distinguish each segment of the alternative protein ecosystem at a glance.

## Current focus

This is a lightweight foundation for a public-facing ecosystem map. It is designed to expand over time with more companies, stronger data coverage, and richer public context.

## Future goals

Possible next steps include:

- Adding more startups and updated ecosystem coverage
- Including filters by region, state, or product category
- Building a web interface for browsing and searching
- Adding attribution and contribution workflows for public data updates
  (making it prettier!) 

## License

This project is intended for educational and exploratory use. Please credit the project when sharing or adapting the material.

## Contributing

If you want to expand the dataset, improve the map, or help turn this into a more complete public resource, contributions are welcome.
