## Revenue Performance Analysis & Root Cause Assessment – AtliQ Grands
AtliQ Grands is a hospitality company operating multiple five-star hotels across India. Recently, the company observed fluctuations in weekly revenue despite stable room availability.

This project analyzes 134,590 hotel booking records from May–July 2022 to investigate the drivers behind the revenue decline and identify opportunities to improve revenue management and pricing strategies.
The analysis focuses on key hospitality KPIs such as RevPAR, ADR, Occupancy Rate, and Booking Realization to identify patterns affecting hotel performance. 

## Business Problem

->Management wanted to understand:
->Why revenue declined despite stable room supply
->Whether the issue was related to occupancy, cancellations, or pricing
->Which segments or booking channels contributed most to the decline

The goal was to identify the root cause and provide insights that support better revenue management decisions.
- Power BI (Dashboarding & DAX)
- SQL / Excel (Data aggregation)
- Business KPI Analysis (RevPAR, ADR, Occupancy)
- Root Cause Analysis
- Revenue Management Concepts

### Dataset

The analysis uses booking and hotel performance data across multiple tables.

Tables Used
  - fact_bookings – 134,590 booking records
  - fact_aggregated_bookings
  - dim_hotels – 25 hotels
  - dim_rooms
  - dim_date
Time Period: May 2022 – July 2022
#### Granularity:
Booking-level data
Daily room availability
Weekly revenue aggregation

### Tools & Technologies

- Power BI – Dashboard creation and visualization  - DAX – KPI calculations
- Excel / SQL – Data validation and aggregation - Business KPI Analysis – RevPAR, ADR, Occupancy

### Analysis Approach

To identify the cause of revenue decline, the following analytical steps were performed:-
  Identified abnormal revenue trends using weekly revenue analysis
  Compared occupancy levels between normal and low-revenue weeks
  Evaluated booking realization ratio to rule out cancellations
  Analyzed segment-level revenue contribution
  Conducted weekday vs weekend pricing analysis
  Evaluated channel-level ADR trends

### Key Insights

Room supply remained stable, as Daily Sellable Room Nights (DSRN) did not change significantly.
Booking realization ratio remained consistent (~69–71%), indicating cancellations were not a major factor.
Luxury segment revenue declined significantly, becoming the primary contributor to overall revenue decline.
Weekend occupancy (64%) was higher than weekday occupancy (57%), indicating stronger demand.
However, ADR remained nearly identical on weekdays and weekends, limiting revenue potential.
A sharp ADR drop in the Offline Direct channel suggests a pricing strategy misalignment.

### Recommendations
Based on the analysis, the following actions are recommended:
Introduce dynamic pricing strategies for weekends
Reevaluate Luxury segment pricing strategy
Investigate Offline Direct channel pricing adjustments
Implement data-driven revenue management practices

### Dashboard
 <img width="1380" height="734" alt="image" src="https://github.com/user-attachments/assets/d2275da2-6d12-469b-9be2-b053e1802afb" />

### Conclusion

The revenue decline was not caused by operational factors such as room availability or booking cancellations.

Instead, the analysis indicates that pricing inefficiencies and reduced revenue contribution from the luxury segment were the primary drivers. Additionally, the lack of premium pricing during high-demand weekends resulted in missed revenue opportunities.

Implementing data-driven pricing strategies and segment-focused revenue optimization can help improve overall hotel performance.
