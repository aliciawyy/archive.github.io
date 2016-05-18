---
layout: post
title: Performance Measures
---

- **High Water Mark** (HWM) is the highest price \\( P_t \\) (or highest cumulative returns) a fund has achieved in the past.

$$
HWM_t = \max_{s \leq t} P_s
$$

- **Drawdown** (DD) is the cumulative loss since losses stared, it is the amount that has been lost since the peak (i.e. the HWM). If the fund is currently at its peak, then the drawdown is zero, otherwise it's a positive number.

$$
DD_t = \big[ (HWM_t - P_t) / HWM_t \big]^+
$$

- **Maximum Drawdown** (MDD) over the past time period is

$$
MDD_T = \max_{t \leq T} DD_t
$$

