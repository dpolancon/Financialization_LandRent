# SHT land-rent review: citation crosswalk

Use `sht_landrent_sources.bib` as the active BibTeX file. The map below translates the author-year references currently used in the draft into stable LaTeX citation keys.

| Current draft reference | BibTeX key | Parenthetical LaTeX | Textual LaTeX | Source file / status |
|---|---|---|---|---|
| Hirano, Jinnai, and Toda (2024) | `hiranoJinnaiToda2024Leverage` | `\citep{hiranoJinnaiToda2024Leverage}` | `\citet{hiranoJinnaiToda2024Leverage}` | `HIRANO_ETAL_2024.pdf`; arXiv manuscript |
| Hirano and Stiglitz (2022a) | `hiranoStiglitz2022LandSpeculation` | `\citep{hiranoStiglitz2022LandSpeculation}` | `\citet{hiranoStiglitz2022LandSpeculation}` | `HIRANO_STIGLITZ_2022a.pdf`; NBER WP 29745 |
| Hirano and Stiglitz (2022b) | `hiranoStiglitz2022WobblyEconomy` | `\citep{hiranoStiglitz2022WobblyEconomy}` | `\citet{hiranoStiglitz2022WobblyEconomy}` | `HIRANO_STIGLITZ_2022b.pdf`; NBER WP 29806 |
| Hirano and Stiglitz (2024) | `hiranoStiglitz2024CreditLandGrowth` | `\citep{hiranoStiglitz2024CreditLandGrowth}` | `\citet{hiranoStiglitz2024CreditLandGrowth}` | `HIRANO_STIGLITZ_2021.pdf` / NBER WP 32479; file name is misleading, source year is 2024 |
| Hirano and Stiglitz (2025a) | `hiranoStiglitz2025HenryGeorge` | `\citep{hiranoStiglitz2025HenryGeorge}` | `\citet{hiranoStiglitz2025HenryGeorge}` | `HIRANO_STIGLITZ_2025a.pdf`; published article |
| Hirano and Stiglitz (2025b) | `hiranoStiglitz2025GrowthFluctuationsLandSpeculation` | `\citep{hiranoStiglitz2025GrowthFluctuationsLandSpeculation}` | `\citet{hiranoStiglitz2025GrowthFluctuationsLandSpeculation}` | `HIRANO_STIGLITZ_2025b.pdf`; NBER WP 33589 |
| Hirano and Stiglitz (2025c) | `hiranoStiglitz2025LowInterestPolicy` | `\citep{hiranoStiglitz2025LowInterestPolicy}` | `\citet{hiranoStiglitz2025LowInterestPolicy}` | `HIRANO_STIGLITZ_2025c.pdf`; local manuscript version + arXiv 2503.23552 |
| Hirano and Toda (2025a) | `hiranoToda2025LandInfiniteDebtRollover` | `\citep{hiranoToda2025LandInfiniteDebtRollover}` | `\citet{hiranoToda2025LandInfiniteDebtRollover}` | `HIRANO_ETAL_2025a.pdf`; arXiv manuscript |
| Hirano and Toda (2025b) | `hiranoToda2025UnbalancedGrowth` | `\citep{hiranoToda2025UnbalancedGrowth}` | `\citet{hiranoToda2025UnbalancedGrowth}` | `HIRANO_ETAL_2025b.pdf`; CIGS WP 25-011E |
| Hirano and Toda (2026) | `hiranoToda2026LandGversusR` | `\citep{hiranoToda2026LandGversusR}` | `\citet{hiranoToda2026LandGversusR}` | `HIRANO_ETAL_2026.pdf`; CIGS WP 26-002E |
| Stiglitz (2015a) | `stiglitz2015WealthResidual` | `\citep{stiglitz2015WealthResidual}` | `\citet{stiglitz2015WealthResidual}` | `STIGLITZ_2015a.pdf`; NBER WP 21189 |
| Stiglitz (2015b) | `stiglitz2015LandCredit` | `\citep{stiglitz2015LandCredit}` | `\citet{stiglitz2015LandCredit}` | `STIGLITZ_2015b.pdf`; NBER WP 21192 |
| Stiglitz (2015c) | `stiglitz2015MeasurementWealth` | `\citep{stiglitz2015MeasurementWealth}` | `\citet{stiglitz2015MeasurementWealth}` | `STIGLITZ_2015c.pdf`; NBER WP 21327 |
| Toda (2025) | `toda2025LandBubbles` | `\citep{toda2025LandBubbles}` | `\citet{toda2025LandBubbles}` | `AKIRATODA_2025.pdf`; published article |

## Page-specific citation patterns for implementation

Use page locators only in the `.tex`, not in the `.bib`. Examples:

- `(Stiglitz, 2015c, pp. 1, 2, 4, 11; Stiglitz, 2015a, pp. 10, 11, 28)` → `\citep[pp.~1, 2, 4, 11]{stiglitz2015MeasurementWealth}; \citep[pp.~10, 11, 28]{stiglitz2015WealthResidual}`.
- `(Hirano and Stiglitz, 2022a, pp. 7, 24, 46, 47; Hirano and Stiglitz, 2022b, pp. 1, 2, 10)` → `\citep[pp.~7, 24, 46, 47]{hiranoStiglitz2022LandSpeculation}; \citep[pp.~1, 2, 10]{hiranoStiglitz2022WobblyEconomy}`.
- `(Hirano and Toda, 2025b, pp. 1, 3, 4, 13)` → `\citep[pp.~1, 3, 4, 13]{hiranoToda2025UnbalancedGrowth}`.
- `(Toda, 2025, pp. 1, 2, 3)` → `\citep[pp.~1--3]{toda2025LandBubbles}`.
- `(Hirano and Stiglitz, 2024, pp. 1, 15, 33, 38)` → `\citep[pp.~1, 15, 33, 38]{hiranoStiglitz2024CreditLandGrowth}`.
- `(Hirano, Jinnai, and Toda, 2024, pp. 2, 3, 9)` → `\citep[pp.~2, 3, 9]{hiranoJinnaiToda2024Leverage}`.
- `(Hirano and Toda, 2025a, pp. 1, 2, 16, 17)` → `\citep[pp.~1, 2, 16, 17]{hiranoToda2025LandInfiniteDebtRollover}`.
- `(Hirano and Toda, 2026, p. 4)` → `\citep[p.~4]{hiranoToda2026LandGversusR}`.
