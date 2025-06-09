# 🏑 Hockey Forecasts

Welcome! This is a personal project where I use Bayesian modeling (via PyMC) to forecast outcomes of upcoming hockey matches based on current standings and past match data.

Each week, this repo:
- Downloads the latest match and standings data
- Fits a Bayesian model to estimate team strengths
- Simulates upcoming games
- Updates predictions and rankings
- Publishes results as a static HTML page via GitHub Pages

📅 **Updated every Monday morning** — or manually from the Actions tab.

---

## 🔮 Forecast Highlights

- Team attack and defense strengths estimated from real data
- Match results simulated using posterior predictive distributions
- Probabilities of final rankings calculated for each team
- Multiple visualizations (bar plots, violin plots) generated in the report

---

## 🚀 View the Latest Forecast

👉 [Live Site on GitHub Pages](https://emielrv.github.io/hockey-forecasts/)

---

## 🛠 Technologies Used

- [`PyMC`](https://www.pymc.io/) for Bayesian modeling
- `matplotlib`, `seaborn` for plots
- `pandas`, `numpy` for data wrangling
- GitHub Actions for scheduled automation
- GitHub Pages for publishing

---
