# Planck Sphere Cosmology (PSC)
## プランク球体宇宙論

**Author:** Tsutomu Ishii（石井 努）  
**Affiliation:** Independent Researcher, Nagano, Japan  
**Date:** June 16, 2026  
**Status:** Research Note / Preprint  
**Related Repositories:** VGT, OFT  

※ In this repository, the Planck Sphere is treated mathematically as a sphere since 4π (the solid angle of a sphere) appears in the core equation. However, whether the initial state and the present universe are truly spherical remains observationally unconfirmed. For details, see the notes in the development document and Axiom 3 in the formulation document.

本リポジトリにおいてプランク球体を数学的計算上4πという球面の数値が確認されることから球体として扱う。ただし初期状態および現在の宇宙が真に球体であるか観測的に未確定である。詳細はdevelopment文書の注記およびformulation文書の公理3を参照されたい。

---

## Title / タイトル

**Planck Sphere Theory: The Minimal Unit of the Universe and Its Unified Description of Fundamental Physics**

*From Fundamental Constants to Baryon Asymmetry, Cosmological Constant, and Dark Sector*

**プランク球体理論：宇宙の最小単位と基本物理学の統一的記述**

*基本定数からバリオン非対称性・宇宙定数・ダーク系まで*

---

## Abstract / 要旨

This paper proposes the Planck Sphere — a sphere of radius equal to the Planck length ℓP — as the minimal geometric unit of the universe. Starting from the core identity:

$$A_P \times c^3 = 4\pi \times \hbar \times G$$

we demonstrate that the fundamental constants of nature (c, G, ℏ) are mutually determined through the Planck sphere's surface area AP and the geometric factor 4π. From this single relation, we derive the Planck length, time, energy, mass, and temperature, as well as the information content of the Planck sphere (I = π bits). Extended equivalences incorporating electromagnetic (ε₀, qP) and thermal (kB, TP) quantities are shown to follow naturally.

We further propose that the cosmological constant Λ is not a true constant but varies as Λ(t) ~ 1/R(t)², consistent with recent DESI 2025 observations suggesting dynamic dark energy. The baryon asymmetry parameter η is estimated as:

$$\eta = \frac{\alpha^3}{16\pi^2} \approx 6.1 \times 10^{-10}$$

within 1.7% of the observed value, where the factor 16 = 2⁴ is identified with the Dirac spinor structure of 4-dimensional spacetime. Separation of the four fundamental forces through the running coupling constant α is outlined.

This work explores the Planck Sphere as a candidate for the minimal geometric unit of the root field Ψ₀ in Origin Field Theory (OFT), and attempts to present a verifiable framework pointing toward a unified description of both OFT and Virtual Gravity Theory (VGT).

---

## 日本語要旨

本論文はプランク長ℓPを半径とする球体「プランク球体」を宇宙の幾何学的最小単位として提案する。核心等式：

$$A_P \times c^3 = 4\pi \times \hbar \times G$$

から出発し、自然界の基本定数（c・G・ℏ）がプランク球体の表面積APと幾何学的係数4πを媒介として相互規定されることを示す。この一つの関係式からプランク長・時間・エネルギー・質量・温度およびプランク球体の情報量（I＝πビット）を導出する。電磁気（ε₀・qP）および熱統計（kB・TP）量を含む拡張等価式も自然に導かれる。

宇宙定数Λは真の定数ではなくΛ(t)～1/R(t)²として変化するという描像を提案し、これはDESI2025の観測と整合する。バリオン非対称性パラメータηを：

$$\eta = \frac{\alpha^3}{16\pi^2} \approx 6.1 \times 10^{-10}$$

と推定し、観測値との誤差1.7%以内の一致を示す。ここで係数16＝2⁴は4次元時空のディラックスピノル構造と同定される。結合定数αの変化による四力の分離過程も概説する。

本論文はプランク球体をOFT（根源場理論）の根源場Ψ₀の幾何学的最小単位の候補として探索し、OFTおよびVGT（仮想重力理論）の統一的記述に向けた検証可能な枠組みの提示を試みる。

---

## Core Equation / 核心等式

$$\boxed{A_P \times c^3 = 4\pi \times \hbar \times G = 4\pi \times E_P \times t_P \times G = \frac{q_P^2 \times G}{\varepsilon_0 \times c}}$$

---

## Key Results / 主要結果

| Result | Value | Status |
|--------|-------|--------|
| Information content of Planck Sphere | I = π bits | Derived |
| Baryon asymmetry η | ≈ 6.1 × 10⁻¹⁰ (1.7% from observed) | Proposed |
| Cosmological constant | Λ(t) ~ 1/R(t)² | Proposed |
| Universe geometry | Spherical-containing (4π confirmed mathematically) | Proposed |
| Dark matter density | ρDM ~ H²/4πG | Proposed |

---

## Keywords / キーワード

Planck sphere, quantum gravity, unified field theory, baryon asymmetry, cosmological constant, dark energy, dark matter, Origin Field Theory, Virtual Gravity Theory, Planck length, information theory

プランク球体、量子重力、統一場理論、バリオン非対称性、宇宙定数、ダークエネルギー、ダークマター、起源場理論、仮想重力理論、プランク長、情報理論

---

## Files / ファイル構成

| File | Content |
|------|---------|
| `planck_sphere_overview_20260616.md` | 概念的入門・総合案内ノート |
| `planck_sphere_development_20260616.md` | 思考の経過と発展（12段階） |
| `planck_sphere_equations_20260616.md` | 式の全体整理・宇宙論的シナリオ |
| `planck_sphere_formulation_20260616.md` | 数学的定式化・定理・命題 |

---

## Relation to VGT/OFT / VGT・OFTとの関係

```
根源場Ψ₀（OFT：根源場理論）
　↓幾何学的最小単位として
プランク球体（PSC：本論文）
　↓展開・分岐
重力‖電磁力（VGT：仮想重力理論）
　↓
現在の宇宙
```

---

## Disclaimer / 免責事項

This work is a research note at a conceptual and semi-quantitative stage. All results are proposals requiring further mathematical formalization and observational verification.

本論文は概念的・半定量的段階の研究ノートである。全ての結果はさらなる数学的定式化および観測的検証を必要とする提案である。

---

## AI Assistance / AI使用について

This research was conducted through collaborative dialogue with Claude (Anthropic, Claude Sonnet 4.6) as the sole AI tool. All core ideas, intuitions, and theoretical directions were proposed by the author. Claude was used as an interactive research assistant for calculation, formalization, and documentation. This methodology follows the author's established ICC Method (Interactive Collaborative Creation), previously applied in the development of VGT and OFT.

本研究はAnthropicのClaude（Claude Sonnet 4.6）のみをAIツールとして使用した対話的研究として実施された。核心的アイデア・直感・理論的方向性は全て著者によるものであり、Claudeは計算・定式化・文書化のための対話的研究アシスタントとして使用された。本手法は著者がVGT・OFTの開発において確立したICCメソッド（Interactive Collaborative Creation）に基づく。

---

## Citation / 引用

Ishii, T. (2026). *Planck Sphere Theory: The Minimal Unit of the Universe and Its Unified Description of Fundamental Physics*. GitHub: PSC Repository. Zenodo. DOI: [pending]

---

*© 2026 Tsutomu Ishii. This work is licensed under CC BY 4.0.*
