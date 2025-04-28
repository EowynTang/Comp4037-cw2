# COMP4037 Coursework 2 - Advanced Visual Designs

This repository contains the submission for COMP4037 Coursework 2.  
The project demonstrates the use of advanced visual designs in data visualization, focusing on environmental impacts across different diet groups.

## Project Structure

- `plot.ipynb`: Jupyter Notebook containing data processing, visualization code, and radar chart generation.
- `data/Results_21MAR2022_nokcaladjust.csv`: The original dataset provided for coursework analysis.
- `radar_chart.png`: Generated radar chart showing normalized environmental impacts across diet groups.

## Visualization Method

- **Visual Design Type**: Radar Chart (Spider Chart)
- **Tool Used**: Python (Pandas + Plotly Graph Objects)
- **Data Source**: Provided dataset `Results_21MAR2022_nokcaladjust.csv`
- **Diet Groups**:
  - Vegan
  - Veggie (Vegetarian)
  - Fish-eater
  - Meat-eater
  - Meat50 (50% meat consumption)
  - Meat100 (100% meat consumption)
- **Variables Visualized**:
  - GHG Emissions
  - Land Use
  - Water Scarcity
  - Eutrophication
  - CH₄ Emissions
  - N₂O Emissions
  - Biodiversity Impact
  - Agricultural Water Use
  - Acidification Potential

## Key Observations

- Vegan and Vegetarian diets show the lowest environmental impact across all categories.
- Meat100 diets (full meat consumption) have the highest environmental burden, especially in GHG emissions, land use, and biodiversity impact.
- Reducing meat consumption (Meat50) moderately reduces environmental impact but does not match the benefits of plant-based diets.

## How to Reproduce

1. Clone the repository:
   ```bash
   git clone https://github.com/EowynTang/Comp4037-cw2.git
