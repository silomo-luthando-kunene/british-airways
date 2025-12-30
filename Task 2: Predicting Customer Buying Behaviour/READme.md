# **Overview**
Built an optimized classification model to predict flight booking completions, focusing on identifying the behavioral triggers that drive customer conversion.

# **Technical Workflow**
* **Data Quality:** Processed 50,000 customer records, implementing SMOTE to address the significant imbalance in successful bookings.
* **Feature Engineering:** Developed the stay_lead_ratio to capture the relationship between "Purchase Lead Time" and "Length of Stay," a key indicator of travel urgency.
* **Model Selection:** Deployed a Random Forest Classifier achieving 91% Recall, ensuring the model captures nearly all high-intent customers for targeted re-marketing.

**Key Finding:** Purchase Lead Time is the strongest predictor of conversion; customers booking within a shorter window show significantly higher commitment levels, suggesting a "Proactive Nudge" strategy for long-lead browsers.
