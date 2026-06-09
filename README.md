 Construction Risk Analysis

 Project Overview

This project analyzes construction project tasks to identify high-priority activities and potential project risks. Using Python, Pandas, and Matplotlib, a custom scoring framework was developed to evaluate task criticality based on risk levels, task dependencies, resource constraints, and site constraints.

The objective was to create a data-driven approach for prioritizing project activities and supporting construction project decision-making.


 Dataset

The dataset contains construction project task information, including:

* Task ID
* Task Duration
* Labor Requirements
* Equipment Units
* Material Cost
* Resource Constraint Score
* Site Constraint Score
* Dependency Count
* Risk Level


 Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab
* GitHub


 Project Workflow

1. Data Exploration

* Examined dataset structure and data types.
* Checked for missing values.
* Reviewed distributions of key project variables.

2. Material Cost Analysis

* Identified the highest-cost construction tasks.
* Evaluated potential financial exposure across project activities.

3. Correlation Analysis

* Analyzed relationships among project variables.
* Found that most variables exhibited weak correlations, suggesting that project performance is influenced by multiple independent factors.

4. Critical Task Score Development

A custom Critical Task Score was created using:

* Dependency Count
* Resource Constraint Score
* Site Constraint Score

This score was designed to identify operationally challenging tasks.

5. Enhanced Critical Task Score

The scoring model was improved by incorporating project Risk Levels.

Components included:

* Risk Score
* Dependency Count
* Resource Constraint Score
* Site Constraint Score

The enhanced score provided a more comprehensive assessment of task criticality.

6. Management Dashboard

A dashboard visualization was developed to rank and display the Top 10 Critical Construction Tasks based on the Enhanced Critical Task Score.



Key Findings

Correlation Analysis

* Most project variables exhibited very weak correlations.
* No single variable emerged as a strong predictor of project risk or complexity.
* Project performance appears to be influenced by multiple independent factors.

Critical Task Analysis

* Task T478 was identified as a high-priority activity due to resource constraints, site constraints, dependencies, and extended duration.
* Operational factors contributed significantly to project risk beyond cost alone.

Enhanced Critical Task Score

* Task T1046 received the highest Enhanced Critical Score (40.3).
* The top-ranked tasks were all classified as High Risk.
* The enhanced scoring model aligned project risk classifications with operational constraints.

Business Insight

The analysis demonstrated that combining multiple risk indicators into a single score provides a more effective method for prioritizing project activities than relying on individual risk measures alone.


Dashboard Example

The Top 10 Critical Tasks dashboard highlights project activities requiring the greatest management attention and risk mitigation efforts.


Conclusion

This project demonstrates how data analytics can be applied to construction project management by transforming operational and risk-related factors into actionable insights. The Enhanced Critical Task Score provides a practical framework for identifying critical activities, supporting resource planning, and improving project risk management.

## Author

**Steffy Johnson**

Data Analytics Portfolio Project
