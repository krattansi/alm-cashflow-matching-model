# 📊 alm-cashflow-matching-model
This project is an Excel simulation of an asset-liability cashflow matching strategy, designed to help ALM actuaries asses whether bond portfolios can fully cover scheduled liabilities while minimizing duration gap risk.

## 📌 Features
- User-defined liability amount, years to match, and bond portfolio
- Calculates present values and Macaulay durations of liabilities and bond asset cash flows
- Conditional formatting to show cash flow sufficiency, both cumulative and by year
- Duration gap output to assess interest rate risk
- Integrated Solver to optimize bond face values for sufficiency and low duration gap (<0.1)
- Built in Excel (.xlsx) with multi-sheet model logic

## 📈 Sheets Overview
- **Inputs**: Set parameters such as liability amount, liability duration, discount rate, duration gap threshold, and bond portfolio
- **Liabilities**: Calculates liability PVs and Macaulay duration
- **Bonds**: Cash flow table for the bonds + solvency checks
- **Duration**: Calculates asset PVs and Macaulay duration + gap analysis
- **Graphs**: Visualization of annual and cumulative cash flows for both assets and liabilities

## 🔧 Future Improvements
- Automate Solver using VBA for perfect and hands-free bond face value optimization
- Add stress testing/sensitivity tables for interest rate shocks

## 🎓 Why This Project?
I developed this model to explore how asset-liability management (ALM) decisions are made using real-world techniques, such as cash flow matching and duration optimization. This project strengthens my understanding of both actuarial risk mathematics and Excel modeling while providing me with an early insight into the world of ALM.
