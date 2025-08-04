# 🇸🇷 Suriname Exchange Rate Tracker

This repository automatically tracks and archives official exchange rates (USD and EUR) from banks operating in Suriname. The process is executed on a private server and stored in a transparent, auditable format.

---

## 📌 Purpose

- Collect, verify, and log foreign exchange rates from official bank websites
- Maintain full traceability of HTTP requests and responses
- Commit and register each snapshot in Git history
- Create a GitHub Issue for every rate snapshot with labels by **bank**, **currency**, and **type (buy/sell)**
- Generate a daily **summary issue** that links all the others
- Support public audits and transparency in Suriname’s exchange markets

---

## 📂 Folder Structure

Each bank’s data snapshot is saved as a folder inside a daily folder:

```
2025/
└── 08/
    └── 03/
        ├── dsb-20250803080112/
        │   ├── request.json
        │   ├── response.json
        │   └── results.json
        └── finabank-20250803080210/
            ├── request.json
            ├── response.json
            └── results.json
```

---

## ✅ Latest Exchange Rates

📅 **Last updated:** 2025-08-04 00:00:00

| Bank | 💵 Buy | 💵 Sell | 💶 Buy | 💶 Sell |
|------|--------|---------|--------|---------|
| Central Bank | 36.53 | 37.07 | 41.96 | 42.96 |
| Central Money Exchange | 38.15 | 38.85 | 42.00 | 42.50 |
| DSB | 36.28 | 37.02 | 41.91 | 42.77 |
| Finabank | 36.76 | 37.18 | 42.73 | 43.78 |
| Hakrinbank | 36.70 | 37.18 | 42.70 | 43.78 |
| VCB Bank | 36.65 | 37.10 | 35.75 | 38.10 |


🔎 [View summary issue](https://github.com/divengine/suriname-rates/issue/1)

---

## 📊 Trend Graphs (90 Days)

Trend visualizations are auto-generated per bank and currency.

```
#### USD Buying Rate (90d)
```
                                                            
                                                            
                                                            
                                                            
                                                            
                                                            
                                                            
                                                            
                                                            
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿                              
```

#### EUR Buying Rate (90d)
```
Chart not available (flat values)
```

```

---

## 📈 Monthly Summary Statistics

| Bank           | Currency | Average | Maximum | Minimum |
|----------------|----------|---------|---------|---------|
| DSB Bank       | USD      |         |         |         |
| DSB Bank       | EUR      |         |         |         |
| VCB Bank       | USD      |         |         |         |
| ...            | ...      | ...     | ...     | ...     |

| Bank | Currency | Average | Maximum | Minimum |
|------|----------|---------|---------|---------|
| Central Bank | EUR | 41.96 | 41.96 | 41.96 |
| Central Bank | USD | 36.53 | 36.53 | 36.53 |
| Central Money Exchange | EUR | 42.00 | 42.00 | 42.00 |
| Central Money Exchange | USD | 38.15 | 38.15 | 38.15 |
| DSB | EUR | 41.91 | 41.91 | 41.91 |
| DSB | EUR/USD | 1.13 | 1.13 | 1.13 |
| DSB | USD | 36.28 | 36.28 | 36.28 |
| Finabank | EUR | 42.73 | 42.73 | 42.73 |
| Finabank | USD | 36.76 | 36.76 | 36.76 |
| Hakrinbank | EUR | 42.70 | 42.70 | 42.70 |
| Hakrinbank | USD | 36.70 | 36.70 | 36.70 |
| VCB Bank | EURO | 42.50 | 42.50 | 42.50 |
| VCB Bank | USD | 36.65 | 36.65 | 36.65 |


---

## 🔐 Integrity and Compliance

- Every snapshot includes `request.json`, `response.json`, and `results.json`
- Traceroute and DNS data included to verify authenticity
- Git history acts as public audit trail
- Each commit is immutable and timestamped

---

## ⚠️ Legal Notice

This project uses public web data from official bank websites.
If any institution prefers to offer a dedicated API or channel, please [open an issue](https://github.com/divengine/suriname-rates/issues) or contact us.

---

## 📅 Future Plans

- Publish a **monthly PDF report** with graphs and analysis
- Add support for more currencies and institutions
- Create a dedicated viewer site (e.g. via paramaribo.info)

---

## 👥 Maintainers

Project by **Divengine Software Solutions**.

Website: https://divengine.com  
Public Transparency Portal: https://paramaribo.info
