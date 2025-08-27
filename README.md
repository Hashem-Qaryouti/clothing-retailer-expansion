# Clothing Retailer Expansion

## Description
This project analyzes potential expansion opportunities for a German high-fashion retail company that has operated stores at European airports for several years. The client aims to expand into the global market and seeks to identify the most profitable location for a new store outside of Europe.

The analysis focuses on a set of international airports, which are being considered for the new store opening:

- **Beijing, China:** Beijing Capital International Airport  
- **Buenos Aires, Argentina:** Ministro Pistarini International Airport  
- **Dallas, USA:** Dallas Fort Worth International Airport  
- **Dubai, UAE:** Dubai International Airport  
- **Hong Kong, Hong Kong:** Hong Kong International Airport  
- **Kuala Lumpur, Malaysia:** Kuala Lumpur International Airport  
- **Melbourne, Australia:** Melbourne International Airport  
- **New York, USA:** John F. Kennedy International Airport  
- **San Francisco, USA:** San Francisco International Airport  
- **Shanghai, China:** Shanghai Pudong International Airport  
- **Singapore, Singapore:** Singapore Changi Airport  
- **Tokyo, Japan:** Tokyo Haneda International Airport

The objective of this project is to provide the client with a **ranked list of airports** based on expected profit, calculated as revenue minus leasing costs, to support informed investment decisions for global expansion.

## Data
The analysis is based on multiple datasets provided by the client, all evaluated as of **December 31, 2019**. The datasets include both customer and airport information to estimate potential revenues and costs for store expansion.

### Provided Datasets
1. **Customer surveys from current European stores**  
   - Evaluations of customer spending patterns  
   - Customers categorized into five groups based on expenditure:  
     - **Category 0:** 0–10 EUR  
     - **Category 1:** 10–50 EUR  
     - **Category 2:** 50–150 EUR  
     - **Category 3:** 150–300 EUR  
     - **Category 4:** 300–500 EUR

2. **Passenger surveys from proposed airports**  
   - Data collected from passengers at the potential new store locations outside Europe

3. **List of proposed airports**  
   - Details about each airport considered for expansion

4. **Monthly rent for stores at proposed airports**  
   - Leasing cost information negotiated by the client for each potential location

These datasets allow for calculating **expected profit** (revenue minus leasing costs) for each airport and provide the foundation for ranking the locations according to their investment potential.

## Features
The project implements the following features:

- **Passenger Expenditure Prediction:** Predict passenger spending volumes and categorize passengers by expected spending at each proposed airport.  
- **Profit Estimation:** Calculate expected monthly revenue for each airport based on predicted passenger expenditures.  
- **Cost Integration:** Incorporate leasing costs to estimate net profit for each potential store location.  
- **Airport Ranking:** Provide a ranked list of airports according to expected profit to guide investment decisions.  
- **Data Visualization:** Optional visualizations to illustrate passenger distributions, predicted revenues, and comparative profitability.

## Methodology
1. Analyze **customer spending patterns** from existing European stores.  
2. Map passenger survey data from proposed airports to estimate **expected spending categories**.  
3. Combine predicted passenger expenditures with **leasing costs** to calculate expected net profit per airport.  
4. Rank airports by expected profit to recommend the **best location for investment**.

## Usage
1. Clone the repository:  
```bash
git clone https://github.com/Hashem-Qaryouti/clothing-retailer-expansion.git
