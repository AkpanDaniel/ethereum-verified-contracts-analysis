
# Ethereum Verified Contracts Analysis (2015-2025)

10-year analysis of 816K Ethereum smart contracts revealing developer trends, ecosystem maturity, and future forecasts.

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow.svg)](https://powerbi.microsoft.com/)

Read Full Analysis on Medium >>

## Dashboard
<img width="1280" height="708" alt="image" src="https://github.com/user-attachments/assets/4d1d4d81-597c-4bad-ad56-f76647559c60" />

## Key Findings

- Two boom cycles: 2017 ICO era + 2021 DeFi/NFT explosion (peak: 2K contracts/day)
- Post-2022 stabilization: Steady 200-300 contracts/day (maturity, not decline)
- Seasonal patterns: High activity in Jan/Apr/Oct/Nov, low in summer months
- 6-month forecast: Steady growth predicted, Q1 2026 uptick expected

## Tech Stack

Analysis: Python • pandas • numpy • Prophet • statsmodels  
Visualization: Plotly • matplotlib • Power BI  
Environment: Jupyter Notebook

## Project Structure

├── notebooks/          # Jupyter analysis notebook
├── data/              # Raw & processed datasets
├── dashboards/        # Power BI dashboard (.pbix)
├── outputs/           # HTML charts from analysis
└── images/            # Screenshots & visuals

## Quick Start

# Clone repository
git clone https://github.com/AkpanDaniel/ethereum-verified-contracts-analysis.git

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook notebooks/Ethereum_VerifiedContracts_2015_2025.ipynb


## Data

- Source: [Etherscan](https://etherscan.io/)
- Period: Jan 2015 – Nov 2025
- Total Contracts: 816,000+
- Daily Records: 3,965 observations

## What's Inside

1. Time-series analysis with rolling averages & cumulative trends
2. Anomaly detection using statistical thresholds (mean + 3σ)
3. Seasonal decomposition revealing yearly patterns
4. ML forecasting with Facebook Prophet (180-day horizon)
5. Interactive Power BI dashboard with filters & KPIs

## Links

[Power BI Dashboard](https://app.powerbi.com/groups/me/reports/6e736c31-c259-40fe-b894-c689f55e67fd?ctid=6648e821-032e-4350-9696-ecff1b4a6ba8&pbi_source=linkShare)  
Medium Link https://medium.com/@danisinator123/a-decade-of-ethereum-what-816k-verified-contracts-tell-us-69967139daee


## License

MIT License - see [LICENSE](LICENSE) file

## Contact
Akpan Daniel [LinkedIn](https://www.linkedin.com/in/akpan-daniel-b09a1b1a1/)

Star this repo if you found it useful!
