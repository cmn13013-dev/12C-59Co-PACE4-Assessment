# 12C-59Co-PACE4-Assessment
This repository provides supplementary materials for the PACE4 consistency assessment for the ¹²C + ⁵⁹Co system at E_lab = 60–80 MeV.
# Assessment of PACE4 against CF-Dominated Channels in ¹²C + ⁵⁹Co

**Manuscript:** Assessment of PACE4 against CF-Dominated Channels in ¹²C + ⁵⁹Co:
Implications for Complete/Incomplete Fusion Discrimination at 60–80 MeV

**Authors:** Ntumba Lobo, Ashok Kumar Chaubey, Edmond Phuku Phuati,
Jérémie Muswema, Patrick Dedetemo Kimilita, Emmanuel Ndiadia Kandolo

**Journal:** Nuclear Physics A (Manuscript No. NPA-D-26-00135)

---

## Overview

This repository provides supplementary materials for the PACE4 consistency
assessment for the ¹²C + ⁵⁹Co system at E_lab = 60–80 MeV.

## Key Results

- R = σ_PACE4 / ΣσCF,LB ranges from 1.92 to 3.57 (mean 2.64)
- Consistent with Hauser-Feshbach expectation R ~ 3–4
- ⁶⁶Ga (αn) channel rises ~7.6× from 60 to 80 MeV (non-CF signature)
- EXFOR entry D6173 contains only α-emission channels (CF channels absent)
- Citation correction: Agarwal et al. (2002) is Phys. Rev. C 65, 034604 (not 034605)

## Data Sources

### Primary experimental data
- A. Agarwal, I.A. Rizvi and A.K. Chaubey, Phys. Rev. C 65, 034604 (2002)
- Values digitised from Figs. 2(a,b) using WebPlotDigitizer
- Systematic digitisation uncertainty: 30% (correlated, log-scale)

### EXFOR data
- F.K. Amanuel et al., Eur. Phys. J. A 47, 156 (2011)
- EXFOR entry: D6173 (subentries D6173.009–.012)
- Access: https://www-nds.iaea.org/exfor
- Note: D6173 contains ONLY α-emission channels; CF channels are absent

## Computational Code

**PACE4** (Complete Fusion only)
- Reference: A. Gavron, Phys. Rev. C 21, 230 (1980)
- Model: Bass fusion barrier, Perey-Perey optical model
- Level density: Gilbert-Cameron, a = A/9 MeV⁻¹ (A = 71)
- Cascades: 100,000 Monte Carlo per energy point
- System: ¹²C + ⁵⁹Co → ⁷¹As*

## PACE4 Parameters

| Parameter | Value |
|-----------|-------|
| Fusion model | Bass barrier |
| Optical model | Perey-Perey |
| Level density | Gilbert-Cameron |
| a (level density) | A/9 MeV⁻¹ = 7.89 MeV⁻¹ |
| Monte Carlo cascades | 100,000 |
| σ_CN (60–80 MeV) | ~1250 mb (plateau) |

## Data Table (Table 1 of manuscript)

| E_lab (MeV) | σ(p3n) ⁶⁷Ge (mb) | σ(2p2n) ⁶⁷Ga (mb) | ΣσCF,LB (mb) | PACE4 σCN (mb) | R |
|-------------|-------------------|-------------------|--------------|-----------------|-----|
| 60 | 200 ± 60 | 200 ± 60 | 400 ± 120 | 1248 | 3.12 |
| 65 | 300 ± 90 | 300 ± 90 | 600 ± 180 | 1253 | 2.09 |
| 70 | 350 ± 105 | 300 ± 90 | 650 ± 195 | 1251 | 1.92 |
| 75 | 200 ± 60 | 300 ± 90 | 500 ± 150 | 1250 | 2.50 |
| 80 | 150 ± 45 | 200 ± 60 | 350 ± 105 | 1248 | 3.57 |

Uncertainties: 30% systematic (correlated digitisation error, not quadrature).

## Methodological Notes

1. CF lower bound constructed from p3n (⁶⁷Ge) and 2p2n (⁶⁷Ga) channels only
2. These channels confirmed CF-dominated by independent cascade analyses [9,10,18]
3. Uncertainty propagated linearly (not in quadrature) — appropriate for correlated log-scale digitisation
4. EXFOR values preferred over digitised values for αn channel at 75–80 MeV

## Citation Correction

Agarwal et al. (2002) is **Phys. Rev. C 65, 034604**.
The citation "034605" appearing in downstream literature (e.g. Amanuel et al. 2011) is a
propagating error. Page 034605 of PRC vol. 65 is an unrelated paper (Raduta et al., fission dynamics).

## Contact

ntumbalobo1988@gmail.com | cmn13013@nitech.jp

## License

Creative Commons Attribution 4.0 (CC-BY-4.0)
