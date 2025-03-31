![aircraft Safety](images/portrait-smiling-pilot-with-airplane-him.jpg)

# **Aviation Safety Analysis: Identifying Low-Risk Aircraft for Business Expansion**

**Author:** [Janine Makorre](janine.makorre@student.moringaschool.com)
---

## **Overview**

This project analyzes aviation accident data to uncover critical safety trends, assess aircraft reliability, and provide data-driven recommendations for strategic decision-making. Through data cleaning, visualization, and statistical analysis, we identify high-risk aircraft models, evaluate engine performance, and explore factors influencing accident severity.  

### **Key Highlights:**  
✅ **Comprehensive Data Cleaning:** Removed inconsistencies, handled missing values, and ensured dataset integrity.  
✅ **Insightful Visualizations:** Identified patterns in accident frequency, aircraft types, and injury severity.  
✅ **Business-Oriented Recommendations:** Provided actionable insights on safer aircraft models, engine types, and operational improvements.  

This analysis serves as a valuable resource for aviation stakeholders, including airline operators, manufacturers, and safety regulators, aiming to enhance aviation safety and investment strategies.

## **Business Problem** 
![Aircraft and Money](images/photorealistic-money-with-plane.jpg)

Our company, is expanding into the aviation industry to diversify its portfolio. Specifically, we are looking to purchase and operate aircraft for both commercial and private enterprises. However, we lack expertise in aircraft safety, performance, and risk assessment, making it difficult to make informed investment decisions.

To mitigate risks and ensure a strategic, data-driven entry into the aviation market, we must identify which aircraft models pose the lowest risk and provide clear, actionable insights that will guide purchasing decisions for the company’s new aviation division.

### **Key Stakeholders**
- **Company Executives & Investors:** Need data-backed recommendations to justify aviation investments.

- **Aviation Division Leadership:** Requires insights on which aircraft to purchase based on safety and performance.

- **Regulatory & Safety Authorities:** Ensuring compliance with aviation safety standards.

- **Private and Commercial Clients:** Businesses and individuals who will use the aircraft for transportation.

### **Key Business Questions**

1. Which aircraft models and engine types have the lowest accident rates?
2. Are there specific aircraft features (e.g., engine type, number of engines) that contribute to lower risk?
3. What types of aircraft should our company prioritize for investment to maximize safety and profitability?

## **Data**  

This project analyzes aviation accident data to identify **low-risk aircraft models** for investment. The dataset, sourced from the [National Transportation Safety Board (NTSB)](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses), contains detailed records of aviation incidents spanning **1962 to 2023**.  

### **1. Main Dataset: Aviation Accident Data**   
This dataset consists of **88,889 records across 31 columns**, providing insights into:  
- **Accident details** – Date, location, severity, and investigation status.  
- **Aircraft specifications** – Make, model, engine type, and category.  
- **Injury reports** – Number of fatalities, serious injuries, and uninjured passengers.  
- **Operational and environmental factors** – Flight purpose, weather conditions, and aircraft damage.  

### **2. Supporting Dataset: U.S. State Codes**   
A small reference dataset with **62 records**, mapping full U.S. state names to their abbreviations. This was used to **standardize location data for improved analysis**.  

Together, these datasets allowed us to **uncover trends in aviation safety, assess accident risks, and guide aircraft investment decisions**.

## **Methods**

This project employs descriptive analysis to explore trends in aviation accidents over time. By examining factors such as aircraft type, engine configuration, and accident severity, we identify patterns that can help assess operational risks and aircraft safety. This analysis provides data-driven insights to support the company's decision-making in aircraft acquisition and risk management.

## **Results**
The analysis shows that **smaller general aviation aircraft** have **higher average fatal injuries**, while **commercial manufacturers like Boeing and Airbus** have lower rates due to stricter safety regulations and better engineering. This helps identify **riskier aircraft makes** for investment decisions.

![Fatalities by aircraft make](images/average_fatal_injuries_by_make.png)

The analysis also reveals that piston-engine aircraft have higher fatality rates, while jet and turboprop engines show better safety records. This highlights the importance of investing in multi-engine turbine aircraft for improved reliability and risk reduction.

![Accident severity by engine type](images/injuries_and_engine_type.png)

The data shows that certain aircraft models are consistently involved in high-fatality incidents, suggesting a higher operational risk. Understanding these trends helps in making safer investment choices by prioritizing models with lower fatality records.

![Fatalities by aircraft model](images/fatal_injuries_by_model.png)

## **Conclusion and recommendations**
### **Summary of findings** 
- **Amateur-built aircraft tend to have higher accident rates** than certified commercial models.
- **Single-engine aircraft are more vulnerable** to fatal accidents compared to multi-engine planes.
- **Turboprop and jet engines offer better reliability and safety** than piston engines.

### **Data-Driven Recommendations**
✅ **Prioritize Commercial & Certified Aircraft**: Investing in well-established, certified aircraft enhances safety and reliability.
✅ **Choose Multi-Engine Aircraft**: They provide redundancy, reducing the risk of total engine failure.
✅ **Invest in Turboprop & Jet-Engine Planes**: These engines are more efficient and have lower accident rates.

## **Next Steps**
* Machine Learning for Risk Prediction – Build models to predict accident severity based on aircraft specs and conditions.
* AI for Accident Reports – Use NLP to analyze pilot narratives for hidden safety insights.
* Real-Time Safety Monitoring – Develop an AI dashboard to track trends and manufacturer reliability.
* Automated Risk Scoring – Create a tool to rate aircraft safety for smarter investment decisions.

Leveraging AI and machine learning will enhance data-driven risk management and improve decision-making in aviation investments.

##  Additional Resources
**Project Notebook:** [GitHub Repository](git@github.com:Uxer-Janine/FlightRisk-Aviation-Accident-Analysis.git)* 

**Interactive Dashboard:** [Tableau Visualization](https://public.tableau.com/views/Aviation-Accident-Analysis-2025-3-30-JRM/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)*


🔹 **Author:** Janine Robi Makorre  
🔹 **Contact Info:** [My email](janine.makorre@student.moringaschool.com), [LinkedIn Profile](https://www.linkedin.com/in/janine-makorre-30a456179/) 

🔹 **License:** MIT  

*This project aims to improve aviation safety through data-driven insights. Let’s make the skies safer together!*

