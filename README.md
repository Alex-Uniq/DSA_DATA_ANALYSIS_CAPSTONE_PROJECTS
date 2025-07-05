# DSA_PROJECT_ 📊 Amazon Product Review Analysis Report 

**Author:** Obiekezie Precious Chinaza  
**Role:** Data Analyst  
**Tools Used:** Google Sheets and WPS Office (Mobile)
**Focus Areas:** Product Reviews • Pricing Strategy • Discount Patterns • Customer Sentiment  
**Dataset:** Amazon Product Listings and Reviews (1,465 rows, 16 columns)  

---

## 📈 Executive Summary

This project involved the analysis of an Amazon product review dataset comprising **1,462 products** across various categories. Using pivot tables and spreadsheet calculations, the analysis uncovers key business insights in pricing, customer reviews, ratings, and potential revenue.

Notable findings include:
- Electronics dominate both in volume and revenue potential  
- Over **50% of products** offer discounts ≥ 50%  
- Low-rated products receive deeper discounts  
- Most products fall into the **mid-price range ($501–$5,000)**  

---

## 🔧 Data Cleaning Summary

- Removed duplicate or empty product rows  
- Standardized product categories  
- Grouped prices into buckets  
- Created calculated fields:
  - **Discount %**
  - **Revenue = Actual Price × Rating Count**
  - **Rating Groups**
  - **Rating × Review Score**
 
---

## 📊 Analysis by Business Questions

### 1. Number of Products per Category  
| Category | Product Count |
|----------|---------------|
| Electronics | 526  
| Computers & Accessories | 451  
| Home & Kitchen | 447  
| Office Products | 31  
| Others | < 3 per category  

---

### 2. Average Discount by Category  
| Category | Avg. Discount |
|----------|----------------|
| Home Improvement | 57.5%  
| Computers & Accessories | 53.9%  
| Health & Personal Care | 53.0%  
| Electronics | 50.8%  
| Office Products | 12.4%  

---

### 3. **Total Number of Reviews per Category**
Displayed as a **clustered column chart** in the dashboard. Electronics has the highest review count.

### 4. **Top 5 Products with Highest Average Ratings**
- Amazon Basics Wireless Mouse - 5.0
- Syncwire LTG to USB Cable - 5.0
- Instant Pot Air Fryer - 4.8
- Oratech Coffee Frother - 4.8
- Swiffer Instant Water Heater - 4.8

### 5. **Average Actual vs Discounted Price per Category**
| Category | Actual Price | Discounted Price |
|----------|--------------|------------------|
| Electronics | $10,127.31 | $5,965.88 |
| Home & Kitchen | $4,165.79 | $2,331.13 |
| Others... | ... | ... | 
See file attached. 

### 6. **Top 5 Products with Highest Review Count**
- AmazonBasics HDMI Cable (3-Foot) — 3,757,358 rating score  
- Others listed in dashboard with rating × review counts.

### 7. **Number of Products with ≥ 50% Discount**
**749** products offer ≥ 50% discount 

### 8. **Distribution of Product Ratings**
Most products are rated between 3.8 and 4.4. Full breakdown in bar chart (dashboard).

### 9. **Total Potential Revenue by Category**
Potential revenue = `Actual Price × Rating Count`.  
Electronics leads with over **$98 billion**.

### 10. **Number of Unique Products per Price Range**
| Bucket | Count |
|--------|-------|
| Low (< $500) | 220 |
| Mid ($501 – $5,000) | 921 |
| High ($5,001 – $20,000) | 224 |
| Luxury (> $20,000) | 97 |

### 11. **Relationship Between Rating and Discount**
| Rating Group | Avg. Discount |
|--------------|----------------|
| Low (< 3.0) | 64.00% |
| Medium (< 4.0) | 52.50% |
| High (≥ 4.0) | 46.07% |

### 12. **Products with Fewer than 1,000 Reviews**
**325** products.

### 13. **Categories with the Highest Discounts**
- Home Improvement (57.5%)
- Computers & Accessories (53.9%)
- Health & Personal Care (53%)

### 14. **Top 5 Products Based on Rating × Reviews Combined**
- AmazonBasics HDMI Cable – **3.75M**
- Amazon Basics High-Speed HDMI (2-pack) – **1.88M**
- Amazon Basics High-Speed HDMI Cable,Black - **1.88M**
- JBL Wired Earphones – **1.57M**
- boAt Bassheads – **1.49M**

---

## 🧠 Key Insights

- High rating does not always equate to highest review count.
- 📉 Lower-rated products are more heavily discounted to boost appeal  
- 💰 Electronics yield the highest potential revenue and sales volume. 
- 🧾 Most products are priced between $501–$5,000  
- 📦 Categories like Office Products and Toys have minimal listings
- Some product names are repeated but vary by minor attributes (color, pack, etc.), influencing the average ratings and review counts.

---

## 🧠 Recommendations

1. **Optimize Discounts**  
   - Review discount strategies for low-rated products. Consider quality improvements instead of high markdowns.

2. **Focus on High-Value Categories**  
   - Expand Electronics and Computers categories; they offer the best ROI in volume and revenue.

3. **Target Mid-Priced Product Optimization**  
   - Most products fall in the mid-price range. Improve quality and customer satisfaction in this band.

4. **Enhance Product Review Strategy**  
   - Encourage reviews for lesser-known products with fewer than 1,000 ratings.

---

## 📌 Author Info

**Name:** Obiekezie Precious Chinaza  
**Email:** precious.obiekezie100@gmail.com 
**Location:** Kaduna State, Nigeria. 

> This project reflects the power of data analysis with limited tools, handled entirely on a smartphone platform.




---




# 📊 Palmora Group HR Analytics Report

**Author:** Obiekezie Precious Chinaza  
**Role:** HR Data Analyst  
**Tools Used:** Excel (Mobile - WPS)  
**Focus Areas:** Gender Equality • Salary Structure • Regional Compliance • Bonus Allocation  

---

## 📈 Executive Summary

This report presents a detailed analysis of HR data for **Palmora Group**, focusing on gender-related issues, pay structure, performance ratings, and compliance across three operating regions: **Abuja, Kaduna, and Lagos**.

Key insights reveal:
- Evidence of a gender pay gap  
- Low compliance with the $90,000 minimum salary regulation  
- Imbalanced gender distributions across departments  

Visualizations and pivot tables were used to guide strategic recommendations for addressing inequalities and aligning compensation structures.

---

## 🔧 Data Cleaning Summary

- Replaced missing gender values with `"Undisclosed"`  
- Removed rows with missing salary values  
- Deleted rows where department was `"NULL"`  
- Renamed `"Location"` column to `"Region"`  
- Added calculated columns:
  - **Bonus %**
  - **Bonus Amount**
  - **Total Pay**
  - **Salary Band**

---

## 📊 Analysis by Case Questions

### 1. Gender Distribution (Overall, Region, and Department)

**Table: Gender Distribution – Company-wide**
- Female: 441  
- Male: 465  
- Undisclosed: 40  

**Table: Gender Distribution by Region**
- Balanced gender split in **Abuja**  
- **Kaduna** and **Lagos** slightly male-heavy  

**Table: Gender Distribution by Department**
- **Support, HR, and Services** are more balanced  
- **Legal** and **Engineering** show male dominance  

---

### 2. Performance Ratings by Gender

**Table: Performance Ratings by Gender**
- Rating distribution is relatively even  
- **Females** have higher counts in *Very Good* and *Good* ratings  

---

### 3. Gender Pay Gap Analysis

**Table: Average Salary by Gender**
- Female: `$72,136`  
- Male: `$74,790`  
- Undisclosed: `$78,368`  

**Table: Average Salary by Gender by Region**
- Gender pay gap in all regions (*Male > Female*)  
- **Abuja and Kaduna** show ~$2,500–$3,000 gaps  

**Table: Average Salary by Gender by Department**
- Gaps exist in most departments  
- Notable disparities in **Legal**, **Engineering**, and **Services**  

---

### 4. Compliance with $90,000 Minimum Salary Regulation

**Table: Salary Band Distribution**
- **654 of 946 employees** earn below $90k (~69%)  
- Only **31%** are compliant  

**Table: Salary Band by Region**
- **Lagos** has the highest number below $90k  
- **Abuja** slightly better, followed by **Kaduna**  

---

### 5. Bonus and Total Pay Calculation

**Bonus Rules Applied** (Based on Performance Rating):
- *Very Poor*: 0%  
- *Poor*: 5%  
- *Average*: 10%  
- *Good*: 15%  
- *Very Good*: 20%  

**Table: Bonus Amount by Region**
- **Kaduna**: `$825,912`  
- **Abuja**: `$801,144`  
- **Lagos**: `$567,054`  

**Table: Total Pay by Region**
- **Kaduna**: `$27.48M`  
- **Abuja**: `$24.92M`  
- **Lagos**: `$19.52M`  

**Table: Company-Wide Totals**
- **Total Bonus Paid**: `$2.19M`  
- **Total Salary + Bonus**: `$71.92M`  

---

## ✅ Final Recommendations – Palmora Group HR Analysis

1. **Address Gender Pay Gaps**
   - Prioritize salary audits in **Legal**, **Engineering**, and the **Lagos region**, where pay disparities are most pronounced.
   - Implement transparent salary bands and ensure **equal pay for equal roles** across genders.

2. **Enforce $90,000 Minimum Salary Policy**
   - With **~69% of employees earning below $90k**, focus remediation efforts on **Lagos** and **Support-related roles**.
   - Review compensation structures and **phase in salary adjustments** to meet regulatory standards.

3. **Maintain Fair Bonus Allocation**
   - Standardize bonus calculations based on performance ratings and ensure **uniform application** across all regions and departments.
   - Publish clear **internal bonus policies** to enhance trust and reduce bias.

4. **Improve Gender Representation**
   - Increase female hiring and retention in **technical and male-dominated departments** (e.g., Engineering).
   - Introduce **anonymous employee feedback systems** to monitor workplace fairness and equity.


---

## 👤 Analyst Profile

**Obiekezie Precious Chinaza**  
_First-Class Biochemistry Graduate_  
📧 Email: precious.obiekezie100@gmail.com
📍 Region: Nigeria  

> This analysis was developed entirely on **mobile (WPS Office)**, showcasing analytical excellence under technical constraints.

-- 
