# PYUSD
**PYUSD transaction client **
# 🧠 PYUSD Blockchain Intelligence Dashboard

A real-time analytics platform focused on understanding the impact of the PYUSD stablecoin on the Ethereum (and Solana) blockchain ecosystems.

## 🚀 Features

- 📈 **Real-time Ethereum Network Congestion Insights**  
  Track metrics like average gas prices, transaction count, and block timing over time.

- 💸 **PYUSD Token Imprint on Ethereum**  
  Analyze daily transfer volume, unique wallet activity, and gas costs associated with PYUSD transactions.

- 🔍 **MEV (Maximally Extractable Value) Event Detection**  
  Identify transactions with abnormal priority fees that may indicate MEV events targeting PYUSD.

- 🧪 **Execution Trace Explorer**  
  Utilize `debug_traceTransaction` and `trace_block` for deep inspection of how PYUSD transactions execute.

- ⚡ **Solana Integration**  
  Monitor PYUSD-related activity on the Solana network using public RPCs and GCP services.

- 📊 **Looker Studio Dashboard**  
  Google-native, interactive visualizations sourced directly from BigQuery and Google Sheets.

---

## 🛠️ Stack

- **Google Cloud Platform (GCP)**
  - BigQuery (Ethereum + Solana datasets)
  - GCP Blockchain Node Engine (trace access)
  - Google Sheets + Looker Studio (dashboard)
- **Google Colab** for data ETL and transformation
- **Python / Pandas** for querying and data processing
- **Solana RPC API** for non-EVM chain visibility

---

## 📂 Project Structure


---

## 📌 Setup Instructions

1. Open either notebook using **Google Colab**
2. Authenticate to GCP using your Google Account
3. Ensure access to:
   - BigQuery public datasets
   - GCP Node Engine (if using `debug_traceTransaction`)
4. Follow on-screen instructions to push data to Google Sheets
5. [Optional] Import Google Sheets into Looker Studio to create a live dashboard

---

## 🔒 Security

- No private keys or wallet credentials are stored
- Only public blockchain data is used

---

## 📈 Sample Dashboard Widgets

- Gas Price Trends by Day
- PYUSD Transaction Heatmap
- Top MEV-like Events
- Wallet Activity Over Time
- Aggregate Gas Costs from PYUSD

---

## 🤝 Contributions

We welcome PRs for:
- Better MEV detection models
- Cross-chain analytics (Polygon, Arbitrum, etc.)
- Enhanced visualizations for end users

---

## 📜 License

MIT License — feel free to use, modify, and distribute.

---

## 💬 Questions?

Open an issue or start a discussion in the repo.



