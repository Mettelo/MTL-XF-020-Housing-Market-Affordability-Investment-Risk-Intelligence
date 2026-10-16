# Business Context

## Business Problem

The Housing and Economic Development Board is under pressure to respond to housing affordability and supply concerns, but current reporting relies heavily on headline house prices. A high price does not automatically mean affordability is deteriorating, and a sharp monthly increase may simply reflect transaction mix or short-term volatility.

This creates a policy and investment prioritisation problem. Leadership needs to understand which areas show sustained market pressure across several indicators, where the evidence is only price-based, and what additional income, supply, planning or demographic data is required before stronger affordability conclusions can be made.

The business problem is to create a transparent housing-market intelligence product that distinguishes observed market pressure from true affordability and directs policy/development teams toward areas that warrant deeper investigation.

## Required Delivery Response

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

## How the Client Will Use the Output

The finished product should support a housing strategy or investment-planning meeting. A Director should be able to identify areas where price growth has persisted, transaction activity and property mix support the concern, and decide which locations warrant deeper affordability, planning or development analysis.

The product must not label an area “unaffordable” based only on house prices and must not be presented as investment advice.

## Client
**Confidential Regional Housing & Economic Development Board**

## Problem
The board faces pressure to support housing supply and affordability, but current reporting over-focuses on headline prices. Leadership cannot consistently separate sustained price pressure, transaction activity, property mix, buyer type and geography when deciding where intervention or further investment analysis is justified.

## Decision Owner
**Director of Housing Strategy**

## Stakeholders
Housing Development Lead, Planning Policy Lead, Economic Strategy Lead, Finance/Investment Lead, Data Governance Lead, BI & Insight Lead, Research/Evaluation Lead

## Decision
**Which housing-market areas show the strongest evidence of sustained market and affordability pressure, and where should development, policy or investment teams investigate first?**

## Role Responsibilities
| Role | Required contribution |
|---|---|
| Business Analyst | Define housing-policy/investment decision, user needs and acceptance criteria. |
| Data Governance Analyst | Govern geography, measures, history, lineage and quality. |
| Data Engineer | Build reproducible HPI ingestion and historical analytical model. |
| Housing/Data Analyst | Own price, transaction, property/buyer and geographic analysis. |
| BI Developer | Build market-pressure decision support and drill-down. |
| Economist / Policy Analyst | Interpret market evidence and identify external evidence required. |
| Data Scientist | Develop transparent segmentation/scenario logic where justified. |
| Model Governance / Assurance | Challenge proxies, thresholds, sensitivity and decision use. |

## Evidence Chain
**Requirement → governed definition → transformation → quality control → metric/analysis → decision insight → recommendation → UAT**
