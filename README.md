# Leveraged_Buyout_Model
Leveraged buyout modeling project covering acquisition financing, sources and uses, five-year operating forecasts, debt repayment waterfalls, investor IRR/MOIC, sensitivity analysis, and downside scenarios.
# Leveraged Buyout Model

A financial modeling project designed to evaluate debt-funded acquisitions, forecast debt repayment capacity, and estimate investor returns under different operating and exit assumptions.

**Status:** In development. The sections below describe the intended scope.

## Overview

A leveraged buyout (LBO) is an acquisition financed with a combination of debt and investor equity. After the acquisition, the company’s available cash flow supports debt repayment. At exit, the equity investor receives the proceeds remaining after outstanding debt and applicable costs are settled.

This project examines three questions:

- How much equity is required to fund the acquisition?
- Can the business generate enough cash to service and repay its debt?
- What returns could investors earn under different assumptions?

## Planned Model Components

| Component | Purpose |
|---|---|
| Transaction assumptions | Define purchase valuation, financing mix, fees, and investment horizon. |
| Sources and uses | Reconcile acquisition costs with debt and equity funding. |
| Five-year operating forecast | Project revenue, EBITDA, taxes, capital expenditure, and working capital requirements. |
| Debt repayment waterfall | Allocate available cash to required and optional repayments according to debt terms. |
| Exit valuation | Estimate the business’s sale value and proceeds attributable to investors. |
| Investor returns | Calculate multiple on invested capital (MOIC) and internal rate of return (IRR). |
| Sensitivity analysis | Measure how selected assumptions affect investment returns. |
| Downside case | Assess liquidity, debt repayment, and investor outcomes under weaker performance. |

## Modeling Workflow

1. Define the acquisition price and transaction costs.
2. Build a balanced sources-and-uses schedule.
3. Forecast operating performance over five years.
4. Calculate cash available for debt service.
5. Calculate interest, required repayments, and optional debt paydown.
6. Estimate exit enterprise value and bridge to equity proceeds.
7. Calculate investor returns.
8. Evaluate sensitivities and downside scenarios.

## Core Financial Logic

**Sources and uses**

Total funding must equal the total cash required to complete the transaction. Investor equity funds the amount not covered by other financing sources.

**Debt balances**

Ending debt equals beginning debt plus new borrowing and any capitalized interest, less principal repayments.

**Exit valuation**

Exit enterprise value is estimated using exit EBITDA multiplied by an assumed exit valuation multiple. Equity proceeds reflect remaining debt, available cash, and applicable exit costs.

**Investor returns**

- **MOIC:** Total equity proceeds divided by total equity invested.
- **IRR:** The discount rate that makes the net present value of investor cash flows equal to zero.

MOIC measures the investment multiple; IRR also reflects cash-flow timing.

## Planned Sensitivity Analysis

The model will evaluate the impact of:

- Entry and exit valuation multiples.
- Revenue growth and operating margins.
- Initial leverage and borrowing costs.
- Investment holding period.

Sensitivity tables will show how changing selected assumptions affects IRR and MOIC.

## Downside Case

The downside scenario will combine weaker operating performance with less favorable exit assumptions.

The analysis will examine:

- Ability to pay interest and required principal repayments.
- Minimum cash requirements and funding shortfalls.
- Remaining debt at exit.
- Reduction in investor returns and potential equity losses.

Additional borrowing will be constrained by modeled financing availability; funding shortfalls will be flagged explicitly.

## Planned Validation Checks

- Sources equal uses.
- Debt balances reconcile across periods.
- Repayments do not exceed outstanding principal.
- Optional repayments respect available cash and minimum liquidity.
- Cash shortfalls are identified.
- Exit equity proceeds reconcile to enterprise value.
- Return calculations use consistent cash-flow signs and timing.

## Expected Outputs

- Acquisition funding summary.
- Five-year financial forecast.
- Debt balances and repayment schedules.
- Exit valuation and equity proceeds.
- Investor IRR and MOIC.
- Return sensitivity tables.
- Base-versus-downside comparison.

## Project Purpose

Develop practical understanding of acquisition financing, cash-flow modeling, debt mechanics, and private equity investment analysis through a transparent and auditable LBO model.

## Limitations

This is an educational project. Results will depend on the assumptions and financial data used. Simplified financing, tax, and transaction treatments may differ from actual deals.
