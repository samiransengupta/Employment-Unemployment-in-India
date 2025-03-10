# 📊 Employment & Unemployment in India

While India's official unemployment rate is **3.2%** (PLFS 2023-24), **pre-election surveys in 2024** indicated that employment remains a **top concern**. Our client needed a **deep, data-backed analysis** to uncover the **true employment scenario**.

## **🚀<img width="422" alt="employment_indicators_plfs" src="https://github.com/user-attachments/assets/6cfdfa46-7f76-4f88-bdcb-12827f4a2498" />
 The Challenge**  
The **Periodic Labour Force Survey (PLFS)** follows a **complex methodology**—understanding its **survey design, weighting techniques, and unique identifiers** was critical for **accurate analysis**. The dataset contains **millions of rows**, making **efficient data handling** a major challenge.  

Moreover, a **detailed understanding of the PLFS instruction manual** was essential, as it provides crucial guidelines on **household/person-level identification, survey weights, and data extrapolation methods**. A misinterpretation could lead to **flawed insights and poor decision-making**, making **methodological accuracy a top priority**.  

## **🔍 Key Insights**  
- **Urban women face an unemployment rate of 7.1%—more than twice the national average.**  
- **Youth unemployment (ages 15–29) exceeds 10%.**  
- **Graduates (13%) and postgraduates & above (12.4%) have the highest joblessness.**  
- **Unemployment among postgraduates is rising—12.4% in 2023-24, up from 12.1% (2022-23) and 11.4% (2021-22).**  
- **Only 19.8% of employed individuals hold regular wage/salaried positions—a steady decline from 20.9% (2022-23) and 21.5% (2021-22).**  
- **Self-employment is rising, signaling greater informalization in India’s labor market: 58.7% in 2023-24, up from 57.3% (2022-23) and 55.9% (2021-22).**  

The **client found these insights highly valuable** and requested a **detailed report** exploring **Worker Population Ratio (WPR), Labour Force Participation Rate (LFPR), and unemployment trends** across **rural-urban divides, gender, age cohorts, religion, and caste**.  

### **💡 My Role:**  
I played a **leading role** in structuring these insights into **comprehensive data tables**, ensuring they met the **client’s analytical and reporting needs**. My approach **streamlined the reporting process**, making the data **more accessible, actionable, and ready for decision-making**.  

---

## **🏆 Business Impact**  
✅ **True Picture Unveiled** – Our analysis exposed **hidden employment trends**, enabling the client to make **data-driven decisions**.  
✅ **Cost & Time Efficiency** – The team initially relied on **Excel & Stata**, but I **introduced Pandas**, which **streamlined data extraction**, significantly **reduced processing time**, and ensured **project completion ahead of schedule**.  
✅ **Accuracy & Reliability** – By applying **rigorous data validation techniques**, we delivered **error-free, high-quality insights**, boosting the client’s **confidence in the findings**.  

---

## **📖 Learning Experience**  
This project was a **rich learning experience**, from **leveraging Pandas for efficient text data extraction** to **deep-diving into PLFS’s survey methodology**. The **PLFS dataset is invaluable** for analyzing **India’s labor market, demography, education levels, and workforce informalization**. Our data team has since **leveraged PLFS insights in multiple projects**, creating **ad-hoc reports** for policymakers and researchers.  

---

## **⚙️ Technical Approach**  
- **Data Source:** Periodic Labour Force Survey (PLFS) – Government of India  
- **Tools Used:** Python (Pandas, NumPy), Excel, STATA  
- **Important Documentation & Data Files:**  
  - **PLFS Data Layout**  
  - **Instruction Manuals**  
  - **Raw Data (.txt) Files**  
  - 🔗 **[PLFS Official Website](https://www.mospi.gov.in/)**  

---

## **📊 Key Variables in Analysis**  

| **Column Name**                  | **Description**  |  
|-----------------------------------|-----------------|  
| `Sector`                          | Urban / Rural classification |  
| `State/UT Code`                   | Identifies the state/union territory |  
| `Sex`                              | Gender of the individual |  
| `Age`                              | Age in completed years |  
| `Marital Status`                   | Current marital status |  
| `General Education Level`          | Education qualification (Graduate, Secondary, etc.) |  
| `Technical Education Level`        | Technical diploma/certifications |  
| `Religion`                         | Religious affiliation |  
| `Social Group`                     | SC/ST/OBC/General classification |  
| `Final Weight`                     | Weighting factor for population estimates |  
| `Usual Principal Status Code`      | Usual Principal Activity |  
| `Usual Subsidiary Status Code`     | Subsidiary Activity |  

---

## **📊 Labour Force Estimation Methodology**  
📌 **According to PLFS documentation, labour force estimates follow two approaches:**  
1️⃣ **Usual Status (ps+ss) Approach** – Considers both **principal and subsidiary activities** over **365 days**.  
2️⃣ **Current Weekly Status Approach** – Based on **work activity during a short reference period**.  

### **📌 Method Used in This Analysis**  
✅ **We used the "Usual Status (ps+ss) Approach"** 

📌 **Definition of Labour Force under Usual Status:**  
see the image
.<img width="422" alt="employment_indicators_plfs" src="https://github.com/user-attachments/assets/3cd86cef-7909-40c2-b5d9-31f25ab39040" />

## ⚠️ Important Note  
Some **proprietary calculations used to derive deeper insights have been omitted** from this repository. 

