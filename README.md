# E-Commerce Customer Sentiment & Operational Risk Analytics

## Executive Summary
This project delivers a comprehensive data analytics solution that transforms over 23,000 unstructured women's e-commerce customer reviews into actionable corporate strategy. By engineering an end-to-end pipeline in Power BI and Power Query, the analysis uncovers critical operational risks hidden beneath strong baseline brand metrics. The final executive dashboard enables stakeholders to isolate severe quality-control anomalies, map customer advocacy thresholds, and deploy targeted, revenue-protecting sourcing interventions.

## Business Problem
On the surface, the retail brand displays strong health indicators with a 4.2/5 baseline rating and an 82% customer recommendation rate. However, traditional high-level reporting masked severe underlying operational and sourcing inefficiencies. The business lacked visibility into how negative feedback scales across digital communities, where the operational breakdowns were concentrated, and whether specific age demographics required unique product adaptations. Without these granular insights, the company faced unmitigated risks to customer lifetime value (LTV) and brand loyalty.

## Objectives
- **Build an End-to-End Analytics Pipeline:** Ingest, clean, and model 23,000+ raw, unstructured customer review rows within a high-pressure development sprint.
- **Isolate Operational Firepoints:** Utilize data segmentation and text mining to pinpoint the exact product categories driving customer dissatisfaction.
- **Quantify Consumer Advocacy:** Measure the precise mathematical relationship between star ratings, community engagement, and referral intent.
- **Deliver Executive-Ready Reporting:** Design a high-density, intuitive dashboard featuring a unified KPI banner and structured navigation to support rapid strategic decisions.

## Dataset
- **Dataset Size:** 23,000+ customer reviews.
- **Data Attributes:** Quantitative metrics (ratings, upvotes, age demographics, recommendation flags) combined with qualitative text features (review titles, body text, product classes).
- **Data Quality:** Handled missing text segments, standardized inconsistent category labels, and engineered clean demographic buckets for uniform analysis.

## Tech Stack
- **Data Engineering:** Power Query (ETL, data cleaning, structural transformations)
- **Data Modeling:** Power BI Desktop (Star schema optimization, relationship mapping)
- **Analytics & Calculations:** DAX (Data Analysis Expressions) for dynamic measures
- **Visualization:** Power BI Reporting Layer (Executive UI design, custom KPI banner cards)

## Methodology (or Approach)
1. **ETL & Data Engineering:** Extracted raw text data into Power Query. Standardized data types, removed null values, and parsed unstructured feedback into structured marketing and product segments.
2. **Data Modeling:** Structured a highly efficient data model to handle seamless cross-filtering across product classes, age groups, and rating categories.
3. **Sentiment & Text Mining:** Isolated high-frequency phrases within low-scoring reviews to differentiate style preferences from genuine manufacturing defects.
4. **UI/UX Dashboard Architecture:** Engineered a cohesive 4-card KPI banner displaying critical baseline metrics. Applied strict visual hierarchy principles, utilizing interactive filters for on-the-fly exploration while relocating complex text clouds to external documentation to protect dashboard real estate.

## Dashboard Preview
*Insert a high-quality screenshot or an animated GIF of your Power BI dashboard here.*

## Key Insights
- **The Viral Risk of Complaints:** While 5-star reviews dominate total data volume, a single 1-star review generates **50.4% more community upvotes and engagement** than a positive one. Negative feedback is heavily amplified by online shoppers.
- **The Advocacy Tipping Point:** Customer loyalty is a steep cliff, not a gradual slope. Customer referral intent remains safe at 4 stars (**96% recommendation rate**), but the second a product falls to 3 stars, intent plummets straight down to **41%**.
- **Concentrated Sourcing Failures:** Operational quality issues are highly isolated rather than systemic. Out of dozens of product lines, just two classes—**Dresses and Knits**—drive the vast majority of all 1 and 2-star ratings. 
- **Textual Evidence of Defect:** Text mining revealed that poor ratings are not driven by style or aesthetic preferences. Detractors consistently flag physical manufacturing flaws, specifically **severe sizing discrepancies and sub-standard fabric quality**.
- **Uniform Consumer Expectations:** Customer demands for quality are completely universal across generations. Data analysis across age demographics (from Gen Z to Seniors) showed nearly identical satisfaction distribution patterns; product quality expectations do not change with age.

## Business Recommendations
- **Deploy Targeted Sourcing Audits:** Immediately audit manufacturing standards and material choices specifically for the **Dresses and Knits** categories to halt negative feedback loops.
- **Revamp Digital Sizing Frameworks:** Update e-commerce sizing charts and integrate interactive fit-calculators on product pages to proactively mitigate sizing mismatches before purchase.
- **Establish an Operational Intervention Threshold:** Implement automated alerts for product teams the moment a product's average rating drops toward **3.5 stars**, allowing teams to intervene before hitting the 3-star advocacy cliff.
- **Prioritize Customer Review Escalation:** Re-engineer the customer service workflow to flag and resolve highly upvoted 1-star reviews immediately, mitigating their viral amplification impact on the digital storefront.

## Connect with Me
- **LinkedIn:** https://www.linkedin.com/in/Basil-Michael-Ifeagwa
- **GitHub:** https://github.com/VLogicBoard
- **Email:** ifeagwabasil@gmail.com