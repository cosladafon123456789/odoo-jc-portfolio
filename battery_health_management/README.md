# Battery Health Management (BAT100 / Threshold Rules)

Battery health tracking and business rules for refurbished devices in Odoo 17.

## Business Problem
Battery condition is a key quality factor in refurbished phones. Without proper control:
- inconsistent grading and customer expectations
- warranty disputes (battery degradation claims)
- operational mistakes (shipping devices below threshold)

## Solution
Implement battery health fields and automated rules to control device eligibility and after-sales outcomes.

## Key Features
- Battery health (%) stored per device / serial
- BAT100 flag (e.g., “Battery 100%” replacement indicator)
- Threshold rules (e.g., block/flag shipments below 85%)
- RMA outcomes based on battery criteria (repair / replacement / refund)
- Internal reporting on battery-related issues

## Business Impact
- Lower return rates and disputes
- Consistent grading and quality control
- Faster post-sales decisions
- Improved customer satisfaction

## Odoo Version
- Odoo 17 Enterprise

## Tech
- Custom fields (battery health %, BAT100)
- Server-side validations / compute logic
- Optional smart buttons and KPI reporting
