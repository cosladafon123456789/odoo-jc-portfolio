# Odoo → Laravel Webhooks (Shipment Sync)

Real-time integration between Odoo 17 and a Laravel-based eCommerce platform using webhooks.

## Business Problem
Order and shipment statuses are often updated manually between ERP and eCommerce.
This creates delays, operational mistakes, and customer support issues.

## Solution
Trigger secure webhooks from Odoo when key events happen (e.g., delivery validated),
so the Laravel store updates the order status automatically (e.g., "shipped").

## Key Features
- Webhook trigger on delivery validation
- Signed requests (security)
- Retries / error logging
- Payload includes order reference + tracking data

## Business Impact
- Real-time order status sync
- Reduced manual work
- Lower support ticket volume
- Fewer shipping-related errors

## Odoo Version
- Odoo 17 Enterprise

## Tech
- Odoo server actions / model overrides
- REST webhook calls (POST)
- Laravel endpoint to receive and process events
