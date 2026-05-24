# SnEco Unit Economics

## Public Repository Rule

This repository is public. Do not include confidential costs, supplier pricing, private documents, personal data, credentials, or non-public commercial strategy.

Use blanks or `TBD` for unknown cost and pricing fields until approved public-safe values are available.

## Active Base Products

- SnEco Gouda 28g EN
- SnEco Cheddar 28g EN

## Selling-Unit Rules

- Each selling-unit scenario is a separate Amazon sellable unit / ASIN candidate.
- Do not include 10-pack in the current active model.
- Amazon FBA should not be expected to assemble multipacks from loose single pouches.
- Each multipack must be physically assembled before inbound to Amazon FBA, either at the Slovakia production/warehouse level or through a prep center.
- Each multipack should have its own barcode/FNSKU and "Sold as set / Do not separate" handling logic.

## Active SnEco Amazon Selling-Unit Scenarios

| Selling unit ID | Composition | Total pouch count | Total net weight | Strategic role | FBA suitability assumption | Bundle packaging needed | Assembly location assumption | Cost data status | Pricing data status | Notes |
| --- | --- | ---: | --- | --- | --- | --- | --- | --- | --- | --- |
| SnEco Gouda 3-pack | 3 x Gouda 28g | 3 | 84g | Entry pack | FBA candidate, needs final dimensions, gross weight, expiration-date handling, and prep checks | Yes | Slovakia production/warehouse or prep center | TBD | TBD | Separate sellable unit / ASIN candidate. |
| SnEco Cheddar 3-pack | 3 x Cheddar 28g | 3 | 84g | Entry pack | FBA candidate, needs final dimensions, gross weight, expiration-date handling, and prep checks | Yes | Slovakia production/warehouse or prep center | TBD | TBD | Separate sellable unit / ASIN candidate. |
| SnEco Gouda 6-pack | 6 x Gouda 28g | 6 | 168g | Main pack candidate | FBA candidate, needs final dimensions, gross weight, expiration-date handling, and prep checks | Yes | Slovakia production/warehouse or prep center | TBD | TBD | Separate sellable unit / ASIN candidate. |
| SnEco Cheddar 6-pack | 6 x Cheddar 28g | 6 | 168g | Main pack candidate | FBA candidate, needs final dimensions, gross weight, expiration-date handling, and prep checks | Yes | Slovakia production/warehouse or prep center | TBD | TBD | Separate sellable unit / ASIN candidate. |
| SnEco Mixed 6-pack | 3 x Gouda 28g + 3 x Cheddar 28g | 6 | 168g | Variety/discovery pack | FBA candidate, needs final dimensions, gross weight, expiration-date handling, and prep checks | Yes | Slovakia production/warehouse or prep center | TBD | TBD | Separate sellable unit / ASIN candidate. |
| SnEco Gouda 15-pack | 15 x Gouda 28g | 15 | 420g | Bulk/value pack | FBA candidate, needs final dimensions, gross weight, expiration-date handling, and prep checks | Yes | Slovakia production/warehouse or prep center | TBD | TBD | Separate sellable unit / ASIN candidate. |
| SnEco Cheddar 15-pack | 15 x Cheddar 28g | 15 | 420g | Bulk/value pack | FBA candidate, needs final dimensions, gross weight, expiration-date handling, and prep checks | Yes | Slovakia production/warehouse or prep center | TBD | TBD | Separate sellable unit / ASIN candidate. |

## Selected Minimal First FBA Launch Batch

| Selling unit | Launch quantity | Pouches per unit | Gouda pouches required | Cheddar pouches required | Total pouches required | Strategic role | Replenishment logic | Status | Notes |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| SnEco Gouda 3-pack | 40 | 3 | 120 | 0 | 120 | Entry pack | Fast replenishment supports minimal test quantity | Selected | Unit economics still needs COGS, bundle packaging, assembly, FBA fee, VAT, and target price. |
| SnEco Cheddar 3-pack | 40 | 3 | 0 | 120 | 120 | Entry pack | Fast replenishment supports minimal test quantity | Selected | Unit economics still needs COGS, bundle packaging, assembly, FBA fee, VAT, and target price. |
| SnEco Gouda 6-pack | 60 | 6 | 360 | 0 | 360 | Main pack candidate | Fast replenishment supports minimal test quantity | Selected | Unit economics still needs COGS, bundle packaging, assembly, FBA fee, VAT, and target price. |
| SnEco Cheddar 6-pack | 60 | 6 | 0 | 360 | 360 | Main pack candidate | Fast replenishment supports minimal test quantity | Selected | Unit economics still needs COGS, bundle packaging, assembly, FBA fee, VAT, and target price. |
| SnEco Mixed 6-pack | 80 | 6 | 240 | 240 | 480 | Variety/discovery pack | Fast replenishment supports minimal test quantity | Selected | Unit economics still needs COGS, bundle packaging, assembly, FBA fee, VAT, and target price. |
| SnEco Gouda 15-pack | 20 | 15 | 300 | 0 | 300 | Bulk/value pack | Fast replenishment supports minimal test quantity | Selected | Unit economics still needs COGS, bundle packaging, assembly, FBA fee, VAT, and target price. |
| SnEco Cheddar 15-pack | 20 | 15 | 0 | 300 | 300 | Bulk/value pack | Fast replenishment supports minimal test quantity | Selected | Unit economics still needs COGS, bundle packaging, assembly, FBA fee, VAT, and target price. |
| Total | 320 |  | 1020 | 1020 | 2040 |  | Approximately 5 days from request to Amazon availability, subject to Amazon receiving/check-in | Selected | Total net product weight: 57.12 kg. |

## Launch Batch Assumptions

- First shipment should be planned as one consolidated FBA inbound shipment where possible.
- Actual Amazon fulfillment center destination will be assigned by Amazon Seller Central.
- Germany / amazon.de may be used as the first operational anchor if Seller Central and category checks support it.
- Amazon may split inbound shipment depending on Seller Central workflow.
- Replenishment lead time assumption: approximately 5 days from request to Amazon availability, subject to Amazon receiving/check-in.
- Replenishment estimate includes approximately 2-3 days for preparation plus 1-2 days for logistics.
- Because replenishment is fast, the first batch intentionally avoids overstocking.

## Required Next Inputs

- COGS per Gouda pouch
- COGS per Cheddar pouch
- Bundle packaging cost
- Assembly cost
- Inbound logistics assumption
- FBA fee estimate
- Referral fee assumption
- Target selling price
- VAT assumption by marketplace
- Ad cost assumption
- Final pack dimensions and gross weight
- Finished unit cost for selected minimal batch
- Bundle packaging cost for selected minimal batch
- Assembly cost for selected minimal batch
- Carton configuration for selected minimal batch
- FNSKU/barcode labeling cost and process
