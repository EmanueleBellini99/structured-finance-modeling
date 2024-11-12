Monte Carlo-based financial modeling tool for structured bonds, featuring pricing, sensitivity analysis, and hedging strategies. This implementation focuses on a case study of an ENEL bond with Asian-style payoffs and floating rate (Euribor) coupons.

Key Features:
- Structured bond pricing using Monte Carlo simulation with Geometric Brownian Motion
- Greeks calculation (Delta, Vega, DV01) for risk assessment
- Hedging strategy computation using stocks, options, and interest rate swaps
- Zero rate curve interpolation and forward rate calculations
- Business day adjustments and multiple day count conventions
- Comprehensive visualization of price paths and convergence analysis

Built with Python, using NumPy, Pandas, and custom financial libraries. Based on established quantitative finance methodologies from Glasserman, Musiela & Rutkowski, and Hull.

Originally developed as a final project for Advanced Mathematical Models in Finance at Politecnico di Milano.
