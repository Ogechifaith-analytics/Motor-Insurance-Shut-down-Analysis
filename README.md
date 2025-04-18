# Motor-Insurance-Shut-down-Analysis (2014 - 2019)


## Overview

This report analyzes the financial performance of a motor insurance company that ceased operations after five years (2014 - 2019) due to significant financial losses. The analysis aims to identify key trends and factors that may have contributed to the company's downfall. By examining claims, premiums, and their relationship over time, we can gain insights into potential issues with underwriting, risk management, or overall business strategy.

## Data Sources

Two primary data tables were used for this analysis:

1.  **Calendar Table:**
    * Contains a date dimension spanning the company's operational period.
    * Transformed using Power Query to extract relevant time-based attributes (Year, Month, Quarter, Day of Week, etc.).

2.  **Motor Insurance Table:**
    * Contains transactional data related to motor insurance policies and claims.
    * Key columns include: Policy ID, Claim Amount, Premium Paid, Claim Date, Policy Start Date, Policy End Date, Vehicle Type, Vechile Make, Location,

## Data Modeling

The **Calendar Table** and the **Motor Insurance Table** were joined using a **one-to-many relationship** based on the relevant date fields. This data model allows for time-based analysis of insurance activities.

## Key Measures (DAX) 
file attached

## Visualizations

The following visualizations were used to present the analysis and highlight key findings:

* **Clustered Bar Chart:**
   
* **Ribbon Chart:**
   
* **Scatter Plot Chart:**

* **Tables:**
   
* **Tree Map:**
   
## Key Insights 

Based on this analysis, we aim to identify:

* **Deteriorating Financial Performance:** The trend of the Premium to Claim Ratio over the five-year period, highlighting when the company started experiencing significant losses.
* **High-Risk Segments:** Vehicle types, Make with disproportionately high claim amounts to the premiums collected.
* **Changes in Claim Patterns:** Any significant shifts in the frequency or severity of claims over time.
* **Potential External Factors:**  the analysis  reveal trends that could be linked to broader economic conditions, regulatory changes, or increased competition during the company's operational period.

## Conclusion

This data analysis provides a comprehensive overview of the motor insurance company's financial performance leading up to its closure. The insights gained can help understand the factors contributing to the heavy financial losses and offer valuable lessons for other players in the insurance industry. Further investigation into operational costs and market dynamics could provide a more complete picture.
