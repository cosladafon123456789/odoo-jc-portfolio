# IMEI / Serial Number Tracking (Device-Level Traceability)

Device-level traceability in Odoo 17 using IMEI/Serial numbers to control stock, sales, returns and refurb workflows.

## Business Problem
In refurbished smartphone operations, stock accuracy depends on tracking each physical device.
Without strict IMEI/Serial control, businesses face:
- wrong device shipped to customers
- mismatched returns (fraud / incorrect IMEI)
- poor traceability for warranty and after-sales

## Solution
Configure and extend Odoo inventory flows to enforce IMEI/Serial tracking end-to-end across:
- incoming stock
- internal transfers
- sales deliveries
- returns and RMAs
- refurbishment loops

## Key Features
- Serial/IMEI enforced at picking operations
- Traceability from purchase to sale to return
- IMEI mismatch detection on returns (control)
- Consistent device history for support and warranty

## Business Impact
- Reduced shipping mistakes
- Fraud prevention on returns
- Faster support resolution (traceability)
- Better stock accuracy and auditability

## Odoo Version
- Odoo 17 Enterprise

## Tech / Configuration
- Product tracking by Serial Number (IMEI)
- Stock picking constraints & validation rules
- Optional custom fields / logs for device history
