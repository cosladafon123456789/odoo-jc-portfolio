# Fraud Prevention & Risk Order Management

Automated fraud prevention rules and risk scoring for sales orders in Odoo 17.

## Business Problem
High-value eCommerce operations face risks such as:
- fraudulent orders
- false return claims (empty box, wrong device)
- repeat offenders

Manual checks do not scale and lead to losses.

## Solution
Implement rule-based risk detection and order control inside Odoo.

## Key Features
- Risk flags on sales orders
- Rules based on value, location, history, and behavior
- Automatic order holds or approval requirements
- Integration with delivery and RMA flows
- Blacklists / watchlists support

## Business Impact
- Reduced fraud losses
- Better control on high-risk orders
- Faster decision-making
- Protected margins

## Odoo Version
- Odoo 17 Enterprise

## Tech
- Computed risk scoring
- Business rule engine
- Order state controls and validations
