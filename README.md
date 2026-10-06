## Nikita Ageev

Retail credit risk lead at a Russian fintech bank: portfolio risk, credit limits, unit economics of consumer lending. Previously Yandex and Sber.
PhD in aircraft aerodynamics (TsAGI), MSc in applied mathematics and physics (MIPT), MSc in Finance (New Economic School).

### What I build

- **[Credit Radar](https://github.com/nikita-ageev/credit-radar)** — an open daily monitor of the Russian retail credit market: lending terms of 12 banks, credit bureau releases, Bank of Russia data and news. Built as an LLM workflow: the route is fixed in code, the model works behind code gates and a judge, offline evals run in CI. Issues: [ageev.dev/credit-radar](https://ageev.dev/credit-radar/), Telegram [@rcradar](https://t.me/rcradar).
- **LLM agents for risk analytics** — monitoring and analysis pipelines with explicit quality gates and evals; Credit Radar is the public example.
- **[su2-trimmed-shape-optimization](https://github.com/nikita-ageev/su2-trimmed-shape-optimization)** — trimmed aerodynamic shape optimization with the SU2 discrete adjoint: max L/D at fixed lift and zero pitching moment, FFD parameterization, SLSQP / trust-region SQP, DAKOTA driver. Supersonic wing-body case: L/D 15.9 → 21.5 (trimmed).
- **Contributions to [SU2](https://github.com/su2code/SU2)** (open-source CFD):
  [#2934](https://github.com/su2code/SU2/pull/2934) STATION function names in SU2_PY ·
  [#2935](https://github.com/su2code/SU2/pull/2935) quoting the executable path in SU2_RUN ·
  [#2952](https://github.com/su2code/SU2/pull/2952) fixed-CL finite-difference dCX/dCL written to `flow.meta`.

### Kaggle — [truenikita](https://www.kaggle.com/truenikita)

Datasets:
- [Russian Banks: Retail Credit from CBR Disclosures](https://www.kaggle.com/datasets/truenikita/russian-banks-retail-credit-cbr) — monthly retail loans, provisions, overdue, P&L and ratios of 13 Russian banks (Bank of Russia forms 0409101/102/135)
- [Russian Retail Lending: Bank of Russia Statistics](https://www.kaggle.com/datasets/truenikita/russian-retail-lending-market-cbr) — monthly household loans, overdue debt, mortgages and rates by region, 2019–2026
- [Russian Bank Reviews: Banki.ru Rating 2019–2026](https://www.kaggle.com/datasets/truenikita/russian-bank-reviews-banki-ru-rating) — bank × product × year review aggregates joined with balances and the key rate

Notebooks:
- [Russian Retail Credit 2019–2026 and the Key Rate](https://www.kaggle.com/code/truenikita/russian-retail-credit-2019-2026-and-the-key-rate)
- [Overdue Retail Debt vs Key Rate: 85 Regions](https://www.kaggle.com/code/truenikita/overdue-retail-debt-vs-key-rate-85-regions)
- [Home Credit: From AUC to Money — Cutoff Economics](https://www.kaggle.com/code/truenikita/home-credit-from-auc-to-money-cutoff-economics)
- [Home Credit: PSI, Drift and Re-setting the Cutoff](https://www.kaggle.com/code/truenikita/home-credit-psi-drift-and-re-setting-the-cutoff)

### Background

12 years in applied aerodynamics before credit risk: 40+ papers on aerodynamic design and adjoint shape optimization (2009–2021), taught general physics at MIPT.

[ageev.dev](https://ageev.dev) · [LinkedIn](https://www.linkedin.com/in/nikita-ageev) · [Kaggle](https://www.kaggle.com/truenikita)
