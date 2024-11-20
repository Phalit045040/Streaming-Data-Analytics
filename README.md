# Streaming-Data-Analytics
# **ABOUT THE DATASET**
The purpose of this analysis is to explore the impact of climate change, resource utilization, and adaptation strategies on agriculture. Using data visualizations created in MongoDB Charts, this report provides insights into crop yields, economic trends, and resource distribution across regions and crop types.

The dataset contains information on various factors, including:

1. Crop types, yields, and resource usage (fertilizer, pesticides).
2. Climate variables like temperature, precipitation, and extreme weather events.
3. Economic impacts and adaptation strategies.
4. The goal is to identify actionable insights that can improve agricultural practices and inform policy-making.

# **OBJECTIVES**
The primary objective of this analysis is to provide data-driven insights into the impact of climate change, resource utilization, and adaptation strategies on agriculture. By leveraging MongoDB Charts and a rich dataset, the analysis aims to achieve the following:

Assess Climate Impacts:

1. Analyze how climate variables like temperature, precipitation, and extreme weather events influence agricultural outcomes such as crop yield and economic impact.

2. Understand Resource Utilization:
Examine the distribution of resources such as fertilizers, pesticides, and irrigation across crop types and regions to identify sustainable practices and areas for improvement.

3. Evaluate Adaptation Strategies:
Investigate the prevalence and effectiveness of various adaptation strategies across regions and their correlation with economic and agricultural performance.

4. Highlight Regional and Crop-Specific Trends:
Explore variations in agricultural performance, resource usage, and climate resilience across different countries and crop types.

5. Identify Key Contributors:
Pinpoint crops, regions, and strategies that contribute the most to economic impact and resource usage, and assess areas with the greatest vulnerability to climate change.

6. Support Policy and Decision-Making:
Provide actionable insights that can guide policymakers, agricultural stakeholders, and researchers in developing strategies to enhance agricultural resilience and sustainability.

# **DASHBOARD (MONGO DB ATLAS)**
![Agriculture (1)](https://github.com/user-attachments/assets/69fda120-9724-4093-8bf8-fbed58441ad1)


# **MANAGERIAL INSIGHTS**




### **1. Average Crop Yield Country-Wise (Line Chart)**
#### **Key Visualization:**
- A multi-line chart showing the average crop yield (metric tons per hectare) for different countries over time.

#### **Insights:**
- Countries like the **USA** and **Canada** maintain relatively high and consistent crop yields compared to others.
- Developing countries show fluctuating trends, possibly due to limited resources or the impact of climate variability.
- Overall, crop yields appear to have subtle upward trends in some regions, reflecting improved agricultural practices or adaptation strategies.

---

### **2. Average Temperature by Country (Map)**
#### **Key Visualization:**
- A choropleth map displaying average temperatures by country.

#### **Insights:**
- Warmer regions (e.g., Africa, parts of Asia) face significantly higher average temperatures, which can negatively impact crop yields and soil health.
- Cooler climates (e.g., Northern Europe, Canada) may provide more favorable growing conditions for certain crops.
- The temperature distribution highlights the critical role of regional climate adaptation strategies.

---

### **3. Economic Impact Over Years with Crop Type (Grouped Bar Chart)**
#### **Key Visualization:**
- A grouped bar chart showing economic impact (in million USD) over years, segmented by crop types.

#### **Insights:**
- High-value crops like **wheat, corn, and rice** consistently contribute the most to economic impact.
- Over the years, the economic impact shows slight fluctuations, potentially linked to extreme weather events or market demand changes.
- Specialized crops like **coffee** and **fruits** exhibit more variability, indicating dependence on region-specific climate conditions.

---

### **4. Economic Impact Over Years Due to Climate Change (Heatmap)**
#### **Key Visualization:**
- A heatmap correlating CO₂ emissions and temperature with economic impacts over time.

#### **Insights:**
- Regions with high CO₂ emissions (e.g., industrial nations) face higher economic losses, indicating a strong link between emissions and agricultural vulnerability.
- Cooler temperatures correlate with reduced economic volatility, whereas extreme temperature increases lead to greater economic losses.
- This underscores the importance of emission mitigation policies to stabilize agricultural economies.

---

### **5. Distribution of Adaptation Strategies Across Regions (Donut Chart)**
#### **Key Visualization:**
- A donut chart showing the proportion of different adaptation strategies used across regions.

#### **Insights:**
- **Crop rotation (20%)** and **organic farming (19.8%)** are the most commonly adopted strategies, reflecting their effectiveness and feasibility.
- **No adaptation** accounts for a significant portion, highlighting regions where action is needed to improve resilience against climate change.

---

### **6. Pesticide Usage by Crop Type Across Countries (Bar Chart)**
#### **Key Visualization:**
- A grouped bar chart comparing pesticide use for various crop types across countries.

#### **Insights:**
- Crops like **fruits and vegetables** have the highest pesticide usage due to pest susceptibility.
- Countries with intensive agricultural practices (e.g., the USA, China) use significantly more pesticides.
- This highlights the need for sustainable pest management solutions to reduce environmental impact.

---

### **7. Total Economic Impact Across All Records (Number Chart)**
#### **Key Visualization:**
- A single numeric visualization showing the total economic impact from the dataset.

#### **Insights:**
- The total economic impact is **6742696.58 million USD**, underscoring the significant financial value of agriculture.
- This highlights the critical role of agriculture in global economies and the need to safeguard its sustainability.

---

### **8. Top Crop by Pesticide Usage (Word Chart or Highlighted Text)**
#### **Key Visualization:**
- The word "Rice" is highlighted, indicating the crop with the highest pesticide usage.

#### **Insights:**
- **Rice** requires intensive pesticide use, likely due to high pest pressure in wet growing conditions.
- This suggests opportunities for integrated pest management (IPM) to optimize pesticide use for rice cultivation.

---

### **9. CO₂ Emissions by Country and Crop Type (Table)**
#### **Key Visualization:**
- A table summarizing CO₂ emissions by country and crop type.

#### **Insights:**
- Countries like **China and the USA** exhibit higher emissions, reflecting their industrialized agricultural practices.
- Crops like **corn and wheat** are associated with significant emissions due to large-scale production.
- The data points to opportunities for emission-reducing innovations, such as precision agriculture or carbon-efficient fertilizers.

---

### **10. Average Soil Health Index Country-Wise (Bar Chart)**
#### **Key Visualization:**
- A bar chart showing the average soil health index for each country.

#### **Insights:**
- Countries like **Canada and France** have higher soil health scores, indicating sustainable farming practices.
- Developing countries with intensive agriculture (e.g., India, Brazil) may need more soil conservation initiatives.
- Soil health strongly correlates with crop yield and economic impact.

---

### **11. Annual Climate Trends: Average Total Precipitation Over the Years (Line Chart)**
#### **Key Visualization:**
- A line chart showing average precipitation trends over time.

#### **Insights:**
- A subtle upward trend in precipitation is observed in some regions, potentially aiding crop growth.
- Year-to-year variability highlights the need for water management strategies to adapt to irregular precipitation.

---

### **12. Fertilizer and Pesticide Use Across Crop Types (100% Stacked Area Chart)**
#### **Key Visualization:**
- A stacked area chart showing the proportion of fertilizer and pesticide use for each crop type.

#### **Insights:**
- Fertilizer use dominates for staple crops like **wheat and rice**, while pesticides are more prominent in **fruits and vegetables**.
- This emphasizes the need to balance fertilizer and pesticide usage for sustainable farming.

---

### **13. Distribution of Crop Types (Donut Chart)**
#### **Key Visualization:**
- A donut chart showing the proportion of various crop types in the dataset.

#### **Insights:**
- Staples like **wheat (10.5%)** and **rice (10.2%)** dominate the crop distribution, followed by fruits and vegetables.
- Diversification of crops can improve food security and reduce reliance on specific crops.

---

### **14. Average Extreme Weather Events (Gauge Chart)**
#### **Key Visualization:**
- A gauge chart showing the average number of extreme weather events.

#### **Insights:**
- The average extreme weather event count is **4.98**, indicating that nearly five significant events occur annually.
- This highlights the pressing need for climate adaptation to reduce the impact on agriculture.

---

### **15. Average Irrigation Access by Country with Extreme Weather Events Highlighted (Colored Bar Chart)**
#### **Key Visualization:**
- A colored bar chart showing irrigation access by country, with extreme weather events as a secondary metric.

#### **Insights:**
- Developed countries like the USA and Canada enjoy higher irrigation access, providing resilience against climate variability.
- Countries with frequent extreme weather events show lower irrigation access, suggesting a need for infrastructure investments.

---


## **Conclusion**

This analysis demonstrates the significant impact of climate change, resource utilization, and adaptation strategies on agricultural performance. The findings reveal that variations in temperature, precipitation, and extreme weather events strongly influence crop yields and economic outcomes, with warmer regions and those frequently experiencing extreme weather showing greater vulnerability. Effective adaptation strategies, such as crop rotation and organic farming, have proven beneficial in regions with higher agricultural and economic stability. However, the prevalence of "No Adaptation" in some areas indicates a lack of preparedness, calling for targeted interventions to enhance resilience.

Resource utilization also varies significantly across crops, with staples like wheat and rice relying heavily on fertilizers, while fruits and vegetables consume more pesticides. Balancing the use of these resources is crucial to reduce environmental impacts and ensure sustainable farming. Additionally, regional disparities were evident, with developed countries like the USA and Canada benefiting from higher irrigation access and more stable yields compared to developing regions, where limited resources and greater exposure to climate risks pose substantial challenges. Crops such as wheat, corn, and rice contribute the most to economic impact but are associated with higher emissions and resource demands, emphasizing the need for low-emission technologies and efficient farming practices.

In conclusion, the findings highlight the importance of promoting sustainable farming practices, investing in irrigation infrastructure, and adopting effective climate adaptation strategies, especially in vulnerable regions. Monitoring and reducing CO₂ emissions remain critical to mitigating climate risks and ensuring food security. This analysis provides a comprehensive foundation for policymakers, researchers, and agricultural stakeholders to make informed decisions that foster resilience and sustainability in agriculture.

---
---




