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
| SnEco Gouda 3-pack | 3 x Gouda 28g | 3 | 84g | Entry pack | Slovakia production/warehouse or prep center | Own barcode/FNSKU needed | Required | TBD | TBD | Needs data | Separate sellable unit / ASIN candidate. |
| SnEco Cheddar 3-pack | 3 x Cheddar 28g | 3 | 84g | Entry pack | Slovakia production/warehouse or prep center | Own barcode/FNSKU needed | Required | TBD | TBD | Needs data | Separate sellable unit / ASIN candidate. |
| SnEco Gouda 6-pack | 6 x Gouda 28g | 6 | 168g | Main pack candidate | Slovakia production/warehouse or prep center | Own barcode/FNSKU needed | Required | TBD | TBD | Needs data | Separate sellable unit / ASIN candidate. |
| SnEco Cheddar 6-pack | 6 x Cheddar 28g | 6 | 168g | Main pack candidate | Slovakia production/warehouse or prep center | Own barcode/FNSKU needed | Required | TBD | TBD | Needs data | Separate sellable unit / ASIN candidate. |
| SnEco Mixed 6-pack | 3 x Gouda 28g + 3 x Cheddar 28g | 6 | 168g | Variety/discovery pack | Slovakia production/warehouse or prep center | Own barcode/FNSKU needed | Required | TBD | TBD | Needs data | Separate sellable unit / ASIN candidate. |
| SnEco Gouda 15-pack | 15 x Gouda 28g | 15 | 420g | Bulk/value pack | Slovakia production/warehouse or prep center | Own barcode/FNSKU needed | Required | TBD | TBD | Needs data | Separate sellable unit / ASIN candidate. |
| SnEco Cheddar 15-pack | 15 x Cheddar 28g | 15 | 420g | Bulk/value pack | Slovakia production/warehouse or prep center | Own barcode/FNSKU needed | Required | TBD | TBD | Needs data | Separate sellable unit / ASIN candidate. |

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

Needs data. FBA planning cannot be completed until final multipack dimensions, gross weights, carton configuration, assembly process, and barcode/FNSKU approach are confirmed.
