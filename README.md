# Job_Description_Tableau_Dashboard
This is the Tableau dashboard of Job_description dataset of world wide companies. It is the project of my one month Internship with NullClass EdTech pvt. ltd .

This project is part of my internship at **NULLCLASS**.  
It is a complete **interactive Tableau Dashboard** built using a synthetic **Job Descriptions Dataset** (`Job_descriptions.csv`).  

The dashboard provides powerful insights into **job market trends** by applying complex filters and visualizations across multiple tasks.

---

## 🚀 Features

- **Task 1:** Chart between *Preference* and *Work Type* with multiple filters (Intern, latitude < 10, excluding certain country names, job title length ≤ 10, company size < 50,000) and **time-based visibility (3–5 PM IST)**.
  
- **Task 2:** Chart between *Company Size* and *Company Name* for *Mechanical Engineer* jobs with **Asian country filter**, salary > $50K, experience > 5 years, and **portal-specific + preference filters**. Includes time-based restriction.

- **Task 3:** Map visualization where clicking on *Latitude/Longitude* opens **Google Maps location**. Filters include *Qualifications, Work Type, African countries, Preference, Company Size, Contact Person, Job Portal*. Visible only between **3–6 PM IST**.

- **Task 4:** Bar chart for **Top 10 companies** with maximum *Data Engineers (Role)* and *Data Scientists (Job Title)*, excluding Asian countries and countries starting with "C". Filters also include *Female preference, Latitude < 10, Date range, Qualification (B.Tech)*. Time-based visibility between **3–5 PM IST**.

- **Task 5:** Comparative chart for *India vs Germany* showing **B.Tech candidates in Full-time roles** (*Data Scientist, Art Teacher, Aerospace Engineer*). Conditions include **Experience > 2 years, Salary > $10K, Female preference, Indeed portal only, Job Posting Date < 08/01/2023**. Colored **Orange (India)** and **Green (Germany)**. Visible between **3–5 PM IST**.

---

## 🛠 Tools & Technologies

- **Tableau Desktop** → Data visualization & dashboard creation  
- **Python (Pandas, NumPy, Jupyter)** → Data preprocessing for cleaning fields like *Salary Range* and *Experience*  
- **GitHub** → Version control & project hosting  

---

## 📊 Dataset

- **File:** `Job_descriptions.csv`  
- **Description:** Synthetic dataset of job postings across industries, used for educational & research purposes.  
- Columns include: Job Id, Experience, Qualifications, Salary Range, Location, Country, Latitude, Longitude, Work Type, Company Size, Job Posting Date, Preference, Job Title, Role, Job Portal, Company Name, etc.  

---

## 📌 Key Learnings

- Advanced filtering in Tableau using **calculated fields** (string, numeric, LOD, and time-based).  
- Building dashboards that adapt to **time constraints (IST)**.  
- Interactive **map-based navigation** using Latitude & Longitude with URL actions.  
- Cleaning and converting string-based columns (*Salary Range, Experience*) into numeric fields for analysis.  

---

## 📷 Dashboard Previews

<img width="1640" height="793" alt="image" src="https://github.com/user-attachments/assets/8620a4eb-ca2d-43f7-acd7-da85e08c05fb" />


---

## 📜 How to Run

1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/job-description-tableau-dashboard.git

