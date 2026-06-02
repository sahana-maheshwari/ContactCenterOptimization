# Contact Center Forecasting & Staffing Optimization

A decision-analytics project that forecasts a year of contact-center call volume and uses it to plan staffing and service levels, balancing wait times against cost.

Team project for the **CM4 – Complex Decision-Making** challenge at Hult International Business School.

---

## The problem

Contact centers live on a trade-off: too few agents and wait times blow up; too many and the economics break. The project built a year-long view of call traffic and applied decision frameworks to allocate staff and protect service levels.

## The approach

- **Forecasting:** quarterly call volume modeled with **exponential smoothing** and **moving averages**, then compared against actuals to expose lag and the peaks/drops each method misses.
- **Statistical analysis:** mean vs. median comparisons per quarter to read the shape and stability of each forecast (where the mean exceeds the median, peaks cluster late in the quarter; the reverse front-loads them).
- **Decision tools:** decision trees, Poisson distribution, probability, and the normal distribution applied to resource-allocation and service-level decisions.
- **External factors:** seasonality and outside drivers folded into the staffing recommendations.

## Results

- Forecast vs. actual reconciled across all four quarters: **Q1 was the lowest-volume quarter (under ~3,100 calls)** and **Q4 the highest (~4,000)**, with forecasts and actuals aligning most closely toward year-end.
- Exponential smoothing tracked the real peaks and drops (with a few days' lag); the moving-average forecast smoothed them out and misaligned each quarter.

## Deliverables

- [`A1 Contact Center Management Report.docx`](A1%20Contact%20Center%20Management%20Report.docx) — the full report (~4,159 words): forecasting, statistical analysis, and staffing strategy.

## Stack

- Forecasting (exponential smoothing, moving averages)
- Decision trees, Poisson and normal distributions, probability analysis
