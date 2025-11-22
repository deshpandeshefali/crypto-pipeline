# 🚀 Automated Real-Time Crypto Data Pipeline & Power BI Dashboard

An end-to-end **automated cryptocurrency data engineering pipeline** that fetches real-time crypto market data, stores it in a **cloud-hosted MySQL database (Aiven)**, automates ingestion using **GitHub Actions**, and visualizes insights through an interactive **Power BI dashboard**.

This project demonstrates real-world skills in:
- API integration  
- Cloud databases  
- Python ETL scripting  
- CI/CD automation  
- Business Intelligence  
- Real-time analytics  

---

## 🧱 **Project Architecture**

- CoinGecko API → Python ETL → Aiven MySQL → GitHub Actions (automation) → Power BI Dashboard

---

## 🌟 **Features**
- Fetches live crypto data (Bitcoin, Ethereum, Ripple)
- Inserts data into Aiven MySQL
- Automatically runs every hour using GitHub Actions
- Stores historical price data for analysis
- Visualizes price trends, market cap & volume in Power BI
- Secure credentials using GitHub Secrets
- Fully cloud-based and scalable

---

## 🛠️ **Tech Stack**
- **Python** (requests, mysql-connector-python)
- **MySQL (Aiven Cloud)**
- **GitHub Actions (CI/CD Automation)**
- **CoinGecko API**
- **Power BI Desktop**
- **SQL for querying data**

---

## 📦 **Repository Structure**

- crypto-pipeline/
│
├── fetch_crypto.py # Python ETL script
├── requirements.txt # Dependencies
│
└── .github/workflows/
└── crypto.yml # Automation workflow (hourly)


---

## 🔧 **Setup Instructions**

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/crypto-pipeline
cd crypto-pipeline
```

## Automation (GitHub Actions)

- This project uses GitHub Actions to run the ETL script every hour.

- Cron schedule: 0 * * * *

## To run manually:

- Go to Actions → Crypto Pipeline → Run Workflow.

## Power BI Dashboard
- The dashboard connects directly to Aiven MySQL and visualizes:
- Real-time price trends
- Market capitalization
- 24h trading volume
- Hourly updated timestamp
- Visuals included:
- Line chart (trend over time)
- Bar chart (market cap)
- KPI cards (latest prices)
- Table (historical records)

**Shefali Deshpande**<br>
Aspiring Data Analyst<br>
Email : dshef20@gmail.com <br>
[LinkedIn][https://www.linkedin.com/in/shefali-deshpande/] <br>
[Portfolio][https://github.com/deshpandeshefali] 

