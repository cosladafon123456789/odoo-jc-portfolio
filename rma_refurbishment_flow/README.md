# RMA & Refurbishment Flow

Custom RMA and refurbishment workflows in Odoo 17 for refurbished electronics.

## Business Problem
Standard RMA flows do not cover real-world refurbishment scenarios such as:
- device inspection after return
- repair vs replacement decisions
- battery or cosmetic exclusions
- refund vs re-shipment logic

Manual handling leads to delays, errors, and inconsistent outcomes.

## Solution
Design structured RMA workflows integrated with stock, repair, and accounting modules.

## Key Features
- RMA intake and inspection process
- Decision flows: repair / replace / refund / reject
- Integration with refurbishment stock locations
- Device history preserved via serial/IMEI
- Automatic stock and accounting actions

## Business Impact
- Faster and consistent RMA handling
- Reduced post-sales costs
- Better traceability for disputes
- Improved operational control

## Odoo Version
- Odoo 17 Enterprise

## Tech
- Custom RMA models / extensions
- Stock picking automation
- Business-rule driven state transitions
