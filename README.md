# Lionel Messi Goals Analysis

This repository contains a detailed analysis of Lionel Messi's goal-scoring data using various visualizations. The goal data includes match details, goal types, minutes scored, home/away performance, and goals per competition, season, and playing position.

## Project Overview

The goal of this project is to explore and visualize Lionel Messi's goal-scoring patterns and trends across various metrics. The dataset includes the following fields:
- **Season**: The season in which the goal was scored.
- **Competition**: The competition where the goal was scored.
- **Matchday**: The matchday number in the competition.
- **Type**: The type of goal (e.g., left-footed shot, header, etc.).
- **Minute**: The minute of the match when the goal was scored.
- **Venue**: Whether the goal was scored at home or away.
- **Playing_Position**: Messi's playing position during the match.

## Data Preprocessing

1. **Data Cleaning**: The dataset is filtered to remove rows with missing or invalid values, focusing on relevant goal types.
2. **Minute Conversion**: The "Minute" field, which may contain strings like '90+3' for injury time, is converted into numeric values for further analysis.

## Visualizations

1. **Histogram of Goal Scoring Minutes**:
   - A histogram is created to show the distribution of the minutes when Messi scored goals. This helps to identify peak times during matches when goals are scored.

2. **Goals Scored per Season**:
   - A bar chart is used to display the number of goals Messi scored in each season, providing insights into his performance over time.

3. **Goals Scored per Competition**:
   - A bar chart to visualize Messi's goal-scoring performance across different competitions.

4. **Goals Scored: Home vs Away**:
   - A bar chart comparing Messi's goals scored at home vs away games.

5. **Goals Scored by Playing Position**:
   - A bar chart to visualize how many goals Messi scored in different playing positions throughout his career.

## Files in the Repository

- **data.csv**: The raw dataset containing Lionel Messi's match and goal details.
- **analysis.py**: Python script containing the code to process the data and generate visualizations.
- **README.md**: Documentation explaining the project and its contents.

## Requirements

- Python 3.x
- pandas
- matplotlib

You can install the required dependencies using `pip`:


## How to Run

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the `analysis.py` script to generate the visualizations.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

