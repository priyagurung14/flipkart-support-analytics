# Flipkart Customer Support Analytics

Analyzed 85,000+ real Flipkart support tickets to identify what's driving low 
customer satisfaction and where the support process needs improvement.

## 🔗 Live Dashboard
[View the interactive Tableau dashboard](https://public.tableau.com/app/profile/priya.gurung7332/viz/Tableau_FlipkartAnalysis/FlipkartCustomerSupportAnalyticsDashboard?publish=yes)

## 🛠️ Tools Used
SQL (SQLite), Python (pandas, Seaborn), Tableau

## 📊 Key Findings
- **Response time is the biggest driver of CSAT** — satisfaction drops steadily 
  from 4.49 (replies under 5 min) to 3.77 (3+ hour replies).
- **Email is the weakest channel** (CSAT 3.91) vs calls (4.26-4.27) — likely 
  because it's slower for back-and-forth.
- **Cancellation has low CSAT (3.99) despite low volume** — a bigger problem 
  than its ticket count suggests, unlike Returns (high volume, still 4.35 CSAT).
- **Big gap between agents** — top performers average 4.9 CSAT, bottom performers 
  as low as 1.86, pointing to a coaching opportunity.
- **Training phase (not experience) is the real weak point** — CSAT stays flat 
  after training (4.27-4.36) but dips during "On Job Training" (4.14).
- **Morning shift** has the highest ticket volume but lowest CSAT (4.19) — the 
  highest-impact shift to improve.

## 💡 Recommendations
1. Speed up response times, especially on email
2. Fix the Cancellation process
3. Strengthen agent onboarding/training
4. Training underperforming agents
5. Add support during Morning shifts

## 📁 Files
- `Flipkart_Customer_Support_Ticket_Analytics.ipynb` — full analysis (SQL + Python + Seaborn)
- `support_data_clean.csv` — cleaned dataset used for Tableau
