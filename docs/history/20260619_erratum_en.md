# Erratum: Correction to the Baryon Asymmetry Formula

**Author:** Tsutomu Ishii, Independent Researcher, Nagano, Japan
**Issued:** June 19, 2026
**Applies to:** Planck Sphere Cosmology (PSC), first version (June 16, 2026; Zenodo DOI: 10.5281/zenodo.20736648)

## 1. Summary

In the first version of PSC, the final formula for the baryon asymmetry parameter η contained a typographical error in the equation. This note corrects it. The numerical reasoning used in the derivation (α³/4π² is about 16 times the observed value, hence divide by 16) was correct; the only error was in the denominator coefficient when writing the "divide by 16" operation as an equation.

## 2. The Error

As published in the first version, evaluating the expression η = α³/(16π²) as written gives approximately 2.46×10⁻⁹, which is about 4 times the observed value of 6×10⁻¹⁰ (a discrepancy of roughly 300%), and does not equal the stated "6.1×10⁻¹⁰".

## 3. The Correct Formula

The derivation text states: "the first candidate α³/4π² ≈ 9.8×10⁻⁹ is about 16 times larger than the observed value, so we divide by 16." Reflecting this correctly in the equation, the denominator becomes 4π² multiplied by a further factor of 16, i.e. 64π²:

$$\eta = \frac{\alpha^3}{64\pi^2} \approx 6.15\times10^{-10}$$

**Verification:**

| Formula | Value | Discrepancy vs. observed (6.1×10⁻¹⁰) |
|---------|-------|----------------------------------------|
| α³/(4π²) (first candidate) | 9.84×10⁻⁹ | — |
| α³/(16π²) (published error) | 2.46×10⁻⁹ | ~303% |
| α³/(64π²) (corrected) | 6.15×10⁻¹⁰ | 0.85% |

In other words, the first version's conclusion — agreement with the observed value — was correct, but the equation expressing it was wrong. The corrected formula α³/(64π²) agrees with observation to within 0.85%.

## 4. On the Coefficient 64 (Important Caveat)

The first version interpreted the denominator coefficient as "16 = 2⁴ = Dirac structure (16 components of a 4×4 matrix)." However, the correct coefficient is 64, not 16. The original "correspondence with Dirac structure" interpretation therefore does not hold as stated.

The number 64 admits several decompositions:

- 64 = 4 × 16 (the coefficient 4 of the first candidate, times the factor 16 = 2⁴ needed to match observation)
- 64 = 2⁶
- 64 = 4³

All are mathematically valid expressions, but which decomposition is physically required remains unresolved. Crucially, the coefficient 64 was obtained by working backward from the observed value, not derived from first principles.

Accordingly, this corrected version positions η = α³/(64π²) as an empirical relation that agrees well with observation, and leaves the physical necessity of the coefficient 64 as future work. This is consistent with the first version already listing "the theoretical necessity of 16" among its open problems.

## 5. Affected Locations

In all of the following, η = α³/(16π²) is corrected to η = α³/(64π²), and the discussion of the coefficient's interpretation is revised as above:

- README.md (Abstract, Key Results table)
- planck_sphere_formulation_20260616.md / _ja (Section 6)
- planck_sphere_equations_20260616.md / _ja
- planck_sphere_overview_20260616.md / _ja
- planck_sphere_readme_ja_20260616.md
- The published Zenodo record (corrected version registered as a new version)

The stated discrepancy of "~1.7%" should also be updated: based on the correct formula and an observed value of 6.1×10⁻¹⁰, it is ~0.85%.

This erratum is preserved alongside the first version for transparency. As a matter of scientific record, it makes the error and the correction explicit.

June 19, 2026. Tsutomu Ishii, Independent Researcher, Nagano, Japan.
