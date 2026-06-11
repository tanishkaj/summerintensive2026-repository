# Summer Intensive 2026 — Tanishka Joshi

**Live site:** https://tanishkajoshi.github.io/summerintensive2026-repository/

Research and computational work from the Gresham Lab Summer Research Intensive, May–June 2026.

---

## Projects

### Sampling Distribution of the Mean (`sampling_distribution.Rmd`)

An interactive R notebook exploring one of the most important ideas in statistics: the **Central Limit Theorem (CLT)**.

**What it does:**

- Generates a large, right-skewed population (exponential distribution) to represent something clearly non-normal, like wait times or income
- Draws **1,000 random samples** from that population at three different sample sizes — small (n = 5), medium (n = 30), and large (n = 100)
- Computes the mean of each sample and plots the resulting **sampling distributions** using ggplot2
- Overlays a fitted normal curve on each distribution to show how closely the sample means follow a bell curve
- Compares the **observed standard error** from the simulation to the theoretical formula σ/√n

**What you learn:**

- Why sample means tend to be normally distributed even when the underlying data is not
- How increasing sample size shrinks the spread of sample means (smaller standard error = more reliable estimates)
- Why n ≈ 30 is a common rule of thumb for the CLT to "kick in"
- The intuition behind confidence intervals and hypothesis tests, which rely on this behavior

**To run:** open `sampling_distribution.Rmd` in RStudio and click **Knit**. Requires `ggplot2`, `dplyr`, and `tidyr`.

---

### Arithmetic Functions in R (`analysis.R`)

An R script exploring basic arithmetic operations and functions in R.

---

*Gresham Lab Summer Intensive 2026*

