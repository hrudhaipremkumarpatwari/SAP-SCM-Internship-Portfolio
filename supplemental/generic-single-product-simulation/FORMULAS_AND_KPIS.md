# Formula and KPI reference

All data are simulated training data. Use the named columns in the workbook/CSV files.

| Measure | Formula | Interpretation |
|---|---|---|
| Forecast error | Actual − Forecast | Positive indicates forecast was below demand. |
| Absolute error | `ABS(Actual − Forecast)` | Error size without direction. |
| Period MAPE | `ABS(Actual − Forecast) / Actual × 100` | Percentage forecast error for one period. |
| Mean MAPE | `AVERAGE(period MAPE)` | Equal-weight average across periods. |
| Closing component stock | Opening + receipts − (production × 2) | RM-01 inventory after production consumption. |
| Production attainment | Output / demand | Share of demand produced in-period. |
| Capacity utilization | Output / available capacity | Share of available capacity used. |
| Fill rate | Shipped / demand | Share of demand fulfilled in the period. |
| Backorders | Demand − shipped | Unfilled demand carried/left open in the simplified model. |
| Freight cost | Shipped × unit freight assumption | Scenario estimate in INR. |
| Supplier on-time delivery | On-time receipts / total receipts | Here supplied as a scenario assumption, not derived from shipment records. |

## Before/after comparison

The comparisons are conditional on modeled changes to forecast review, supplier selection, production capacity, and distribution design. Since several levers change together, the dataset does not isolate causal effects. Do not describe the differences as actual savings, achieved business benefits, or SAP-generated results.

