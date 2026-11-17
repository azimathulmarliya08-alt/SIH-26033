Smart India Hackathon Workshop
Date:17/11/2026
Reference Number:26018986
Name: AZIMATHUL MARLIYA.A
Problem Title

SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

Problem Creater’s Organization

Ministry of Consumer Affairs, Food & Public Distribution

Theme

Agriculture, FoodTech & Rural Development

Problem Description

Expected Solution: Create a digital marketplace that:

Connects farmers/FPOs directly with consumers and bulk buyers.
Provides logistics support.
Uses AI for demand forecasting and route optimization.

Benefits:

Better prices for farmers.
Lower prices for consumers.
Reduced supply chain inefficiencies.
Proposed Solution

FarmPool: A Demand-First Group-Buying Network for Farmers and Buyers

1. Detailed explanation of the proposed solution

Most farm marketplaces start from the farmer’s stock. The farmer harvests first, then looks for a buyer. If no buyer is found in time, the produce is dumped on a local trader at a low price. This is exactly how intermediaries gain power.

FarmPool reverses this order. Buyers order first, and farmers harvest second. The platform is built around buying groups and a weekly cycle:

Buying groups: Apartment associations, hostels, college canteens, small restaurants, grocery shops and self-help groups register as a “pool”. Each pool has a leader who manages the group’s orders.
Weekly pre-order window: Each pool places its order for the coming week (for example, Monday to Wednesday), choosing vegetables, fruits, pulses or grains from a list of crops available in the region.
Harvest List: The platform combines the orders of all pools and sends each FPO a “Harvest List” showing crop, quantity, quality grade, price and delivery date. The FPO divides the work among its member farmers.
Farmer confirmation without an app: Farmers confirm the order through a WhatsApp message, a missed call or a simple voice call in their own language. No smartphone skills are needed.
Harvest, pack and tag: Farmers harvest only what has been ordered. Every pack gets a QR code at the FPO collection point.
Fixed drop day: Produce is delivered on a fixed day each week to a pickup point for each pool, so a single vehicle can serve a whole locality.
Instant payment: Once the pool leader confirms delivery, the money goes directly from the escrow account to the farmer’s bank account by UPI.
Bulk buyers and individuals: Large buyers can place bigger direct orders, and individual households can join an existing pool near them.

2. How it addresses the problem

Removes the need for middlemen: Traders earn by buying cheap from farmers who have no other buyer. When orders are confirmed before harvest, farmers have no reason to sell to a trader.
Fair, locked price: The price is agreed at the time of ordering, based on mandi rates and the farmer’s cost, so there is no last-minute bargaining or sudden price drops.
Lower cost of logistics: One vehicle delivers to one pickup point per locality instead of many small deliveries, which cuts cost per kg.
No wastage: Because only ordered quantities are harvested, unsold stock and spoilage fall sharply.
Lower prices for consumers: The layers of wholesaler, sub-wholesaler and retailer are replaced by one platform fee, so the consumer pays less for fresher produce.
Faster payment: Farmers are paid within a day instead of waiting days or weeks for traders.
Better supply chain efficiency: Demand is known in advance, so planning, transport and packing are all done once instead of being repeated at every layer.

3. Innovation and uniqueness of the solution

Harvest-on-order model: Production follows confirmed demand, which almost removes unsold stock.
QR code on every pack: Scanning shows the farmer’s name, farm location, harvest date and a price split (farmer’s share, transport, platform fee). This builds trust and shows consumers exactly where their money goes.
App-free farmer access: WhatsApp, missed call and voice support make the platform usable by farmers who are not comfortable with apps.
Use of existing routes: Delivery can use milk-collection vehicles, return trips of empty trucks and bus parcel services, which lowers logistics cost without needing a new fleet.
AI-based forecasting for pools: The system learns each pool’s ordering pattern and warns FPOs about expected demand a week or two ahead.
Freshness promise: Harvest-to-delivery time is tracked, and produce delivered later than the promised window is flagged and compensated.
Farmer reputation score: Farmers and FPOs earn ratings based on quality and on-time supply, which brings them more orders.
Technical Approach

1. Technologies to be used

Frontend:
React web app and mobile app (Flutter or React Native) for pool leaders, buyers and FPO managers
WhatsApp Business API chatbot and missed-call/IVR service for farmers
Backend: Python (FastAPI or Django) with REST APIs
Database: PostgreSQL for users, pools, orders, crops and payments
AI and ML:
Demand forecasting from past pool orders, seasonality and festivals using Prophet or LSTM
Price suggestion using Agmarknet and eNAM mandi data
Route optimisation and vehicle pooling using Google OR-Tools with OpenStreetMap
Traceability: QR code generation, linked to each batch of produce
Payments: UPI gateway with an escrow-style hold and release
Language support: Speech-to-text and translation APIs for Tamil, Hindi, Telugu and other regional languages
Cloud: AWS or Azure free tier for the prototype
Notifications: SMS and WhatsApp alerts for orders, delivery and payment

2. Methodology and process for implementation

Flow of the system:

Buying groups register and place weekly pre-orders
              ↓
AI combines orders and forecasts demand
              ↓
Harvest List sent to FPO (WhatsApp / app)
              ↓
Farmers confirm by WhatsApp or missed call
              ↓
Harvest, weigh, pack and attach QR code
              ↓
AI plans the route and pooled vehicle for drop day
              ↓
Delivery to each pool's pickup point
              ↓
Pool leader confirms delivery
              ↓
Escrow releases UPI payment to the farmer
              ↓
Ratings and order data improve the next forecast

Implementation phases:

Phase 1, Prototype (1-2 months): pool registration, weekly ordering, Harvest List and UPI payment in a working web app.
Phase 2 (2-3 months): WhatsApp bot for farmers, QR traceability and price suggestions from mandi data.
Phase 3 (3-4 months): demand forecasting and route optimisation for one city.
Phase 4, Pilot: run with one FPO and 10 to 15 buying groups for 8 to 12 weeks, collect feedback and fix issues.
Phase 5, Scale: add more FPOs, crops and cities, and connect with ONDC.

(Add your flow chart image and prototype screenshots here.)

Feasibility and Viability

1. Analysis of the feasibility of the idea

Technical: All parts (ordering app, WhatsApp bot, forecasting, routing, UPI and QR codes) use proven and mostly open-source tools.
Operational: No warehouse or cold storage is needed at the start, because produce moves only after orders are confirmed. FPOs already exist across India and can run the collection points.
Economic: A small service fee (for example 4 to 6 percent of the order value) plus a delivery charge covers costs. Savings from removing layers and wastage still leave farmers earning more and buyers paying less.
Social: WhatsApp and UPI are already familiar in rural and urban India, and group buying is a natural habit in apartments, hostels and self-help groups.
Scalable: Once one city and one FPO work, the same model can be copied to any region with a nearby farming belt.

2. Potential challenges and risks

Low order volumes in the early weeks
Weather, pests or floods reducing crop supply
Buying groups cancelling late
Quality differences between farmers
Delivery delays for perishable items
Farmers’ trust in a new system and in digital payments
Dependence on the FPO’s management quality

3. Strategies for overcoming these challenges

Begin in one city with colleges, hostels and apartment groups near one FPO to build steady volume
Keep backup farmers and a second FPO for each major crop
Take a small advance payment to confirm orders, with a clear cancellation rule
Grade and check produce at the FPO collection point before packing, with ratings for farmers
Use fixed delivery slots, insulated crates and short routes for perishable items
Build trust through field demonstrations, FPO leaders as local champions and first-week payments made on time
Train and support FPO managers, and share simple dashboards that show orders and earnings
Impact and Benefits

1. Potential impact on the target audience

Farmers and FPOs: Guaranteed buyers before harvest, a locked and fair price, quick payment and no unsold stock. Small farmers get the selling power that only large traders had before.
Consumers and buying groups: Fresh produce at lower prices, with complete visibility of the farmer and the price split through the QR code.
Bulk buyers such as hostels, canteens and restaurants: Reliable weekly supply, predictable pricing and easy reordering.
Local community: Jobs at collection points, packing and delivery, and a stronger local FPO network.
Government and policy makers: Real-time data on supply and demand that helps with price stabilisation and crop planning.

2. Benefits of the solution

Social:
Gives small farmers confidence and stable demand
Builds trust between farmers and consumers
Brings digital inclusion to rural areas through voice and WhatsApp access
Economic:
Higher share of the final price for farmers
Lower retail prices for consumers
Lower transport cost per kg and new rural jobs
Environmental:
Less food waste and spoilage
Fewer delivery trips through pooled routes
Lower fuel use and carbon emissions
