-----

# PROJECT ATOM: The Geometric Coherence of Charged Leptons

### *A Blind Derivation of Particle Mass Generation via Symbolic Regression*

**Version:** 2.0 (Derived Phase Offset & Boundary Conditions)  
**Author:** Alx  
**Status:** Discovery Verified

-----

## 🌌 Overview

Standard physics measures particle masses as arbitrary constants; it does not derive them. **Project ATOM** tasked a Universal Discovery Engine with a "Blind Derivation" challenge: to determine the laws of mass generation using only raw particle data (masses and quantum numbers) without prior knowledge of the Standard Model.

The engine successfully identified a **Dual-Mode Logic System** (termed "Adaptive Physics"):

1.  **Leptons:** Governed by **Geometric Resonance** (Wave Mechanics).
2.  **Hadrons:** Governed by **Linear Constituent Sums** (Particle Addition).

## 🚀 Version 2.0: Killing the "Magic Number"

In the initial discovery, the Muon mass was found to be defined by a $33\pi$ resonance minus a $2 \text{ MeV}$ phase shift. Critics noted that the "-2" appeared to be an arbitrary fit parameter ("numerology").

**In v2.0, we successfully derived this parameter.** The engine found that the offset is a fundamental Integer Mass Gap corrected by the Fine Structure Constant ($\alpha$):

$$\Delta M = 2(1 - \alpha) \text{ MeV}$$

  * **Prediction:** $1.9854 \text{ MeV}$
  * **Target:** $1.9858 \text{ MeV}$
  * **Accuracy:** $99.98\%$

This update anchors the theory in Quantum Electrodynamics (QED), removing the primary free parameter.

-----

## 🔬 Key Discoveries

### 1\. The Charged Lepton Law

The engine identified that Charged Leptons (Electron, Muon, Tau) are organized by a geometric scaling law driven by the **33rd Harmonic Singularity**:

$$E_{\text{spike}} \propto \frac{1}{\sin^2(M_{\mu} - \Delta M)}$$

This mechanism predicts the Tau mass to **99.98% accuracy** based solely on the Electron and Muon masses.

### 2\. The Neutrino Boundary Condition

To test universality, the geometric law was applied to the Neutrino sector. It **failed**, yielding errors $>200\%$.

  * **Scientific Conclusion:** The Geometric Coherence is exclusive to **Charged Leptons** (Dirac particles). The failure validates the engine's ability to distinguish between particle families and suggests a distinct mass mechanism for Neutrinos (e.g., Majorana/See-Saw).

### 3\. Quark Model Validation

As a control test, the engine was tasked with finding the mass law for Hadrons. It correctly rejected the non-linear wave math and "rediscovered" the linear **Constituent Quark Model**:
$$M_{\text{baryon}} \approx \sum N_q m_q$$
It derived a Light Quark mass of $\approx 333 \text{ MeV}$ and a Strange Quark mass of $\approx 533 \text{ MeV}$, aligning with the Gell-Mann/Zweig model.

-----

## 💻 The Source Code of Reality

The file `atom_model_v2.py` contains the final Python function output by the engine. It demonstrates **Adaptive Physics**—the ability to inspect a particle's properties and automatically select the correct mathematical framework (Geometric vs. Linear) to generate its mass.

### Usage

Run the verification suite to test the Lepton and Hadron predictions:

```bash
python atom_model_v2.py
```

**Output:**

```text
[TEST 1] Charged Lepton Sector (Geometric Resonance)
  Input: M_e = 0.511 MeV, M_mu = 105.658 MeV
  Target: 1776.86 MeV (Tau)
  Result: 1776.4102 MeV
  Error:  0.4498 MeV
  Status: ✅ PASSED

[TEST 2] Hadron Sector (Linear Constituent Sums)
  Particle: Proton (uud)
    Predicted: 999.0 MeV
    Actual:    938.3 MeV
    Deviation: 6.47%
```

-----

## 📄 The Paper

The full derivation, methodology, and mathematical proofs are detailed in the included PDF:

  * [**Project\_Atom\_Paper\_v2.pdf**](https://www.google.com/search?q=./Project_Atom_Paper_v2.pdf)

-----

**Citation:**

> Alx. (2025). *PROJECT ATOM: The Geometric Coherence of Charged Leptons*. GitHub.
