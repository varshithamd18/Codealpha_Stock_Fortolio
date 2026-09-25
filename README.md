# 📈 Stock Portfolio Tracker

> A lightweight, interactive CLI tool to calculate and track stock investments with automatic text export.

---

## 📌 Overview

**Stock Portfolio Tracker** is a Python command-line utility designed to help users quickly estimate the monetary value of their asset holdings. It maps hardcoded price feeds against user-selected ticker symbols, aggregates total capital allocated, and exports the final investment summary to a persistent text log.

---

## ✨ Features

- **Interactive Terminal Workflow:** Simple loop-driven prompt for entering stock symbols and share quantities.
- **Built-in Ticker Validation:** Protects against invalid ticker names before prompting for quantities.
- **Dynamic Valuation:** Computes individual asset value per entry alongside real-time total investment aggregation.
- **Automated Export:** Automatically writes summary reports out to `portfolio.txt` upon completion.
- **Zero Third-Party Dependencies:** Built entirely with standard library Python.

---

## 📊 Supported Assets & Base Prices

| Ticker | Company | Default Reference Price (USD) |
| :--- | :--- | :--- |
| `AAPL` | Apple Inc. | $180 |
| `TSLA` | Tesla, Inc. | $250 |
| `GOOG` | Alphabet Inc. | $150 |
| `AMZN` | Amazon.com, Inc. | $190 |
| `MSFT` | Microsoft Corp. | $420 |

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher installed on your machine.

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/stock-portfolio-tracker.git](https://github.com/varshithamd18/stock-portfolio-tracker.git)
   cd stock-portfolio-tracker
# Codealpha_Stock_Fortolio