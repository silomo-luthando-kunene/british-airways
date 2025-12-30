# **Overview** 
Developed a scalable "Lounge Eligibility Lookup Table" to forecast passenger demand for Terminal 3, enabling long-term capacity planning without requiring granular flight details.

# **Technical Workflow**
* **Systemic Grouping:** Categorized flights into four distinct "Demand Profiles" using a combination of HAUL (Long/Short) and DEPARTURE_FLOW (Peak Business vs. Leisure).
* **Assumption Modeling:** Applied weighted percentage estimates for Tier 1 (Concorde), Tier 2 (First), and Tier 3 (Club) based on historical premium seat density.
* **Key Finding:** Long-Haul "Peak Business" flows represent the highest systemic risk for lounge overcrowding, requiring a Tier 3 (Club) capacity of at least 25% of the total seat volume.
