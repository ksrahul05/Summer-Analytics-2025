This project uses machine learning to predict parking occupancy and generate dynamic pricing for parking lots.

## 📂 Folder Structure

- `CapStoneProject.py`: Main ML pipeline with model training and predictions
- `parking_analysis_results/`: Contains generated results (plots, CSVs, model)
- `requirements.txt`: Dependencies for environment setup

## 🧠 Model

- `GradientBoostingRegressor` used to predict occupancy
- Dynamic pricing scales with occupancy between $5 and $20

## 📊 Outputs

- Bokeh visualization of pricing
- Top 5 peak hours
- Feature importance ranking
- Next-day price predictions

## 🚀 How to Run

```bash
pip install -r requirements.txt
python CapStoneProject.py
