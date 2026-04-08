# Global Chargeback & Fraud Overview

# **Project Overview**

[Global Chargeback & Fraud Overview](https://lookerstudio.google.com/reporting/9092b2a9-5c60-420e-86d4-6d26baef9d48)

### **Objective**

The project aimed to monitor the global chargeback status across different (fictitious) financial legal entities, with a particular focus on fraud cases. Chargeback data usually comes from many different channels, making it hard to see the big picture. I built this dashboard to centralize the data and give stakeholders a single, clear overview of the global risk.

### Context

For this project, I simulated a global fintech company with multiple branches (legal entities). Financial apps deal with chargebacks on a daily basis. For example, a scammer might use a stolen credit card to add funds to a digital wallet. When the real cardholder discovers the fraud, they contact their bank to cancel the payment. This dashboard helps the Risk Team track these lost funds, identify the areas most at risk, and prevent future fraud. All data is tracked by the transaction's Authorization Date.

*Note: All data displayed in this dashboard is fictional.*

### Key Insights

- **The Q4 Server Overload**
    - The "Monthly Chargeback Breakdown" shows a huge spike in November and December 2025, causing about €119k in losses. Most of these were *Not Fraud*, meaning hackers weren’t the issue. Likely, server delays during the year-end rush caused deposits to appear late, prompting users to request refunds.
- **Fraud vs. Service**
    - Fraud cases actually peaked earlier in August 2025  and are now decreasing. The Risk Team’s updated anti-fraud filters worked well. The current main issue is the *Services Not Provided* dispute reason. The company should focus on fixing server delays (IT) and reassuring users (Customer Service).
- **High US Exposure**
    - The US accounts for almost €100k of the total risk exposure. The company must prioritize support and technical upgrades for North American users to stop these financial losses.
- **Branch Vulnerability**
    - Among legal entities, *Cipher Finance* is the most affected, with 371 cases and €97,434 in losses, mostly in Q4. Their app infrastructure struggled under heavy traffic and requires an urgent technical review.
- **Problematic Channels**
    - The data shows that *J.P. Morgan Payments* and the *Visa* network  are the channels with the highest losses. The developer team needs to review the API connection with J.P. Morgan to ensure faster deposit processing.

Try it out! You can interact with the filters below to explore the data:

[https://lookerstudio.google.com/embed/reporting/9092b2a9-5c60-420e-86d4-6d26baef9d48/page/d1MfF](https://lookerstudio.google.com/embed/reporting/9092b2a9-5c60-420e-86d4-6d26baef9d48/page/d1MfF)
