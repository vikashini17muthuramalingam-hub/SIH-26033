# Smart India Hackathon Workshop
# Date: 25-11-2026
## Reference Number: 26016718
## Name: M Vikashini

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
We propose VayalBridge – A Demand-Driven Smart Agricultural Marketplace, a digital platform designed to connect farmers, Farmer Producer Organizations (FPOs), retailers, restaurants, wholesalers and individual consumers through a transparent and intelligent supply chain. Unlike conventional agricultural marketplaces that primarily focus on selling already-harvested products, VayalBridge introduces a demand-first approach in which buyers can communicate their expected requirements before harvesting begins. The platform collects information about crop availability, estimated harvest dates, buyer demand, geographical locations and prevailing market prices to identify suitable trading opportunities. Its AI-based demand forecasting system analyses historical sales, seasonal patterns, local consumption and market trends to estimate which crops are likely to have higher demand in different regions. Farmers receive these insights before deciding where and when to sell their produce. Buyers can place advance requirements, while farmers and FPOs can respond with available quantities and expected delivery dates. This creates a more organized connection between agricultural production and actual market demand.

The platform addresses the problem of multiple intermediaries by introducing a direct negotiation and transparent transaction system. Every farmer can create a digital produce listing containing the crop name, available quantity, expected harvest date, quality grade, location and minimum acceptable price. Buyers can compare multiple farmer listings and submit offers directly. A unique feature called the FairShare Price Window displays an estimated price breakdown showing the farmer's expected earnings, transportation expenses, handling charges and platform service fees before an order is confirmed. Farmers retain control over whether to accept or reject an offer. Another feature called HarvestLink Pooling combines orders from nearby buyers and produce from nearby farms into coordinated collection and transportation schedules. Instead of each farmer arranging separate transportation, multiple farmers can share available vehicle capacity and divide transportation expenses according to the quantity transported. This helps reduce unnecessary transport costs and delays.

## Technical Approach
VayalBridge will be developed as a mobile-friendly web application with a scalable backend and a database that maintains farmer profiles, buyer requirements, crop listings, orders, transactions, transport schedules and produce traceability records. The frontend can be developed using HTML, CSS, JavaScript and React, while Python with Django REST Framework will manage backend operations, user authentication, APIs and business logic. PostgreSQL will store structured information, and cloud storage can be used for product photographs, inspection documents and digital records. The AI module will initially use Python-based machine-learning models, including time-series forecasting and regression techniques, to analyse historical commodity prices, seasonal demand, previous orders and available supply. Publicly available agricultural market information, including relevant e-NAM and Agmarknet data, can support price comparison and market analysis where permitted access is available. Weather information from suitable agricultural weather services can be incorporated to improve demand and harvest planning. The system will calculate approximate transportation requirements by grouping orders according to location, quantity, delivery deadline and available vehicle capacity. Mapping and route-planning services will help identify practical collection and delivery routes. The QR-based Digital Passport will connect each produce lot to its stored records, while secure payment integration through an authorized payment gateway will support transactions. The application will provide separate interfaces for farmers, buyers, FPO administrators and logistics partners, with regional-language options and low-bandwidth-friendly pages. Development will begin with a working prototype containing registration, crop listing, buyer requirements, direct offers, price breakdowns, order management and QR-based tracking before advanced AI forecasting and automated logistics are introduced.


## Feasibility and Viability
The proposed solution is technically feasible because it can be developed using existing web technologies, open-source programming frameworks, relational databases, machine-learning libraries and mapping services. Rather than constructing an entirely new agricultural distribution network, VayalBridge will coordinate existing farmers, FPOs, buyers, collection centres and transport providers through a common digital platform. The first implementation can be tested within a limited geographical area by onboarding a small group of farmers, one or more FPOs, local retailers and transportation partners. Initially, demand prediction can use historical price information, seasonal patterns and manually entered buyer requirements, allowing the system to function even when large datasets are unavailable. As more transactions take place, the platform can gradually improve its forecasting accuracy using verified transaction records. Potential challenges include limited digital literacy, inconsistent internet access, inaccurate crop availability information, quality disagreements, delayed payments and insufficient transportation during peak harvesting periods. These challenges can be addressed through regional-language interfaces, voice and SMS notifications, assisted registration through FPO representatives, produce verification at collection points, digital transaction records and partnerships with local transport providers. The platform will also maintain alternative arrangements for orders that cannot be fulfilled as planned. Financial sustainability can be achieved through a small and clearly disclosed transaction service fee, optional logistics coordination charges and subscription-based services for large buyers, without making farmers dependent on expensive intermediaries. A phased implementation will reduce initial investment, allow real-world testing and make future expansion practical.

## Impact and Benefits
VayalBridge is expected to create economic, social and environmental benefits by improving the way agricultural products move from farms to consumers. Farmers gain access to multiple buyers, advance demand information, transparent price comparisons and greater control over negotiations, helping them make better selling decisions and potentially improve their share of the final selling price. Consumers, retailers and bulk buyers benefit from more direct sourcing, better visibility of product origins and reduced unnecessary distribution expenses, which may contribute to more affordable prices. FPOs gain a common platform for combining the produce of their members, managing bulk orders and coordinating transportation. The FairShare Price Window makes financial deductions visible, while the Farm-to-Fork Digital Passport improves accountability and buyer confidence. HarvestLink Pooling can improve vehicle utilization, reduce repeated journeys and lower transportation costs. Demand forecasting can also help reduce the mismatch between production and consumption, potentially limiting unsold agricultural produce and avoidable food wastage. The platform can create additional opportunities for local collection centres, quality inspectors and logistics providers while supporting the digital participation of rural communities. Its long-term objective is to build a more transparent, inclusive and efficient agricultural marketplace where farmers have stronger market access, buyers have reliable sourcing options and agricultural resources are used more efficiently.

## Research and References
National Agriculture Market (e-NAM): https://enam.gov.in/

e-NAM Farmer Producer Organizations: https://www.enam.gov.in/web/stakeholders-Involved/fpos

Agmarknet – Agricultural Marketing Information: https://agmarknet.gov.in/

India Meteorological Department – Agricultural Meteorology: https://imdagrimet.gov.in/

Ministry of Agriculture and Farmers Welfare: https://agriwelfare.gov.in/
