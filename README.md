# PerfectFit: AI-Powered Outfit Selection

## Overview

PerfectFit is an AI-powered outfit recommendation system that uses a genetic algorithm to generate optimal outfits based on user preferences. The system considers factors such as dress code, color palette, comfort level, and budget to suggest an outfit with the highest fitness score.

## Features

- Generates an initial population of outfits from a predefined dataset.
- Evaluates the fitness of each outfit based on user preferences.
- Uses genetic algorithms with selection, crossover, and mutation to evolve better outfit combinations.
- Implements elitism to retain the best outfits across generations.
- Plots the average fitness of the population over generations.

## Requirements

- Python 3.x
- Google Colab (or Jupyter Notebook for local execution)
- Required Libraries:
  - `pandas`
  - `matplotlib`
  - `random`

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Raneem0Alyahya/PerfectFit.git
   ```
2. Open `
PerfectFit.ipynb` in Google Colab or Jupyter Notebook.
3. Ensure dependencies are installed by running:
   ```sh
   pip install pandas matplotlib
   ```

## Usage

1. Run the notebook.
2. Enter the following inputs when prompted:
   - **Dress Code**: (Casual, Sportswear, Business, Evening)
   - **Color Palette**: (Dark, Bright)
   - **Comfort Level**: (1 to 5)
   - **Budget**: (in SAR)
3. The system will process the best possible outfit based on the given inputs.
4. View the recommended outfit along with its fitness score.

## Algorithm

1. **Initialize Population**: Randomly generates outfits from the dataset.
2. **Fitness Evaluation**: Scores each outfit based on user preferences.
3. **Selection**: Uses binary tournament selection to choose parents.
4. **Crossover**: Applies two-point crossover to create new outfits.
5. **Mutation**: Randomly replaces an item in the outfit with a new one.
6. **Elitism**: Retains top-performing outfits across generations.
7. **Termination**: Stops when the fitness threshold is reached or max generations are exhausted.
8. **Visualization**: Plots the fitness trend over generations.

## Dataset

The dataset (`search_space.csv`) contains:

- **Category**: Type of clothing item (Top, Bottom, Shoes, etc.)
- **Item Name**: Name of the clothing piece
- **Price**: Cost in SAR
- **Dress Code**: Appropriate occasion
- **Color**: Dark or Bright
- **Comfort Level**: Rated from 1 to 5

## Output

The final suggested outfit includes:

- Top
- Bottom
- Shoes
- Neck Accessory
- Purse
- Fitness Score

## License

This project is open-source and available under the MIT License.

## Author

Developed by Raneem Al-Yahya


