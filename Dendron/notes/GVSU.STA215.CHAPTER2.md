---
id: b42nkty1f6l7z507y5twpm8
title: CHAPTER2
desc: ''
updated: 1726244963595
created: 1725899080215
---
# Analysis of Categorical Data

## Table of Contents <!-- omit from toc -->
- [Analysis of Categorical Data](#analysis-of-categorical-data)
    - [R Cheat Sheet](#r-cheat-sheet)
    - [Graphs:](#graphs)
      - [Quantitative](#quantitative)
      - [Categorical](#categorical)

---

### R Cheat Sheet
<details open>
<summary> Click to expand </summary>

```r
Frequency Table
> tbl_1var(_DATANAME_, ~_VARIABLE_)

Bar Graph Using Percent
> plot_bar(_DATANAME_, ~_VARIABLE_, type = "percent", na_rm = FALSE)

Note: Change to na_rm = TRUE to eliminate missing values from plot.

Bar Graph Using Counts
> plot_bar(_DATANAME_, ~_VARIABLE_, type = "count", na_rm = FALSE)

Note: Change to na_rm = TRUE to eliminate missing values from plot.

Two-Way Table
> tbl_2var(_DATANAME_, _RESPONSE_~_EXPLANATORY_)

Clustered Bar Graph
> plot_bar(_DATANAME_, ~_RESPONSE_, fill = ~_EXPLANATORY_, na_rm = FALSE)
```
</details>

### Graphs:

#### Quantitative 
- Histogram
- Steam and Leaf Plot

#### Categorical
- Bar Chart
- Pie Chart