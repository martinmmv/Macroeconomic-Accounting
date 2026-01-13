# Sectoral Balances Analysis (U.S.)

## Overview

This project analyzes U.S. sectoral financial balances, comprising the government, domestic private, and foreign sectors, using official data from the Bureau of Economic Analysis (NIPA) and the Federal Reserve Economic Data (FRED). The objective is to examine how these balances interact over time and how fiscal policy, private sector behavior, and external imbalances are linked through an accounting identity.

## Data Sources

### Bureau of Economic Analysis (BEA), NIPA
- Government Net Lending / Borrowing  
- Domestic Private Net Lending / Borrowing  

### Federal Reserve Economic Data (FRED)
- **NETFI** — Net Financial Investment (External Sector)  
- **GDP** — Gross Domestic Product  

All series are quarterly and measured as **flows**, not stocks.

---

## Methodology

### Data Preparation
- Align quarterly time series (1990–2025)  
- Normalize all sectoral balances as a percentage of GDP  
- Validate accounting consistency across sectors  

### Sectoral Identity

The analysis is grounded in the macroeconomic accounting identity:

```math
Government Balance + Private Balance + Foreign Balance = 0
