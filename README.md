# Renewable-Energy-Adoption
Analyzing renewable energy adoption across U.S. states and business sectors.

## About This Project
This project explores **renewable energy adoption rates across U.S. states and business sectors**. 
The dashboard provides stakeholders with a clear picture of:  
- Which states are leading vs lagging in adoption.  
- Which business sectors are outperforming or struggling.  
- Where opportunities exist for improvement and investment.

  Built using **Python** for data preparation and **Tableau** for visualization.  

---

## Key Business Questions Answered  
1. What is the overall market adoption rate across U.S. states and sectors?  
2. Which states show the highest and lowest adoption rates?  
3. Which business sectors are performing better than others?  
4. Where are the gaps — sectors that underperform within strong states, or vice versa?  
5. How can this information guide resource allocation and policy decisions?
   
---

## Data Sources  
- `adoption_by_region.csv` → Adoption rate by state.  
- `adoption_by_sector.csv` → Adoption rate by business sector.  
- `merged_for_tableau.csv` → Combined state × sector data for deeper analysis.  

---

## 🛠Workflow  

### 1. Data Preparation (Python / Pandas)  
- Cleaned column names, ensured consistency, and validated adoption rates.  
- Combined datasets into a state–sector matrix for Tableau heatmap analysis.  
- Exported clean CSVs into the `data/` folder.  

### 2. Data Visualization (Tableau)
Built an interactive dashboard with multiple views:  
- **US Map (State Adoption):** geographic hotspots vs laggards.  
- **Bar Chart (Sector Adoption):** ranking of sectors by adoption rate.  
- **Heatmap (State × Sector):** shows where sectors over/underperform relative to state averages.  
- **Dual-Axis Chart:** compares adoption rate vs uplift potential.  
- **KPIs:** highlights national adoption averages.  

---

## 📊 Business Insights  
- **National Adoption Rate:** 20%  
- **Top State:** California (32.5%)  
- **Lowest State:** West Virginia (15.3%)  
- **Top Sector:** Housing Co-op (30.9%)  
- **Lowest Sector:** Nonprofits (14.3%)  

### Key Takeaways:  
- Innovation-driven states like **California, Massachusetts, and New York** lead adoption.  
- **Housing Co-ops and collective models** consistently outperform other sectors.  
- **Nonprofits underperform**, pointing to barriers such as funding or regulatory constraints.  
- Adoption varies widely across the U.S., highlighting opportunities for targeted support.  

---

## 📸 Dashboard Preview  

<img width="1600" height="886" alt="image" src="https://github.com/user-attachments/assets/8d955079-d21b-437c-9de2-39da4884369f" />

[View the Interactive Dashboard on Tableau Public](https://public.tableau.com/views/Renewableenergyadoption/RenewableEnergyAdoptionDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  

---

## 💡 Applications for Stakeholders  
- **Resource Allocation:** Focus on low-performing states and sectors for maximum impact.  
- **Benchmarking:** Learn from adoption leaders and replicate successful models.  
- **Strategic Planning:** Identify where adoption uplift will deliver the best ROI.  
- **Policy & Incentives:** Use evidence-based insights to support lagging areas.  

---

## Tech Stack  
- **Python**: pandas, numpy (data cleaning and preparation)  
- **Tableau Desktop & Public**: interactive dashboards 
