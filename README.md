

# Stablecoins Analysis

## Project Overview

This project provides an in-depth analysis of stablecoins using various blockchain data sources. Stablecoins are a class of cryptocurrencies that aim to maintain a stable value relative to a reference asset, often a fiat currency like the US Dollar. The analysis leverages data from multiple providers to explore key metrics and trends within the stablecoin ecosystem.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Sources](#data-sources)
3. [Key Metrics](#key-metrics)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Results and Visualizations](#results-and-visualizations)

## Introduction

The project focuses on aggregating and visualizing data related to stablecoins from various blockchain and cryptocurrency data providers. The primary goal is to provide a comprehensive overview of stablecoin activities, including metrics like active supply, current supply, and reserve composition.

## Data Sources

We utilize data from the following providers:

- **[Messari](https://messari.io/screener):** Offers detailed, human-readable data. The primary advantage is its ease of use, though it requires a subscription and proper citation.
- **[The Block](https://www.theblock.co/data/crypto-markets/spot):** Provides in-depth market data.
- **[CoinGecko](https://www.coingecko.com/):** A widely-used platform for real-time data on cryptocurrency prices and trends.
- **[CoinMetrics](https://coinmetrics.io/):** Focuses on providing comprehensive data for crypto assets.
- **[Dune Analytics](https://dune.com/home):** A community-driven platform for blockchain data analysis.
- **[The Graph API](https://thegraph.com/en/):** Offers a decentralized protocol for indexing and querying blockchain data.

## Key Metrics

The analysis covers several key metrics, including but not limited to:

- **Adjusted Transaction Value (in native units):** The sum of native units transferred between distinct addresses, with certain noise and artifacts removed.
- **1-Year Active Supply:** The sum of unique native units that transacted at least once in the trailing 1 year.
- **Current Supply (in native units):** The sum of all native units ever created and visible on the ledger.
- **Supply Velocity:** The ratio of value transferred to the current supply, indicating the rate of turnover.
- **Reserve Composition:** The allocation of funds to different securities by stablecoin issuers.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/stablecoins-analysis.git
    cd stablecoins-analysis
    ```

2. **Install the required Python packages:**

    Ensure you have Python 3.x installed. You can install the required packages using:

    ```bash
    pip install -r requirements.txt
    ```

    _Note:_ If you're running the notebook in Google Colab, the required packages can be installed in the notebook itself.

## Usage

1. **Data Collection:**

    Before running the analysis, make sure to collect the necessary data from the aforementioned sources. Ensure that your API keys (if needed) are correctly set up.

2. **Running the Notebook:**

    You can run the Jupyter notebook using the following command:

    ```bash
    jupyter notebook stablecoins.ipynb
    ```

3. **Visualizations:**

    The notebook contains several visualizations using `Matplotlib`, `Seaborn`, and `Plotly`. Ensure these libraries are installed and run the notebook cells to generate the visualizations.

## Results and Visualizations

The results section of the notebook provides various insights into the stablecoin market, including:

- **Supply Dynamics:** Visualizations showing the growth in stablecoin supply over time.
- **Transaction Activity:** Analysis of transaction volumes and their trends.
- **Reserve Analysis:** Breakdown of stablecoin reserves and their security.

