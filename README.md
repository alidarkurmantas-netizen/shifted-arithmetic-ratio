# A Sharp Lower Bound for a Shifted Arithmetic Function Ratio on Even Integers

[![DOI](https://zenodo.org)](https://doi.org)

**Author:** Alidar Kurmantas  
**Preprint:** [Read full PDF on Zenodo](https://doi.org)

## Overview

This repository accompanies the mathematical note *"A Sharp Lower Bound for a Shifted Arithmetic Function Ratio on Even Integers"*.

We study the shifted ratio of classical arithmetic functions over the set of even positive integers:

$$f(n) = \frac{n^2 \cdot \sigma(n)^2}{\varphi(n+2)^2 \cdot \mathrm{rad}(n+2)}$$

where:
- $\sigma(n)$ is the sum-of-divisors function,
- $\varphi(n)$ is Euler's totient function,
- $\mathrm{rad}(n)$ is the radical of $n$ (the product of distinct prime factors of $n$).

## Main Theorem

> **Theorem.** For every even integer $n \ge 16$, the following sharp inequality holds:
>
> $$\frac{n^2 \cdot \sigma(n)^2}{\varphi(n+2)^2 \cdot \mathrm{rad}(n+2)} \ge \frac{3528}{11} \approx 320.72727\dots$$
>
> Equality holds if and only if $n = 20$.

## Key Findings

1. **Exact Threshold ($n \ge 16$):** For small even integers $2 \le n \le 14$, the bound does not hold (e.g., $f(2) = 4.5$, $f(14) = 110.25$). From $n = 16$ onward, $f(n)$ never drops below $\frac{3528}{11}$.
2. **Sensitivity to Shift ($n+2$ vs. $n+k$):** Computational testing across $299{,}993$ even integers shows that replacing $n+2$ with a random neighbor $n+k$ ($3 \le k \le 200$) causes the observed minimum to drop to $\approx 0.1244$.
3. **Analytical Proof:** Using elementary bounds $\sigma(n) > \frac{3}{2}n$ and $\varphi(n+2)^2 \mathrm{rad}(n+2) \le \frac{(n+2)^3}{4}$ for even $n$, we establish $f(n) > \frac{9n^4}{(n+2)^3}$, which strictly exceeds $328.76$ for all $n \ge 42$.

## Citation

If you reference this work, please cite it using the Zenodo DOI:

```bibtex
@misc{kurmantas2026shifted,
  author       = {Kurmantas, Alidar},
  title        = {A Sharp Lower Bound for a Shifted Arithmetic Function Ratio on Even Integers},
  month        = nov,
  year         = 2026,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.24250739},
  url = {doi.org/10.5281/zenodo.24250739}
}
```
