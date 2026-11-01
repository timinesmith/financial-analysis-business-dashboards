# KPI Dashboard Specification

**Status:** Illustrative demonstration using synthetic data definitions only.

## Audience

Executive and operations leaders who need a one-page view of performance, cash, delivery risk, and required decisions.

## KPI set

| KPI | Definition | Frequency | Owner | Alert rule |
|---|---|---|---|---|
| Revenue vs. budget | Actual revenue divided by budgeted revenue | Weekly | Operations | Below 95% |
| Gross margin | Revenue less direct costs, divided by revenue | Weekly | Finance | Declines 3+ points |
| Payroll percentage | Payroll divided by revenue | Weekly | Finance | Above approved threshold |
| Open AP over 30 days | Value of unpaid invoices aged over 30 days | Weekly | Finance | Any increase for two weeks |
| Forecast cash low point | Lowest projected cash balance in forecast horizon | Weekly | Finance | Below reserve policy |
| Milestone completion | Completed milestones divided by planned milestones | Weekly | Program lead | Below 90% |
| Customer repeat rate | Returning customers divided by active customers | Monthly | Sales/operations | Downward trend |

## Design rules

- Every KPI has a named owner and a written definition.
- Charts show plan, actual, and forecast where applicable.
- Variances require a short explanation and next action.
- Source refresh date appears on the dashboard.
- Access to underlying financial records remains restricted; the dashboard is a summary, not a substitute for the ledger.
