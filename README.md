# Premier League Title Race Forecast

An educational Python project that simulates the 2026/27 Premier League title race.

## Objective

Estimate each team's probability of winning the Premier League using previous-season performance and a Monte Carlo match simulation.

## Method

The model:

- Uses 2025/26 league points per game as the baseline for returning Premier League teams.
- Includes Coventry City, Ipswich Town and Hull City as promoted teams, using conservative assumed Premier League points-per-game baselines.
- Applies higher uncertainty to promoted teams and teams with a new manager.
- Simulates a full home-and-away league season across all 20 teams.
- Includes a simplified home-advantage assumption.
- Repeats the season simulation thousands of times and records the champion in each run.

## Initial model result

The current simulation identifies Arsenal as the leading title favourite, followed by Manchester City and Manchester United.

The exact probabilities are generated in the notebook and can change when assumptions or inputs are updated.

## Limitations

This is an educational forecasting project, not betting advice.

The current version does not fully model injuries, future transfers, individual players, tactical changes, fixture timing, European competition, or real match-level expected-goals data. Results represent the model’s assumptions, not certain predictions.

## Tools used

- Python
- pandas
- NumPy
- matplotlib
- Google Colab

## Run the project

Open `01_title_race_forecast.ipynb` in Google Colab and run all cells.
