# National Social Assistance Programme (NSAP) Analysis

## Project Overview
This project analyzes the **National Social Assistance Programme (NSAP)** dataset for the year 2024.  
The goal is to understand patterns and trends in India’s social welfare distribution, focusing on the number of beneficiaries, digital coverage (Aadhar and mobile linkage), and caste-wise inclusion across states and union territories.  
The analysis is performed using **PySpark** for data processing and **Pandas, Seaborn, and Matplotlib** for visualization.

---

## Dataset
**File:** `data/National_social_assistance_programme.csv`  
**Description:** Contains detailed information about NSAP beneficiaries, including state-wise distribution, caste classification, and digital coverage indicators.

### Key Features
- `state_name` – Name of the state or union territory  
- `total_beneficiaries` – Total number of beneficiaries under NSAP  
- `total_aadhar` – Number of beneficiaries linked with Aadhar  
- `total_mobileno` – Number of beneficiaries with registered mobile numbers  
- `total_sc` – Total number of Scheduled Caste (SC) beneficiaries  
- `total_st` – Total number of Scheduled Tribe (ST) beneficiaries  
- `total_obc` – Total number of Other Backward Class (OBC) beneficiaries  
- `total_gen` – Total number of General category beneficiaries  

---

## Project Objectives
- Explore and clean the dataset using **PySpark**  
- Perform statistical analysis to calculate totals, averages, and category distributions  
- Visualize key insights using **Seaborn** and **Matplotlib**  
- Provide a summary of trends and patterns to evaluate digital coverage, inclusiveness, and program reach  

---

## Folder Structure
NSAP_Analysis/
│── data/ # Dataset (.csv file)
│── plots/ # Saved charts (optional)
│── National_Social_Assistance_Programme.ipynb
│── README.md
│── requirements.txt # Python packages

---

## Libraries Used
- Python 3.x  
- PySpark  
- Pandas  
- Seaborn  
- Matplotlib  

---

## How to Run
1. Clone or download this repository  
2. Place the dataset in the `data/` folder  
3. Open `National_Social_Assistance_Programme.ipynb` in Jupyter Notebook  
4. Run all cells sequentially  
5. Visualizations will appear in the notebook (can also be saved in the `plots/` folder)  

---

## Key Visualizations
- **Top 10 States by Total Beneficiaries:** Bar chart showing states with the highest number of beneficiaries  
- **State-wise Aadhar Coverage:** Bar chart showing the percentage of beneficiaries linked with Aadhar  
- **State-wise Mobile Number Coverage:** Bar chart showing beneficiaries with registered mobile numbers  
- **State-wise Caste Percentage Distribution:** Grouped bar chart comparing SC, ST, OBC, and GEN proportions  
- **National Caste-wise Beneficiary Distribution:** Pie chart showing caste representation at the national level  

---

## Insights
- States like **Uttar Pradesh, Maharashtra, and West Bengal** account for the highest number of beneficiaries, showing regional concentration  
- **Aadhar coverage** is strong nationwide (approximately 85–90%), while **mobile number coverage** is slightly lower in some regions  
- **OBC and SC groups** make up the majority of beneficiaries, reflecting inclusive targeting, though **ST representation** remains limited  
- Data reveals **digital readiness** in many states but also highlights gaps in mobile linkage and regional disparities  
- The findings indicate that enhanced digital inclusion can improve efficiency and transparency in benefit delivery  

---

## Optional Future Work
- Include fund allocation and disbursement tracking to measure efficiency  
- Add year-wise or monthly trends for temporal analysis  
- Develop interactive dashboards for policy monitoring and decision-making  

---

## Requirements
Install the required Python packages:
```bash
pip install -r requirements.txt
