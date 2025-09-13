# DeFi Analytics Projects  

This repo contains two notebooks showcasing on-chain analytics work in DeFi using Python, Web3.py, Covalent API, Pandas, and Matplotlib.  

---

## 1. USDC On-Chain Analysis  
- **Goal:** Track inflows/outflows of USDC to understand liquidity movements.  
- **Key Features:**  
  - Pulled USDC transfer data via APIs.  
  - Analyzed top inflow/outflow trends.  
  - Visualized top 10 wallets by USDC volume.  
- **Notebook:** [usdc_analysis.ipynb](https://github.com/giftekpen/usdc-whale-analysis/blob/main/USDC%20Analysis.ipynb)  

---

## 2. Whale Tracking (Ethereum Addresses)  
- **Goal:** Monitor hourly activity of large Ethereum addresses ("whales").  
- **Key Features:**  
  - Defined whale addresses to track.   
  - Built monitoring logic for transactions above $100k.    
- **Notebook:** [whale_tracking.ipynb](https://github.com/giftekpen/usdc-whale-analysis/blob/main/Whale%20txn%20%26%20monitoring%20(1).ipynb)  

---

### Tools & Libraries
- **Python**, **Web3.py**, **Alchemy API**, **Pandas**, **Matplotlib** , **Etherscan API** 
- Data queried directly from Ethereum on-chain events  

---

### Notes
Both notebooks are exploratory and demonstrate the ability to:  
- Decode on-chain data into usable insights  
- Build analytics logic for vaults, tokens, and whale activity  
- Support both risk analysis and data science workflows in DeFi
