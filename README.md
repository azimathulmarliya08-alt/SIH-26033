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

1. Detailed explanation of the proposed solution

KisanConnect is a mobile and web marketplace where farmers and Farmer Producer Organisations (FPOs) list their produce directly and sell to households, restaurants, hostels, retailers and bulk buyers, with no middlemen.

Farmers/FPOs list crop, quantity, quality grade, expected harvest date and price using a simple app in regional languages with voice input.
Buyers browse fresh produce, place one-time or subscription orders (for example, weekly vegetable boxes) and track delivery.
Local collection hubs run by FPOs or village groups gather produce, do basic grading and weighing, and hand over to delivery partners.
Logistics support pools orders from many farmers into shared vehicles and delivers to the buyer.
AI engine forecasts demand, suggests fair prices and plans the best delivery routes.
Payments go directly to the farmer’s bank account through UPI within 24 hours of delivery.

2. How it addresses the problem

Problem	KisanConnect’s answer
Many intermediaries take a cut	Direct farmer-to-buyer listing removes most middle layers
Farmers don’t know fair prices	Live mandi price comparison and AI price suggestions
Delayed payments	Direct UPI payment to the farmer’s account
Crop wastage due to poor demand matching	Demand forecasting tells farmers what to grow and sell, and when
High transport cost	Pooled loads and optimised routes cut per-kg delivery cost
Consumers pay high prices	Fewer layers means lower retail prices with fresher produce

3. Innovation and uniqueness of the solution

Voice-first, multilingual interface for farmers with low digital literacy.
Pre-harvest listing: buyers can pre-book crops, so farmers know their demand before harvest.
Transparent price breakdown: buyers see how much of their payment goes to the farmer, logistics and the platform.
Pooled logistics: orders from nearby farmers are combined into one vehicle to lower cost.
AI price and demand advisor that tells farmers when and where to sell for the best return.
FPO-centric model: FPOs act as aggregation hubs, giving small farmers bulk-selling power.
Freshness and quality score based on harvest-to-delivery time.
Technical Approach

1. Technologies to be used

Frontend: React (web), Flutter or React Native (mobile app)
Backend: Python (Django or FastAPI), REST APIs
Database: PostgreSQL (orders, users, listings)
AI/ML:
Demand and price forecasting: time-series models (Prophet, LSTM)
Route optimisation: Google OR-Tools with OpenStreetMap-based routing
Quality grading (future scope): image classification with a CNN
Voice and language: speech-to-text and translation APIs for regional languages
Payments: UPI gateway (Razorpay or similar)
Maps and tracking: OpenStreetMap or Google Maps API
Data sources: Agmarknet and eNAM open price data
Cloud: AWS or Azure free tier for the prototype
Notifications: SMS and WhatsApp for farmers with basic phones

2. Methodology and process for implementation

Flow of the system:

Farmer/FPO lists produce (voice/app)
        ↓
AI suggests fair price + demand insight
        ↓
Buyer browses, orders, pays via UPI
        ↓
Order sent to nearest collection hub
        ↓
AI groups orders and plans the best delivery route
        ↓
Pickup → grading/weighing → pooled delivery
        ↓
Buyer receives produce, confirms delivery
        ↓
Payment released directly to farmer's bank account
        ↓
Ratings and data feed back to improve forecasts

Implementation phases:

Phase 1 (Prototype): farmer listing, buyer ordering and UPI payment in a working web app.
Phase 2: price suggestion and demand forecasting using historical mandi data.
Phase 3: route optimisation and pooled delivery for one district.
Phase 4: pilot with one FPO and nearby buyers, collect feedback, then scale.

(Add your flow chart image and prototype screenshots here.)

Feasibility and Viability

1. Analysis of the feasibility of the idea

Technical: all components (marketplace, forecasting, routing, UPI) use proven, mostly open-source technology.
Operational: FPOs already exist across India and can act as ready-made aggregation hubs.
Economic: a small commission (for example 3-5%) on each order plus delivery fees can sustain the platform while still leaving farmers better off than in the mandi system.
Social: smartphone and UPI use is growing in rural areas, and voice and regional-language support reduces the literacy barrier.

2. Potential challenges and risks

Low digital literacy among some farmers
Poor internet connectivity in villages
Quality inconsistency and spoilage of perishables
Last-mile delivery cost for small orders
Trust issues about payment and product quality
Difficulty balancing supply and demand at the start

3. Strategies for overcoming these challenges

Voice-based interface, local-language support and training through FPO volunteers and Krishi Mitras
Offline-friendly app and SMS/WhatsApp fallback
Basic grading at collection hubs and a rating system for quality
Pooled deliveries and fixed delivery slots to cut cost
Escrow-style payments (money held until delivery is confirmed) and verified farmer profiles
Start with one district and a few high-demand crops, then expand
Impact and Benefits

1. Potential impact on the target audience

Farmers/FPOs: a larger share of the final price, faster payment and better planning of what to grow.
Consumers: fresher produce at lower prices with transparent sourcing.
Bulk buyers (restaurants, hostels, retailers): reliable supply, predictable pricing and easy reordering.
Government: better visibility of supply-demand data to support policy and price stabilisation.

2. Benefits of the solution

Social: empowers small farmers, strengthens FPOs and builds rural digital inclusion.
Economic: higher farmer income, lower consumer prices and new rural jobs in hubs and delivery.
Environmental: less food wastage, fewer delivery trips through route optimisation and less cold-storage dependence through shorter supply chains.
