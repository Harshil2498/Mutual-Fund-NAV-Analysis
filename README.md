# Mutual Fund NAV Analysis – My Project  

**Hi! This is my submission for the programming assessment**

### What I Did 
I took 5 mutual funds, downloaded their daily NAV from the last ~4 years (Nov 2021 – Nov 2025), and wrote a Python program (Jupyter Notebook):

- Reads all the Excel files automatically 
- Calculates the correct CAGR (Compound Annual Growth Rate) for each fund
- Shows the **Top 2** best performing funds
- Shows the **Worst 2** performing funds
- Finds every single day when any fund’s NAV jumped or fell by more than ±5% compared to the previous day

### Results I Got
================================================================================
                    MUTUAL FUND 7-YEAR CAGR ANALYSIS RESULT                     
           (Data available only from Nov-2021 → ~4 years CAGR shown)            
================================================================================

TOP 2 PERFORMING MUTUAL FUNDS
--------------------------------------------------
1. Aditya Birla Nifty Index Fund →  13.95%
2. UTI Index fund            →  10.62%

WORST 2 PERFORMING MUTUAL FUNDS
--------------------------------------------------
4. HDFC Index Fund           →  10.40%
5. ICICI Nifty Fund          →  10.38%

================================================================================
                          NAV SWING DETECTION (> ±5%)                           
================================================================================
                    Fund Name        Date % Change
Aditya Birla Nifty Index Fund 04-Jun-2024   -5.48%
              HDFC Index Fund 04-Jun-2024   -5.85%
             ICICI Nifty Fund 04-Jun-2024   -5.85%
               SBI Index Fund 04-Jun-2024   -5.87%
               UTI Index fund 04-Jun-2024   -5.85%

Total days with > ±5% change: 5

================================================================================
### How to Run My Project
1. 5 Excel files inside the folder called `fund_data`
2. Open the file `Mutual Fund Analysis.ipynb` in Jupyter Notebook
3. Click “Run All”


### Folder Contains
- `fund_data/` → Excel files go here  
- `Mutual fund analysis.ipynb` → my complete code  
- `README.md` → this file you’re reading  

 
Ready for submission!

Thank you!
