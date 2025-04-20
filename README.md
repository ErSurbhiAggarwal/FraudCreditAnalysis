# **A Tableau Dashboard for Smarter Fraud Detection By Surbhi** 

  In the fast-paced world of finance, fraud isn’t just a threat—it’s a moving target. With millions of transactions happening every day, catching fraudulent activity quickly and accurately is critical. 
  This Tableau project dives deep into transaction data to uncover risky patterns, spot vulnerabilities, and help financial institutions stay one step ahead.
  
  ## 🎯 Project Goal
      The goal of this dashboard is simple: make fraud detection smarter and faster. By visualizing key transaction data, we can highlight suspicious behavior, assess risk levels, and guide data-driven decisions to strengthen security and reduce financial losses.
    
  ### **🛠️ Chapter 1: Building the Foundation with Python (ETL Process)**
      Before diving into visualization, the first step was preparing the data. Using Python, we created an ETL (Extract, Transform, Load) process that cleansed and structured the raw transaction data for analysis.
    
      1. Extracted data from source files containing transaction details
      2. Transformed it to handle missing values, correct formats, and categorize transaction types
      3. Loaded the cleaned dataset into a format optimized for Tableau
      This notebook ensured we had a reliable, high-quality dataset to build accurate and meaningful visuals on top of.
    
   ### **📊 Chapter 2: Designing the Interactive Tableau Dashboard**
      With the data ready, we moved into Tableau to bring it to life through an interactive, easy-to-use dashboard focused on fraud detection and risk analysis.
      **Key features of the dashboard include:**
    
      1. Fraud BreakDown By Account And Transaction Type
        Quickly see where fraud is happening most—especially with Transfers and Cash Outs, which together account for 63% of flagged cases in both account types.
      2. Peak Fraud Days
        Higher fraud activity observed on Mondays, Thrusdays, Fridays, Saturdays and Sundays, possibly targeting end/start-of-week processing gaps.   
      3. Peak Fraud Times
        Fraud peaks during off-business hours, suggesting automated or stealth attempts.
      4. Transaction Breakdown by Transaction Type
        Fraudsters prefer methods that quickly liquidate or relocate stolen funds as Cash outs gives instant access and Transfers are easy to hide/move money.
      5. Branch Risk Map
        A visual breakdown of fraud by location helps identify vulnerable branches like Mujoka, guiding targeted security improvements.
    
  ## Financial Impact
    Metrics show the bigger picture—$36.28M in losses from 68 fraud cases, making the financial risk crystal clear.
    
  ## 💡 Key Takeaways
    1. Transfers and Cash Outs account for about 63% of all fraud cases—tightening controls here could make a big difference.
    2. Fraud peaks in the afternoon and late evening, suggesting these times need stronger oversight.
    3. Certain branches are more vulnerable, offering a chance to focus training and security resources where they’re needed most.

## 🎯 Actionable Insights
  1. Enhance monitoring during peak fraud hours and days.
  2. Strengthen controls around high-risk account and transaction types.
  3. Investigate branches with recurrent fraud spikes.
  4. Adjust fraud detection rules to catch frequent small-value attempts.
  5. Strengthen identity verification before large cash withdrawals.
  6. Monitor for unusual transfer patterns, especially rapid or repeated transfers to new recipients.
  7. Consider setting dynamic thresholds for alerts based on customer history.
