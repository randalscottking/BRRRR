# BRRRR Investment Automation - Complete Setup Guide

**Last Updated:** March 11, 2026

## Overview

You now have three interconnected tools:

1. **Deal Tracker** (Notion) - Track individual properties through the BRRRR cycle
2. **Market Analysis Tracker** (Notion) - Understand local market conditions
3. **Market Automation Script** (Python) - Automate market data collection

## Notion Databases

### Deal Tracker Database
- **URL:** https://www.notion.so/936926d8f35342e1a43c4bb66fc04e34
- **Status:** ✅ Ready to use
- **Fields:** 40+ properties covering buy, rehab, rent, refinance, repeat

### Market Analysis Tracker Database
- **URL:** https://www.notion.so/2e33ce7a0b4f49d693d8c76b4acec2ea
- **Status:** ✅ Ready to use
- **Fields:** Market metrics, neighborhoods, comps, trends

## Python Automation Setup

### Prerequisites
- Python 3.8+ installed
- pip installed
- Notion API Token

### Step 1: Configure the Script

Open `brrrr_market_automation.py` in a text editor and update:

```python
# Line 13-15
NOTION_TOKEN = "secret_YOUR_TOKEN_HERE"  # Paste your Notion API token
MARKET_TRACKER_DB_ID = "db8dbfba-33b5-4d31-abbd-afa98738eeb0"  # Already correct
DEAL_TRACKER_DB_ID = "c70f641c-4d58-45be-9885-cde094e0c9c9"  # Already correct
```

### Step 2: Install Dependencies

The script uses `requests` library:
```bash
pip install requests --break-system-packages
```

### Step 3: Test the Script

```bash
cd ~/BRRRR
python3 brrrr_market_automation.py
```

Expected output:
```
🚀 BRRRR Market Analysis Automation
============================================================
Ready to run automation.
```

## Market Focus

- **Acworth, GA** - ZIP 30101 (Cobb County)
- **Cartersville, GA** - ZIP 30120 (Bartow County)

---

**System Created:** March 11, 2026