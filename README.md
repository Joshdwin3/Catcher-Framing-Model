# Catcher Framing Evaluation Model

This project builds a probabilistic strike-calling model using pitch-level location and movement data and applies it to quantify catcher framing on a per-game basis.

## Project Overview
Traditional catcher evaluation relies on subjective observation. This project provides an objective, pitch-level metric to measure how often a catcher gains or loses strikes relative to expectation.

## Key Features
- XGBoost strike probability model (AUC ≈ 0.96)
- Pitch-level framing scores
- Game-level catcher evaluation
- Automated PDF reporting for game summaries

## Project Structure
- `notebooks/` – 01: Model training, 02: Game scoring & report generation
- `outputs/` – Example PDF report for a game
- `models/` – Optional trained model artifacts
- `src/` – Optional reusable functions for scoring/reporting

## Example Output
See `outputs/sample_catcher_report.pdf`

