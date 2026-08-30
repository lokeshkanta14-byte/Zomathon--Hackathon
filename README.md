# Zomathon--Hackathon
AI-powered Cart Super Add-On (CSAO) recommendation system for personalized food recommendations, AOV improvement, and delivery optimization
# Zomathon – Cart Super Add-On (CSAO) Recommendation System

## Project Overview

An AI-powered food delivery solution designed to increase Average Order Value (AOV), improve customer experience, and optimize delivery operations through intelligent cart-based recommendations and context-aware delivery support.

The solution combines basket-based recommendations, customer behaviour, time and location context, restaurant optimization, delivery risk prediction, customer availability prediction, and apartment-entry verification.

## Problem Statement

Food delivery platforms face challenges such as:

- Customers may leave the cart without adding complementary items.
- Generic recommendations may not match customer preferences or ordering context.
- Delivery partners may face delays at apartments and gated communities.
- Customers may be unavailable when the delivery partner reaches the destination.
- Manual coordination between customers, security, and delivery partners can increase waiting time and failed deliveries.

## Proposed Solution

The proposed CSAO system provides intelligent add-on recommendations while also supporting delivery optimization and verification.

### Key Features

- Basket-based add-on recommendations
- Context-aware recommendations based on time and location
- Personalized recommendations using customer behaviour
- Popular item combination analysis
- Dynamic recommendations as cart contents change
- LLM-based food intelligence
- Smart restaurant recommendation
- Delivery risk prediction
- Customer availability prediction
- Intelligent apartment/address classification
- Security entry verification using OTP/QR
- Delivery partner routing optimization

## Recommendation Strategy

### 1. Basket-Based Recommendations

Suggest complementary products based on items already present in the customer's cart.

### 2. Context-Aware Recommendations

Recommendations change based on:

- Time of day
- Location
- Ordering patterns
- Restaurant characteristics

### 3. Personalized Recommendations

Suggestions can adapt to customer preferences, ordering history, and spending behaviour.

### 4. Dynamic Sequential Recommendations

Recommendations are continuously updated when customers add or remove items from their cart.

## Dashboard Analysis

The project includes a Power BI dashboard for analysing cart behaviour and recommendation opportunities.

### Dashboard KPIs

- Total Revenue: 4M
- Average Order Value (AOV): 1.76K
- Average Items per Order: 6.02
- Total Orders: 2K

### Key Dashboard Insights

- Starters generated the highest revenue among the analysed categories.
- Starter and Main Course items contributed strongly to average basket size.
- Night showed the highest ordering activity.
- Mumbai recorded the highest number of orders among the displayed cities.
- Noodles and Chicken Fry were among the most popular items.

## Delivery Optimization

The solution also addresses real-world delivery challenges in apartments and gated communities.

### Customer Availability Prediction

The system uses customer response behaviour and response time to estimate delivery-time availability.

Possible outcomes include:

- Customer Likely Available
- Availability Uncertain – Send Reminder
- Customer May Be Unavailable

### Intelligent Address Classification

The system identifies apartment or gated-community addresses using address patterns and keywords such as:

- Apartment
- Apt
- Block
- Tower
- Gated
- Society

### Security Entry Support

For apartment or gated-community deliveries, the proposed system can provide:

- Entry support notification
- OTP/QR-based verification
- Customer arrival confirmation
- Delivery partner notification

This is designed to reduce gate waiting time and improve delivery success.

## AI System Workflow

```text
User Input
    ↓
Data Processing Layer
    ↓
Intelligent Address Classification
    ↓
AI Recommendation Engine
    ↓
LLM Intelligence Layer
    ↓
Restaurant Optimization
    ↓
Delivery Risk & Availability Prediction
    ↓
Automatic Entry Notification & Security Verification
    ↓
Delivery Partner Notification & Routing
    ↓
Final Recommendations to User
