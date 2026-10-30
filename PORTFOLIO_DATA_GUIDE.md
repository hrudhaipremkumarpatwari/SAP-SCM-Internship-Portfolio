# Portfolio Data and Comparability Guide

This guide explains how to interpret figures across the six SAP SCM assessment repositories.

> **Training-data disclosure:** Company names and scenario figures are fictional or illustrative unless a repository explicitly identifies a public source. The projects document learning simulations and configuration blueprints. They do not claim live SAP production execution.

## Portfolio map

| Week | Repository focus | Scenario basis shown in the project | Comparison note |
|---|---|---|---|
| 1 | Supply Chain Network Planning | Deccan Harvest network, sourcing, capacity, inventory positioning, transportation lanes, and SNP planning | Network design blueprint; the README does not define one shared transaction-level time series. |
| 2 | Master Data & Inventory Optimization | Deccan Harvest planning-data quality, inventory parameters, stock-out and excess scenarios | Parameter and data-quality exercise; do not treat its example values as the same run as another week's scenario. |
| 3 | Logistics & Distribution Network Design | Weekly distribution case; modeled trips, utilization, transport cost, and a disruption case | Weekly trips/costs are local to this assessment's stated network and assumptions. |
| 4 | Production Planning & Scheduling | Three products, 138.5 tonnes of weekly demand, packaging-capacity and breakdown recovery calculations | Weekly quantities and capacity use the units and assumptions stated in that analysis. |
| 5 | Integration & Collaboration | A simplified weekly packaging-material delay, plus a proposed event timeline and integration controls | The timeline and interface measures are illustrative process-design examples, not measured system events. |
| 6 | Performance Evaluation & Continuous Improvement | Simulated monthly KPI series from April to September 2026 | The six-month KPI series is a separate performance illustration; trends do not prove that an action caused a change. |

## How the assessments connect

The progression is conceptual: network planning defines locations and flows; master-data governance supports planning; logistics moves and positions inventory; production planning checks capacity and material readiness; integration coordinates changes and exceptions; performance evaluation monitors outcomes and improvement actions.

That learning progression does **not** mean every repository uses one reconciled dataset. The projects were prepared for different assessment scopes and use different measures, units, time windows, and scenario assumptions. Even where the same fictional company name appears, figures should not be joined, summed, or presented as one operating history without an explicit reconciliation.

## Before comparing or combining measures

Confirm all of the following:

1. Same scenario version, product/location population, and business process scope.
2. Same time window and bucket (for example, week versus month).
3. Same unit of measure, currency, and conversion basis.
4. Same KPI numerator, denominator, inclusion rules, and data status.
5. Same baseline/intervention definition and assumptions.
6. Source, calculation, owner, and validation status are documented.

Where any item differs or is unknown, present the measure as a project-specific illustration and explain the limitation.

## Portfolio presentation

Use each repository's own README, supporting analysis, diagrams, and report as the source of truth for that assessment. Label simulated values in any copied chart or table. Describe configuration, planning runs, integration checks, and validation as proposed or simulated unless there is genuine evidence of execution in a SAP environment.

