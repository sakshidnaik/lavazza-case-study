# Lavazza Logistics Network Optimization Case Study

## Overview
This case study explores how Lavazza, a leading Italian coffee brand with a 44% retail share, can revamp its logistics network to tackle market fluctuations and growing demands from large retail chains. The project focuses on optimizing warehouse locations and distribution methods to enhance efficiency, reduce costs, and improve customer satisfaction.

### Key Situation:
**Lavazza's Challenge**: An expanding product range and centralized storage requests from major retailers have strained the logistics network. The company must consider more direct deliveries and efficient distribution strategies.
- **Objective**: To redesign the logistics network to minimise handling and distribution costs while meeting customer demand.
- **Solution**: A linear transhipment programming model was developed to optimize the flow of goods from the central and satellite warehouses to six customers, balancing cost and efficiency.

## Key Insights & Analysis
### Logistics Strategy
Lavazza is exploring possibly co-locating a satellite warehouse with one of its key customers. This would allow for Full Truck Load (FTL) deliveries, leading to significant cost savings.

### Business Objective & Constraints:
- **Goal**: Minimize total distribution and handling costs while satisfying all customer demands.
- **Constraints**:
  - The central warehouse must remain active.
  - Only one satellite warehouse can be implemented.
  - Outbound shipments from any satellite warehouse must match inbound volumes.

### Decision Visualization & Scenario Analysis
- **Primary Focus**: Based on demand fluctuations and cost variations, the analysis investigates different warehouse locations, specifically Satellite Warehouse 2 (SW2) and Satellite Warehouse 4 (SW4).
- **Recommendation**: Establishing SW2 is the optimal solution, offering substantial cost savings. However, if handling costs or customer demand (specifically from Customer 4) changes, SW4 could become a more favourable option.

## Excel Model Breakdown
### Key Sheets in the Model:
- **Original Model**: Baseline analysis for distribution costs and optimal warehouse configurations.
- **Scenario Simulations**: Activates each isolated satellite warehouse to evaluate cost impacts.
- **Sensitivity Report**: Evaluates how demand and cost fluctuations influence the overall strategy, offering dynamic adaptability to market conditions.

### Model Insights:
- **SW2 vs SW4**: Initially, SW2 is identified as the most cost-effective option, resulting in potential savings of $1,465,660. However, changes in demand or costs, especially for Customer 4, could shift the advantage to SW4.
- **Cost-Benefit Analysis**: The scenario planning supports SW2 as the primary recommendation, ensuring customer satisfaction without incurring unnecessary costs.

## Strategic Recommendations
Lavazza should establish Satellite Warehouse 2 due to its immediate cost-saving potential and proximity to high-demand customers. However, staying flexible and monitoring market changes that could justify a shift to SW4 or other configurations is essential. This data-driven approach allows Lavazza to optimize its logistics strategy in real-time, maximizing both cost efficiency and customer service.
