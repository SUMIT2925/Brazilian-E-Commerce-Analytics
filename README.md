# Analysis of Target's E-commerce Operations in Brazil

## Problem Statement Overview
The business case focuses on analyzing Target's operations in Brazil using a dataset of 100,000 orders placed between 2016 and 2018. The goal is to extract actionable insights to optimize logistics, marketing, and customer experience. Key tasks include:

1. **Exploratory Data Analysis (EDA)**: Understand dataset structure, time range of orders, and customer distribution.
2. **Trend and Seasonality Analysis**: Identify growth trends and monthly seasonality in orders.
3. **Customer Behavior**: Analyze preferred order times (Dawn, Morning, Afternoon, Night).
4. **Regional Analysis**: Study order distribution and customer demographics across Brazilian states.
5. **Economic Impact**: Evaluate money movement via order prices, freight costs, and payment methods.
6. **Delivery Performance**: Assess delivery times, freight values, and deviations from estimated delivery dates.

## Solution Analysis

### Key Findings from the Provided Solution

#### 1. Exploratory Data Analysis (EDA)
- **Data Types**: Confirmed `STRING` and `INT64` types for customer table columns.
- **Order Time Range**: Orders were placed from **4th September 2016 to 17th October 2018**.
- **Customer Distribution**: 
  - **São Paulo (SP)** had the highest order count (15,540), followed by Rio de Janeiro (RJ) and Minas Gerais (MG).
  - SP also had the highest customer count (41,746), aligning with its status as Brazil's most populous state.

#### 2. Trend and Seasonality
- **Growing Trend**: Orders increased from 2016 to 2018, peaking in 2017-2018.
- **Seasonality**: 
  - Higher orders during **Carnival (Feb-Mar)** and **Festival de Cachaça (Aug)**.
  - Lowest orders in September-October.

#### 3. Customer Behavior
- **Order Time**: Most orders were placed in the **afternoon (38,135)** and **night (28,331)**.

#### 4. Regional Analysis
- **Order Distribution**: SP consistently led in monthly orders, followed by RJ and MG.
- **Freight Costs**: 
  - **Highest**: Roraima (RR) - 42.98 avg.
  - **Lowest**: São Paulo (SP) - 15.15 avg.
- **Delivery Times**: 
  - **Fastest**: SP (8.26 days avg.).
  - **Slowest**: RR (27.83 days avg.).

#### 5. Economic Impact
- **Cost Increase**: Order costs rose by **138.53%** from 2017 to 2018 (Jan-Aug).
- **Order Prices**: 
  - **Highest Total Price**: SP (due to volume).
  - **Highest Avg. Price**: Paraíba (PB).

#### 6. Delivery Performance
- **Fastest Deliveries**: States where actual delivery was significantly faster than estimated (e.g., AC, RO, AM).
- **Payment Methods**: 
  - **Credit cards** dominated (most popular).
  - **Single installment** payments were most common (52,184 orders).

### Recommendations
1. **Logistics Optimization**: 
   - Partner with reliable carriers in slow-delivery states (e.g., RR, AP).
   - Reduce freight costs in high-avg. states (e.g., PB, RO).

2. **Marketing Strategies**: 
   - Leverage peak seasons (Carnival, August) for promotions.
   - Target afternoon/night shoppers with timed campaigns.

3. **Customer Experience**: 
   - Improve delivery estimates (actual vs. estimated gaps exist).
   - Offer incentives for credit card usage (already popular).

4. **Regional Focus**: 
   - Allocate resources to high-volume states (SP, RJ, MG).
   - Investigate low-avg. price states for potential pricing adjustments.

### Conclusion
The analysis highlights Target's strong e-commerce growth in Brazil, with opportunities to enhance logistics, capitalize on seasonal trends, and improve customer satisfaction. By addressing regional disparities and optimizing payment/delivery processes, Target can strengthen its market position.
