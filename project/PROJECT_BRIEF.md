# Project Brief

## 1. Business Problem

The Housing and Economic Development Board is under pressure to respond to housing affordability and supply concerns, but current reporting relies heavily on headline house prices. A high price does not automatically mean affordability is deteriorating, and a sharp monthly increase may simply reflect transaction mix or short-term volatility.

This creates a policy and investment prioritisation problem. Leadership needs to understand which areas show sustained market pressure across several indicators, where the evidence is only price-based, and what additional income, supply, planning or demographic data is required before stronger affordability conclusions can be made.

The business problem is to create a transparent housing-market intelligence product that distinguishes observed market pressure from true affordability and directs policy/development teams toward areas that warrant deeper investigation.

## What the Team Needs to Do

The team is expected to build a housing-market pressure and investigation-prioritisation solution.

The work should include:
- defining the policy/development decision and stakeholder needs;
- building a governed historical HPI analytical model;
- standardising geography, reporting period, property type and buyer-type fields;
- analysing sustained price change rather than one-period movements;
- adding transaction/activity context where supported;
- comparing property-type and buyer-type patterns using compatible measures;
- creating a multi-indicator market-pressure framework;
- testing alternative look-back windows and composite weights;
- documenting the additional evidence needed for a true affordability assessment;
- building policy/development BI with clear distinction between evidence and hypothesis;
- completing reconciliation, UAT and handover.

## Practical Use Case

The finished product should support a housing strategy or investment-planning meeting. A Director should be able to identify areas where price growth has persisted, transaction activity and property mix support the concern, and decide which locations warrant deeper affordability, planning or development analysis.

The product must not label an area “unaffordable” based only on house prices and must not be presented as investment advice.

## 2. Business Decision
> **Which housing-market areas show the strongest evidence of sustained market and affordability pressure, and where should development, policy or investment teams investigate first?**

## 3. Agreed Objectives
1. Build a governed historical HPI analytical model with consistent geography, period, property and buyer dimensions.
2. Distinguish sustained market pressure from one-period price changes.
3. Create transparent pressure indicators while clearly separating house-price evidence from true income-based affordability.
4. Identify areas warranting deeper policy/development investigation rather than automatic intervention.
5. Provide a decision-support product with explicit data gaps and next-evidence requirements.

## 4. Key Business Questions
1. Which geographies show sustained price growth over multiple periods?
2. How do transaction activity and property type alter the interpretation of price pressure?
3. How do first-time buyer/new/existing property measures differ where supported?
4. Which areas appear pressured under multiple indicators rather than price alone?
5. What additional income, supply, planning or demographic evidence is required for a true affordability conclusion?
6. How sensitive are priority areas to alternative look-back windows or indicator weights?

## 5. Cross-Functional Roles
| Role | Minimum expected output |
|---|---|
| Business Analyst | Define housing-policy/investment decision, user needs and acceptance criteria. |
| Data Governance Analyst | Govern geography, measures, history, lineage and quality. |
| Data Engineer | Build reproducible HPI ingestion and historical analytical model. |
| Housing/Data Analyst | Own price, transaction, property/buyer and geographic analysis. |
| BI Developer | Build market-pressure decision support and drill-down. |
| Economist / Policy Analyst | Interpret market evidence and identify external evidence required. |
| Data Scientist | Develop transparent segmentation/scenario logic where justified. |
| Model Governance / Assurance | Challenge proxies, thresholds, sensitivity and decision use. |

## 6. Minimum Delivery Standard
Traceable requirements; governed definitions/lineage; preserved raw data; reproducible transformation; reconciliation; project-specific analysis; transparent decision logic; governed BI; UAT; handover; collaborative evidence.

## 7. Constraints
- House prices alone do not measure affordability.
- Transaction changes may reflect market composition rather than underlying demand alone.
- Geographic series and property/buyer categories must be compared on compatible definitions.
- Priority indicators must not be presented as investment advice.
- Any composite score must expose its assumptions and sensitivity.

## 8. Agreed Success Criteria
- Every geography and period in the curated model uses documented HPI definitions and granularity.
- At least five selected geography/period values reconcile directly to the frozen HPI source.
- No output labels an area unaffordable solely from house-price level or growth.
- Priority areas require multiple documented indicators or an explicit exception rationale.
- Any composite market-pressure score exposes all components and weights and includes sensitivity analysis.
- Property-type and buyer-type comparisons use compatible source measures and do not mix incomparable series.

## 9. Out of Scope
Core delivery excludes confidential personal data, paid production infrastructure, automated operational decisions and unsupported causal inference.

## 10. Reproducibility Definition
A reviewer should be able to clone the team repository, obtain the approved source data, execute the workflow and reproduce curated outputs and validation evidence without undocumented manual changes.
