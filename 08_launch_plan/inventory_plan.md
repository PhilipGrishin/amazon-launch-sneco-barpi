# Inventory Plan

## Public Repository Rule

This repository is public. Do not include confidential production quantities, supplier commitments, costs, private documents, personal data, credentials, or non-public commercial strategy.

Use `TBD` for unknown operational inputs until public-safe planning values are approved.

## SnEco Multipack Inventory Planning

### Operating Rules

- Each selling-unit scenario is a separate Amazon sellable unit / ASIN candidate.
- Do not include 10-pack in the current active model.
- Amazon FBA should not be expected to assemble multipacks from loose single pouches.
- Each multipack must be physically assembled before inbound to Amazon FBA, either at the Slovakia production/warehouse level or through a prep center.
- Each multipack should have its own barcode/FNSKU and "Sold as set / Do not separate" handling logic.

### Selling Units

| Selling unit ID | Composition | Total pouch count | Total net weight | Strategic role | Assembly location assumption | Barcode/FNSKU approach | Sold as set / Do not separate labeling | First test quantity per selling unit | Inbound destination assumption | Status | Notes |
| --- | --- | ---: | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SnEco Gouda 3-pack | 3 x Gouda 28g | 3 | 84g | Entry pack | Slovakia production/warehouse or prep center | Own barcode/FNSKU needed | Required | 40 | Assigned by Amazon Seller Central | Selected for minimal first batch | Separate sellable unit / ASIN candidate. |
| SnEco Cheddar 3-pack | 3 x Cheddar 28g | 3 | 84g | Entry pack | Slovakia production/warehouse or prep center | Own barcode/FNSKU needed | Required | 40 | Assigned by Amazon Seller Central | Selected for minimal first batch | Separate sellable unit / ASIN candidate. |
| SnEco Gouda 6-pack | 6 x Gouda 28g | 6 | 168g | Main pack candidate | Slovakia production/warehouse or prep center | Own barcode/FNSKU needed | Required | 60 | Assigned by Amazon Seller Central | Selected for minimal first batch | Separate sellable unit / ASIN candidate. |
| SnEco Cheddar 6-pack | 6 x Cheddar 28g | 6 | 168g | Main pack candidate | Slovakia production/warehouse or prep center | Own barcode/FNSKU needed | Required | 60 | Assigned by Amazon Seller Central | Selected for minimal first batch | Separate sellable unit / ASIN candidate. |
| SnEco Mixed 6-pack | 3 x Gouda 28g + 3 x Cheddar 28g | 6 | 168g | Variety/discovery pack | Slovakia production/warehouse or prep center | Own barcode/FNSKU needed | Required | 80 | Assigned by Amazon Seller Central | Selected for minimal first batch | Separate sellable unit / ASIN candidate. |
| SnEco Gouda 15-pack | 15 x Gouda 28g | 15 | 420g | Bulk/value pack | Slovakia production/warehouse or prep center | Own barcode/FNSKU needed | Required | 20 | Assigned by Amazon Seller Central | Selected for minimal first batch | Separate sellable unit / ASIN candidate. |
| SnEco Cheddar 15-pack | 15 x Cheddar 28g | 15 | 420g | Bulk/value pack | Slovakia production/warehouse or prep center | Own barcode/FNSKU needed | Required | 20 | Assigned by Amazon Seller Central | Selected for minimal first batch | Separate sellable unit / ASIN candidate. |

## Selected Minimal First FBA Launch Batch

| Selling unit | Launch quantity | Pouches per unit | Gouda pouches required | Cheddar pouches required | Total pouches required | Strategic role | Replenishment logic | Status | Notes |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| SnEco Gouda 3-pack | 40 | 3 | 120 | 0 | 120 | Entry pack | Fast replenishment supports minimal test quantity | Selected | First shipment should be planned as one consolidated FBA inbound shipment where possible. |
| SnEco Cheddar 3-pack | 40 | 3 | 0 | 120 | 120 | Entry pack | Fast replenishment supports minimal test quantity | Selected | First shipment should be planned as one consolidated FBA inbound shipment where possible. |
| SnEco Gouda 6-pack | 60 | 6 | 360 | 0 | 360 | Main pack candidate | Fast replenishment supports minimal test quantity | Selected | Germany / amazon.de may be used as first operational anchor if Seller Central and category checks support it. |
| SnEco Cheddar 6-pack | 60 | 6 | 0 | 360 | 360 | Main pack candidate | Fast replenishment supports minimal test quantity | Selected | Germany / amazon.de may be used as first operational anchor if Seller Central and category checks support it. |
| SnEco Mixed 6-pack | 80 | 6 | 240 | 240 | 480 | Variety/discovery pack | Fast replenishment supports minimal test quantity | Selected | Amazon may split inbound shipment depending on Seller Central workflow. |
| SnEco Gouda 15-pack | 20 | 15 | 300 | 0 | 300 | Bulk/value pack | Fast replenishment supports minimal test quantity | Selected | Avoids overstocking while testing bulk/value pack demand. |
| SnEco Cheddar 15-pack | 20 | 15 | 0 | 300 | 300 | Bulk/value pack | Fast replenishment supports minimal test quantity | Selected | Avoids overstocking while testing bulk/value pack demand. |
| Total | 320 |  | 1020 | 1020 | 2040 |  | Approximately 5 days from request to Amazon availability, subject to Amazon receiving/check-in | Selected | Total net product weight: 57.12 kg. |

## Operational Assumptions

- First shipment should be planned as one consolidated FBA inbound shipment where possible.
- Actual Amazon fulfillment center destination will be assigned by Amazon Seller Central.
- Germany / amazon.de may be used as the first operational anchor if Seller Central and category checks support it.
- Amazon may split inbound shipment depending on Seller Central workflow.
- Replenishment lead time assumption: approximately 5 days from request to Amazon availability, subject to Amazon receiving/check-in.
- Replenishment estimate includes approximately 2-3 days for preparation plus 1-2 days for logistics.
- Because replenishment is fast, the first batch intentionally avoids overstocking.

## Required Inputs

- Final pack dimensions
- Final gross weight
- Units per shipping carton
- Carton dimensions
- Carton gross weight
- Assembly location
- Barcode/FNSKU approach
- Sold as set / Do not separate labeling
- First test quantity per selling unit
- Inbound destination assumption

## Current Status

Minimal first FBA launch batch selected. FBA planning cannot be completed until final multipack dimensions, gross weights, carton configuration, assembly process, and barcode/FNSKU approach are confirmed.
