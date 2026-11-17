# Justin Target

Engineering student at ESILV (Paris), specializing in Financial Engineering. I build interest rate models from scratch in Python and validate them against independent benchmarks.

Seeking a **work-study placement** in Global Markets / Quantitative Finance (Fixed Income, Credit, FX), starting **September 2027**.

## Featured projects

| Project | Key result | Tools |
|---|---|---|
| [Nelson-Siegel-Svensson calibration](https://github.com/Target-Justin/nelson-siegel-svensson-oat-calibration) | NS/NSS fitted on French OATs and 13 €STR/SOFR OIS curves (1W–50Y). NS fails on long maturities (43 bp median max error) while NSS stays under 5 bp; two independent calibration methods agree within 0.01 bp. | Python, SciPy, Pandas |
| [Zero-coupon yield curve bootstrap](https://github.com/Target-Justin/Zero-Coupon-Yield-Curve-Bootstrap) | From-scratch bootstrap of 19 French OATs and 13 OIS curves. Matches QuantLib within 0.25 bp on OATs and 10⁻⁷ bp on OIS. | Python, Pandas, QuantLib |
| [PONAX audit forecasting][(https://github.com/Target-Justin/ponax-audit-forecasting)] | Bond factors (TERM, DEF) built from FRED raise adjusted R² from 0.52 to 0.67 vs Fama-French; Jensen's alpha not significant. ARMA backtest: past returns do not beat the historical mean. | Python, statsmodels, pandas |

🚧 **In progress: Hull-White short rate model.** Step 1 done: Vasicek simulation validated against closed-form moments, zero-coupon pricing. Next: Hull-White calibration to the curve, then maximum-likelihood estimation.

## Experience

**Quant Developer @ VQM Capital** (student quant-macro fund, paper trading)
- `VQM Data Platform` *(private)*: backtesting engine and data library. Transaction costs, FRED US rates with look-ahead control, strategy implementation, tests.
- `VQM Research` *(private)*: research team's strategy repository, turned into production strategies on the platform.

**Order Flow Alpha & Optimal Execution, Amundi Asset Management** (ESILV research project, team of 5) *(private repo)*
Order-flow signals and optimal execution (Almgren-Chriss vs TWAP/VWAP). My part: analysis of executions, cancellations and market impact.

## Stack

Python · Pandas · NumPy · SciPy · QuantLib · statsmodels · pytest · Git

## Contact

[LinkedIn](https://www.linkedin.com/in/justin-target/?locale=en-US) · justin.target.pro@gmail.com
