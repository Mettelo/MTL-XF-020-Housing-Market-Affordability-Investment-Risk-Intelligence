# Data Guidance

## Approved Core Dataset

Use the **UK House Price Index (UK HPI) — June 2026 full historical CSV**.

Official source:
https://www.gov.uk/government/statistical-data-sets/uk-house-price-index-data-downloads-june-2026

The full file is small and includes the long historical UK HPI series.

## What to Put in `data/raw/`

Store the original CSV unchanged:

```text
data/raw/
└── uk-hpi-full-file-2026-06.csv
```

The file is small enough to commit directly to GitHub.

## Core Time Scope

Do **not** use the entire historic series automatically just because it is available.

Recommended core period:
- latest **10 years** for the main market-pressure analysis.

Use the earlier back series only for long-term context where it adds value.

## Recommended Geographic Scope

Choose a manageable policy/development scope, for example:
- one region;
- selected local authorities;
- comparable neighbouring areas;
- a defined group of housing markets.

Document the selection rationale.

The core project should not attempt every UK geography unless the team has a clear reason.

## Recommended Analytical Grain

Use a clearly documented:
**geography × reporting period** main fact table.

Keep property-type and buyer-type measures in compatible supporting tables or a controlled long-format model.

## Additional Attribute Files

The publisher also provides small separate CSVs for:
- average price;
- average price by property type;
- sales;
- cash/mortgage sales;
- first-time buyer/former owner occupier;
- new build/existing resold property;
- index;
- seasonally adjusted measures;
- repossessions.

These may be added where they directly support the agreed business questions.

Do not download every attribute file simply because it exists.

## Affordability Rule

UK HPI is a **housing-market** dataset, not a complete affordability dataset.

For true affordability analysis, teams would need additional evidence such as:
- household income;
- rents;
- housing supply;
- planning/development;
- demographic context.

Those are optional extensions and should be documented separately.

## Time-Series Guidance

Before comparing periods:
- confirm geography continuity;
- check revision notes;
- avoid mixing incomparable measures;
- use sustained multi-period trends rather than single-month movements.

## Optional Extensions

After the core 10-year HPI analysis is complete, a team may add:
- ONS earnings/income data;
- housing supply data;
- planning data;
- rental data.

These should enrich, not replace, the frozen HPI baseline.

## Assessment Baseline

The core project must remain reproducible from the frozen June 2026 UK HPI full CSV alone.
