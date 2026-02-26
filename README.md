# Resume-to-Job Market Gap & Recruiter Decision Analytics

## 📌 Project Overview
This project analyzes resume data to understand **what factors influence recruiter hiring decisions**.  
Using analytical techniques and business-driven metrics, the project identifies **skill gaps, salary mismatches, and role-specific hiring patterns**, helping candidates improve their chances of being hired.

The focus is on **explainable data analytics**, not predictive modeling.
                                                                                                             
---
                                                        
## 🎯 Business Objectives                                                                                
- Identify key factors influencing recruiter hire vs reject decisions                        
- Analyze skill demand across different job roles
- Detect salary expectation mismatches leading to rejection
- Design a Resume Strength Index to evaluate profile quality
- Perform exception analysis to identify high-quality rejected candidates

---

## 📊 Dataset Description
- **Source:** Public resume dataset (1,000 candidate profiles)
- **Key Features:**
  - Skills (multi-skill text field)
  - Experience (Years)
  - Education
  - Certifications
  - Job Role
  - Recruiter Decision (Hire / Reject)
  - Salary Expectation
  - Projects Count
  - AI Resume Score

---

## 🛠 Tools & Technologies
- **Python:** Data cleaning, preprocessing, analysis
- **Pandas & NumPy:** Data manipulation
- **Matplotlib & Seaborn:** Exploratory analysis
- **Power BI:** Interactive dashboard & business storytelling
- **DAX:** Custom measures and KPIs

---

## 🔍 Analytical Approach
1. Data understanding and cleaning
2. Hiring outcome analysis (Hire vs Reject)
3. Skill-level impact analysis
4. Job role–wise hiring trends
5. Salary expectation vs experience analysis
6. Resume Strength Index (business metric)
7. Exception analysis to identify process failures

---

## 📈 Power BI Dashboard Pages
1. **Hiring Overview:** Overall hiring funnel and KPIs  
2. **Skill Impact Analysis:** Skills that increase hiring probability  
3. **Resume Strength vs Hiring:** Why strong resumes get rejected  
4. **Salary Expectation Analysis:** Salary mismatch insights  
5. **Exception Analysis:** High-quality rejected candidates  

---

## 💡 Key Insights
- High AI scores alone do not guarantee hiring
- Skill alignment with job role is a major hiring factor
- Salary overestimation leads to rejection even for strong profiles
- Some high-quality candidates are rejected due to non-technical reasons

---

## 📌 Business Recommendations
- Candidates should align skills with role-specific demand
- Salary expectations should be benchmarked against experience
- Recruiters can improve hiring accuracy by reviewing exception cases
- Resume evaluation should use composite metrics, not single scores

---

## 📂 Project Structure
Resume-Job-Market-Gap-Analytics/
├── Resume-Data.csv
├── Resume_Analysis.ipynb
├── data_cleaned.csv
├── powerbi/
│     ├── Resume_Job_Market_Gap_Analytics.pbix
├── README.md
└── requirements.txt

---

## 🚀 How to Run the Project
1. Clone the repository
2. Install dependencies:
3. Run the file `Resume_Analysis.ipynb`
4. Open the Power BI dashboard from `powerbi/`
