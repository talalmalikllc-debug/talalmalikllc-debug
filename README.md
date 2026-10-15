# Hi, I'm Muhammad Talal Malik 👋

**Quantitative Researcher & Data Analyst** · Founder of [Khurjeen.pk](https://khurjeen.pk)
📍 Pakistan · 🌍 Open to remote roles

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/talal-malik-inc-marketing-agency-fb/) [![Email](https://img.shields.io/badge/Email-talalmalikllc%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:talalmalikllc@gmail.com) [![Store](https://img.shields.io/badge/Store-Khurjeen.pk-96BF48?logo=shopify&logoColor=white)](https://khurjeen.pk)

I do **academic-driven quantitative research**. I start from published findings in empirical finance, replicate them on instruments that people actually trade, and then build and test **my own hypotheses** where the original result is weak, too costly to trade, or not fully explained. Every idea is a falsifiable hypothesis with a stated null. Each one is tested with out-of-sample discipline and reported honestly, including the ideas that fail.

I also run my own private-label e-commerce brand, so I'm used to making decisions with real money on the line.

---

### 🧪 How I research

```
 Academic paper  ──►  Replicate on a tradable market  ──►  Find where the effect lives (or dies)
        │                                                              │
        ▼                                                              ▼
 Form my own hypothesis (H₀ / H₁)  ──►  Pre-register rules  ──►  Train → Validate → Test
                                                                       │
                                                                       ▼
                                Costs, robustness checks, full disclosure  ──►  Freeze → forward test
```

1. **Start from the literature.** Take a published result, such as an anomaly, return predictability or a market-microstructure effect, and read it critically.
2. **Replicate before innovating.** Rebuild the paper's main test on liquid, tradable futures and compare my numbers with the authors'.
3. **Audit the data first.** Bar-timestamp conventions, session calendars, contract rolls, 1-min vs 5-min consistency and leakage tests come before any result is looked at.
4. **Form my own hypothesis.** Ask *where* and *when* the effect is strongest, and turn that into a testable H₀ / H₁ with a concrete trading rule.
5. **Pre-register and split time.** Fix the candidate rules in advance, choose on training data only, then judge on untouched validation and test periods.
6. **Make it survive reality.** Model transaction costs under several scenarios and stress-test with the bootstrap, best-trade removal, delayed entries and parameter neighbours.
7. **Report everything.** Disclose all rules tried, all limitations and all failures. Freeze the surviving rule and evaluate it only on new data.

---

### 📚 Research log

| Idea | Source | My hypothesis | Outcome |
|---|---|---|---|
| Overnight return → first-half-hour reversal | Iwanaga & Sakemoto (2026), SSRN 5807282 | The paper's SPY reversal also exists in Nasdaq-100 futures | ✅ **Replicated, but weaker:** β×100 = −4.15 (t = −2.42) vs −9.19 for SPY. Most of the effect sits in the first ~5 minutes, which is too small to trade after costs. |
| Momentum instead of reversal | Extension of the above | Trading *with* the overnight move works better | ❌ Rejected in every holding window |
| **Post-open rebound after extreme drops** | My own hypothesis, built on the replication | The reversal is concentrated in *extreme*, volatility-scaled drops once a bounce has started | ✅ **Out of sample: +50.9 pts/trade after costs, t ≈ 2.5** (18 trades). Frozen for forward testing. → [repo](https://github.com/talalmalikllc-debug/nq-post-open-rebound) |
| Overnight drift (close → open) | Overnight-return anomaly literature | Holding NQ overnight earns a premium after costs | ⚠️ Positive over 2016–2026 (t ≈ 2.5), but concentrated before 2021. 26 follow-up filters and enhancements tested: **0 significant**, all reported. |

---

### 🔬 Featured research

**[NQ Post-Open Rebound After Extreme Overnight Drops](https://github.com/talalmalikllc-debug/nq-post-open-rebound)**
Do Nasdaq-100 futures rebound between 09:35 and 10:00 New York time after an extreme overnight drop?

- 10 years of intraday NQ futures data (2016 → 2026), with timestamp, contract-roll and leakage checks
- **Pre-registered** rule selection on training data, then separate validation and test periods
- Out of sample: **18 trades, +50.9 points/trade after costs, t ≈ 2.5**, tested under 4 cost scenarios
- Robustness: bootstrap confidence interval, best-trade removal, delayed entry, and all candidate rules disclosed
- Started as a replication of an academic paper (Iwanaga & Sakemoto, 2026) on overnight-return reversal

`Python` `pandas` `statsmodels` `SciPy` `matplotlib` `Jupyter`

---

### 🛠️ Skills

| Area | What I use |
|---|---|
| **Quant research** | Backtesting, out-of-sample testing, transaction-cost modelling, bootstrap and Monte Carlo, regression, hypothesis testing |
| **Market data** | Intraday futures bars, session calendars, contract rolls, look-ahead and leakage checks |
| **Data analysis** | Python, pandas, NumPy, SciPy, statsmodels, Jupyter, data cleaning and validation |
| **Visualisation** | matplotlib, equity curves, drawdowns, distribution and bucket analysis |
| **E-commerce** | Shopify store management, private-label product sourcing, nationwide fulfilment |

---

### 🛍️ Entrepreneurship: [Khurjeen.pk](https://khurjeen.pk)

I own and run **Khurjeen**, a private-label bags brand in Pakistan, which I co-run with my partner. We sell backpacks, laptop bags, luggage, travel bags and accessories through our own Shopify store, with cash on delivery across Pakistan.

---

### 🎯 What I'm looking for

Roles in **quantitative research, trading research, or data analysis/data science**, remote or hybrid. I'm happy to walk through any of my research in detail. The best way to reach me is [LinkedIn](https://www.linkedin.com/in/talal-malik-inc-marketing-agency-fb/) or email.

### 📫 Contact

- 💼 **LinkedIn:** [Talal Malik](https://www.linkedin.com/in/talal-malik-inc-marketing-agency-fb/)
- ✉️ **Email:** [talalmalikllc@gmail.com](mailto:talalmalikllc@gmail.com)
- 📸 **Instagram:** [@tmfinancials](https://www.instagram.com/tmfinancials)
- 🎵 **TikTok:** [@tmfinancials](https://www.tiktok.com/@tmfinancials)
- 🛒 **Store:** [khurjeen.pk](https://khurjeen.pk)
