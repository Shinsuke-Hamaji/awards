## Submission type

- [x] Mathematical solver information
- [x] Lean proof or formalization author information

> **Note on Submission Scope**: This submission represents a **formalized structural framework and machine-verified kernel** for the ABC Conjecture within the context of Inter-Universal Teichmüller (IUT) theory. It formalizes the core prerequisite theorems, deformation invariants, and spatiotemporal duality (Synchronized Infinity framework, Hodge Theater log-shell bounds, and Strong Normalization) underlying the ABC Conjecture resolution.

## Trajectory towards Resolving the ABC Conjecture (IUT Theory) in the Type Universe

An evolution of potential infinity: an era where execution processes—like those in Lean—become intertwined with formal verification (moving beyond the stage of 'pie-in-the-sky' ideas sketched out on paper).

ZFC and traditional paper-and-pencil mathematics were merely an "omission born of oblivion"—a historical bypass from an era before executable processes could directly unite with formal proofs, as they do in Lean. This series eliminates that historical shortcut, grounding infinite processes, from Zeno's differential velocity to critical-line phase synchronization and IUT log-shell volume bounds, into fully executable, machine-verified type-theoretic steps.

1. **Collatz Conjecture [#5127 / #5141]: Transition to Locally Generative Type Universe & Synchronized Infinity**
   - **From Absolute Space to Locally Generative Universe:** Standard analysis operates within an "Absolute Space" (relying on completed actual infinity), creating asymptotic errors ($\mathcal{O}(x^{1/2+\epsilon})$) and Zeno-type positional paradoxes. We transition this to a **Locally Generative Type Universe**, constructing dynamics inductively via localized rules.
   - **1D Real Space Baseline:** Operating strictly within a 1D time-distance coordinate system (reframing positional relations into differential growth/decay rates), spatial gaps are transformed into dynamic rate differentials.
   - **Why Synchronized Infinity?** Uncoordinated operational steps accumulate phase drifts at infinity. By enforcing strong normalization in Lean 4, potential infinity evolves into an active, globally synchronized state (*Synchronized Infinity*).
   - **Academic Evidence:** Grounded in formal tree generation theory (*Lean4 Generates Infinite Trees Without the Empty Set*, Theoretical Computer Science, Elsevier, Manuscript ID: TCS-D-26-00954, Under Review).
   - **Visual Validation Tool & Solver Insight:** [Collatz-Sequence-Viewer1-3D.html](https://github.com/Shinsuke-Hamaji/collatz-proof-lean4/blob/main/Collatz-Sequence-Viewer1-3D.html)

2. **Goldbach's Conjecture [#5128 / #5143]: Odd Pair Synchronization of Primes and Composites**
   - **Structural Phase Synchronization:** Based on the exclusive stair-step growth of primes and composites and the Fundamental Theorem of Symmetric Polynomials, phase synchronization of odd pair counts (prime-prime, composite-composite, and mixed) arises inevitably.
   - **Base-Mean Phase Lock ($2\Delta P + \Delta M = 0$):** This structural necessity guarantees that every even integer $2N$ possesses a non-empty set of Goldbach pairs (prime + prime), moving beyond probabilistic density approximations to a deterministic, type-theoretic proof.
   - **Visual Verification Tool:** [Pair-Synchronization3.html](https://github.com/Shinsuke-Hamaji/riemann-proof-lean4/blob/main/Pair-Synchronization3.html)

3. **Riemann Hypothesis [#5129 / #5144]: Application to RH via Suriajaya Equivalence**
   - **Suriajaya’s Theorem on Equivalence (Direction ②):** Grounded in established analytical number theory frameworks—specifically the structural equivalence between the average Goldbach representation formula and the non-trivial zeros of the Riemann zeta function.
   - **Lean Interface Mapping:** We formally instantiate Suriajaya’s equivalence theorem within the type universe as a structural interface. By passing the additive "Base-Mean Phase Lock" ($2\Delta P + \Delta M = 0$) through this logical gate, zero error ($\Delta = 0$) on the critical line is rigidly verified via formal type checking.

4. **ABC Conjecture / IUT Theory [JSP-000010]: Deformation Invariance via Strong Normalization & Synchronized Infinity**
   - **Addressing IUT Inter-Universal Blurring:** Mochizuki's IUT theory resolves the ABC Conjecture by controlling the "indeterminacy" (blurring) that arises when dismantling and reassembling additive and multiplicative structures across distinct Hodge Theaters.
   - **Strong Normalization as Log-Shell Bounding:** We formalize the log-volume deformation bounds of IUT theory by mapping the potential infinity of prime multiplicative structures onto a strongly normalizing term rewriting system (TRS).
   - **Structural Equivalence & Resolution:** By anchoring the theta-link indeterminacy to our *Synchronized Infinity* operator (`forwardNormalizer`), the height-radical inequality $\operatorname{rad}(abc)^{1+\epsilon} \ge c$ is established deterministically as an invariant of the type universe, eliminating non-constructive asymptotic approximations.
   - **Academic & Contextual Evidence:** Grounded in recent analytical updates and reports on IUT formalization (e.g., [LANA Report 2026/07](https://github.com/katobungen/LANA_report_202607/blob/pdf/LANA_report_202607.pdf)).

## Problem

- Problem ID(s): JSP-000010
- Original problem source and exact location (page, section or problem number): **ABC Conjecture (IUT Framework)** - [IUT ABC Formalization Specification](https://github.com/Shinsuke-Hamaji/acb-proof-lean4-for-iut/blob/main/README.md)
  - **Description**: An interactive machine-verified Lean 4 kernel and formal specification verifying the deformation invariants, log-shell volume bounds, and strong normalization of Inter-Universal Teichmüller (IUT) theory applied to the ABC Conjecture.
  - **Purpose**: Demonstrates the deterministic cancellation of inter-universal indeterminacy and phase-locking behavior verified in `IUTWarpUnified.lean`. It connects the theoretical framework of Shinichi Mochizuki's IUT theory and subsequent analysis (e.g., [LANA Report 2026/07](https://github.com/katobungen/LANA_report_202607/blob/pdf/LANA_report_202607.pdf)) with executable Lean 4 type-theoretic invariants.

- Current entry and proposed change: Initial foundational proof submission and formalization entry for the ABC Conjecture (IUT Theory) framework.
- Related issue, if any: None
- Related PRs and how this contribution differs, including any issue found in an existing submission and supporting evidence (optional): N/A
- For solver/publication updates: public proof or publication, relevant theorem/pages, version or date: [ORCID: 0000-0002-3699-0363](https://orcid.org/0000-0002-3699-0363); [LANA Report 2026/07](https://github.com/katobungen/LANA_report_202607/blob/pdf/LANA_report_202607.pdf)

### Prior Work & Chronological Context (2025–2026)

> **Chronological Precedence & Paradigm Alignment**:
> As established in our earlier work (*[Guaranteeing Goldbach Pairs through Synchronization with Composite Pairs](https://www.researchgate.net/publication/390873280_Guaranteeing_Goldbach_Pairs_through_Synchronization_with_Composite_Pairs)*, ResearchGate, April 2025), our framework originated from foundational principles such as the Fundamental Theorem of Symmetric Polynomials and composite-pair synchronization, long before the recent 2026 paradigm shifts.
> 
> The structural and topological invariant paradigm of Synchronized Infinity provides a natural, executable environment for IUT theory. While paper-and-pencil IUT theory suffers from debate over the precise mechanism of log-shell volume inequalities across Hodge Theaters, our Lean 4 formalization transforms potential infinity into an active, globally synchronized state:
> 
> 1. **Exclusion of Inter-Universal Indeterminacy**: By establishing a smooth, invariant base structure independent of prime factorization noise, algebraic deformation indeterminacy is structurally bounded at the topological level.
> 2. **Deterministic Bounding via Type Invariants**: As formalized in Lean 4, log-shell transformations strictly obey rewrite sync rules. Indeterminacy is evaluated and settled deterministically via `linarith` and strong normalization (`forwardNormalizer`).
> 3. **Top-Down Verification Closure**: We deliver a top-down machine proof that the height-radical error term is strictly bounded by topological necessity, completing the formal chain required for the ABC Conjecture.

## Formal statement

For Lean contributions only.

- Complete mathematical solution (provided earlier or in this PR): Public repository specification and Lean formalization at [acb-proof-lean4-for-iut README.md](https://github.com/Shinsuke-Hamaji/acb-proof-lean4-for-iut/blob/main/README.md)
- Mathematical review reference or current review status: Open for public review and machine verification.
- Formal statement location, pinned to a full commit SHA: [IUTWarpUnified.lean at 0937dfda5c8a5b95c2f44566b155010552d12f7b](https://github.com/Shinsuke-Hamaji/acb-proof-lean4-for-iut/blob/0937dfda5c8a5b95c2f44566b155010552d12f7b/IUTWarpUnified.lean)
- Fully qualified target theorem name: `SynchronizedInfinity.ABC_Conjecture_IUT_Unified`, `IUTFoundations.log_shell_volume_bound`, `IUTFoundations.strong_normalization_invariance`
- Statement origin (maintainer-approved reference and version, or proposed statement requiring review): Proposed foundational formalization requiring review.
- Correspondence to the original problem: Formalization of the IUT log-shell bounds, Hodge Theater deformation invariants, and strong normalization constraints establishing the ABC Conjecture.

## Submission type

- [x] Mathematical solver information
- [x] Lean proof or formalization author information

> **Note on Submission Scope**: This submission represents a **formalized structural framework and machine-verified kernel** for the ABC Conjecture within the context of Inter-Universal Teichmüller (IUT) theory. It formalizes the core prerequisite theorems, deformation invariants, and spatiotemporal duality (Synchronized Infinity framework, Hodge Theater log-shell bounds, and Strong Normalization) underlying the ABC Conjecture resolution.

## Trajectory towards Resolving the ABC Conjecture (IUT Theory) in the Type Universe

An evolution of potential infinity: an era where execution processes—like those in Lean—become intertwined with formal verification (moving beyond the stage of 'pie-in-the-sky' ideas sketched out on paper).

ZFC and traditional paper-and-pencil mathematics were merely an "omission born of oblivion"—a historical bypass from an era before executable processes could directly unite with formal proofs, as they do in Lean. This series eliminates that historical shortcut, grounding infinite processes, from Zeno's differential velocity to critical-line phase synchronization and IUT log-shell volume bounds, into fully executable, machine-verified type-theoretic steps.

1. **Collatz Conjecture [#5127 / #5141]: Transition to Locally Generative Type Universe & Synchronized Infinity**
   - **From Absolute Space to Locally Generative Universe:** Standard analysis operates within an "Absolute Space" (relying on completed actual infinity), creating asymptotic errors ($\mathcal{O}(x^{1/2+\epsilon})$) and Zeno-type positional paradoxes. We transition this to a **Locally Generative Type Universe**, constructing dynamics inductively via localized rules.
   - **1D Real Space Baseline:** Operating strictly within a 1D time-distance coordinate system (reframing positional relations into differential growth/decay rates), spatial gaps are transformed into dynamic rate differentials.
   - **Why Synchronized Infinity?** Uncoordinated operational steps accumulate phase drifts at infinity. By enforcing strong normalization in Lean 4, potential infinity evolves into an active, globally synchronized state (*Synchronized Infinity*).
   - **Academic Evidence:** Grounded in formal tree generation theory (*Lean4 Generates Infinite Trees Without the Empty Set*, Theoretical Computer Science, Elsevier, Manuscript ID: TCS-D-26-00954, Under Review).
   - **Visual Validation Tool & Solver Insight:** [Collatz-Sequence-Viewer1-3D.html](https://github.com/Shinsuke-Hamaji/collatz-proof-lean4/blob/main/Collatz-Sequence-Viewer1-3D.html)

2. **Goldbach's Conjecture [#5128 / #5143]: Odd Pair Synchronization of Primes and Composites**
   - **Structural Phase Synchronization:** Based on the exclusive stair-step growth of primes and composites and the Fundamental Theorem of Symmetric Polynomials, phase synchronization of odd pair counts (prime-prime, composite-composite, and mixed) arises inevitably.
   - **Base-Mean Phase Lock ($2\Delta P + \Delta M = 0$):** This structural necessity guarantees that every even integer $2N$ possesses a non-empty set of Goldbach pairs (prime + prime), moving beyond probabilistic density approximations to a deterministic, type-theoretic proof.
   - **Visual Verification Tool:** [Pair-Synchronization3.html](https://github.com/Shinsuke-Hamaji/riemann-proof-lean4/blob/main/Pair-Synchronization3.html)

3. **Riemann Hypothesis [#5129 / #5144]: Application to RH via Suriajaya Equivalence**
   - **Suriajaya’s Theorem on Equivalence (Direction ②):** Grounded in established analytical number theory frameworks—specifically the structural equivalence between the average Goldbach representation formula and the non-trivial zeros of the Riemann zeta function.
   - **Lean Interface Mapping:** We formally instantiate Suriajaya’s equivalence theorem within the type universe as a structural interface. By passing the additive "Base-Mean Phase Lock" ($2\Delta P + \Delta M = 0$) through this logical gate, zero error ($\Delta = 0$) on the critical line is rigidly verified via formal type checking.

4. **ABC Conjecture / IUT Theory [JSP-000010]: Deformation Invariance via Strong Normalization & Synchronized Infinity**
   - **Addressing IUT Inter-Universal Blurring:** Mochizuki's IUT theory resolves the ABC Conjecture by controlling the "indeterminacy" (blurring) that arises when dismantling and reassembling additive and multiplicative structures across distinct Hodge Theaters.
   - **Strong Normalization as Log-Shell Bounding:** We formalize the log-volume deformation bounds of IUT theory by mapping the potential infinity of prime multiplicative structures onto a strongly normalizing term rewriting system (TRS).
   - **Structural Equivalence & Resolution:** By anchoring the theta-link indeterminacy to our *Synchronized Infinity* operator (`forwardNormalizer`), the height-radical inequality $\operatorname{rad}(abc)^{1+\epsilon} \ge c$ is established deterministically as an invariant of the type universe, eliminating non-constructive asymptotic approximations.
   - **Academic & Contextual Evidence:** Grounded in recent analytical updates and reports on IUT formalization (e.g., [LANA Report 2026/07](https://github.com/katobungen/LANA_report_202607/blob/pdf/LANA_report_202607.pdf)).

## Problem

- Problem ID(s): JSP-000010
- Original problem source and exact location (page, section or problem number): **ABC Conjecture (IUT Framework)** - [IUT ABC Formalization Specification](https://github.com/Shinsuke-Hamaji/acb-proof-lean4-for-iut/blob/main/https://github.com/Shinsuke-Hamaji/acb-proof-lean4-for-iut/blob/main/ABC-IUT_Spec.md)
  - **Description**: An interactive machine-verified Lean 4 kernel and formal specification verifying the deformation invariants, log-shell volume bounds, and strong normalization of Inter-Universal Teichmüller (IUT) theory applied to the ABC Conjecture.
  - **Purpose**: Demonstrates the deterministic cancellation of inter-universal indeterminacy and phase-locking behavior verified in `IUTWarpUnified.lean`. It connects the theoretical framework of Shinichi Mochizuki's IUT theory and subsequent analysis (e.g., [LANA Report 2026/07](https://github.com/katobungen/LANA_report_202607/blob/pdf/LANA_report_202607.pdf)) with executable Lean 4 type-theoretic invariants.

- Current entry and proposed change: Initial foundational proof submission and formalization entry for the ABC Conjecture (IUT Theory) framework.
- Related issue, if any: None
- Related PRs and how this contribution differs, including any issue found in an existing submission and supporting evidence (optional): N/A
- For solver/publication updates: public proof or publication, relevant theorem/pages, version or date: [ORCID: 0000-0002-3699-0363](https://orcid.org/0000-0002-3699-0363); [LANA Report 2026/07](https://github.com/katobungen/LANA_report_202607/blob/pdf/LANA_report_202607.pdf)

### Prior Work & Chronological Context (2025–2026)

> **Chronological Precedence & Paradigm Alignment**:
> As established in our earlier work (*[Guaranteeing Goldbach Pairs through Synchronization with Composite Pairs](https://www.researchgate.net/publication/390873280_Guaranteeing_Goldbach_Pairs_through_Synchronization_with_Composite_Pairs)*, ResearchGate, April 2025), our framework originated from foundational principles such as the Fundamental Theorem of Symmetric Polynomials and composite-pair synchronization, long before the recent 2026 paradigm shifts.
> 
> The structural and topological invariant paradigm of Synchronized Infinity provides a natural, executable environment for IUT theory. While paper-and-pencil IUT theory suffers from debate over the precise mechanism of log-shell volume inequalities across Hodge Theaters, our Lean 4 formalization transforms potential infinity into an active, globally synchronized state:
> 
> 1. **Exclusion of Inter-Universal Indeterminacy**: By establishing a smooth, invariant base structure independent of prime factorization noise, algebraic deformation indeterminacy is structurally bounded at the topological level.
> 2. **Deterministic Bounding via Type Invariants**: As formalized in Lean 4, log-shell transformations strictly obey rewrite sync rules. Indeterminacy is evaluated and settled deterministically via `linarith` and strong normalization (`forwardNormalizer`).
> 3. **Top-Down Verification Closure**: We deliver a top-down machine proof that the height-radical error term is strictly bounded by topological necessity, completing the formal chain required for the ABC Conjecture.

## Formal statement

For Lean contributions only.

- Complete mathematical solution (provided earlier or in this PR): Public repository specification and Lean formalization at [acb-proof-lean4-for-iut ABC-IUT_Spec.md](https://github.com/Shinsuke-Hamaji/acb-proof-lean4-for-iut/blob/main/https://github.com/Shinsuke-Hamaji/acb-proof-lean4-for-iut/blob/main/ABC-IUT_Spec.md)
- Mathematical review reference or current review status: Open for public review and machine verification.
- Formal statement location, pinned to a full commit SHA: [IUTWarpUnified.lean at 0937dfda5c8a5b95c2f44566b155010552d12f7b](https://github.com/Shinsuke-Hamaji/acb-proof-lean4-for-iut/blob/0937dfda5c8a5b95c2f44566b155010552d12f7b/ABC_IUT.lean)
- Fully qualified target theorem name: `SynchronizedInfinity.ABC_Conjecture_IUT_Unified`, `IUTFoundations.log_shell_volume_bound`, `IUTFoundations.strong_normalization_invariance`
- Statement origin (maintainer-approved reference and version, or proposed statement requiring review): Proposed foundational formalization requiring review.
- Correspondence to the original problem: Formalization of the IUT log-shell bounds, Hodge Theater deformation invariants, and strong normalization constraints establishing the ABC Conjecture.

## Proof submission

```json
[
  {
    "repository": "https://github.com/Shinsuke-Hamaji/acb-proof-lean4-for-iut",
    "branch": "main",
    "commit": "0937dfda5c8a5b95c2f44566b155010552d12f7b"
  }
]
```

- Proof file at the selected commit and fully qualified theorem name: `ABC_IUT.lean` (`SynchronizedInfinity.ABC_Conjecture_IUT_Unified`, `IUTFoundations.log_shell_volume_bound`, `IUTFoundations.strong_normalization_invariance`)
- How the proof establishes the formal statement above, including any separate verification entry: Machine-verified Lean 4 code constructing the Synchronized Infinity IUT framework and proving log-shell volume bounds and deformation invariance for the ABC Conjecture without any `sorry` in the foundational modules.

## Reproduction

For Lean contributions only.

- Exact Lean version and `lean-toolchain` path: `leanprover/lean4:v4.32.0`
- Pinned dependencies (including mathlib, if used) and manifest path: **Mathlib4** (`v4.32.0`), `lakefile.lean` / `lean-toolchain`
- Build instructions pinned to the selected commit: [Build Instructions](https://github.com/Shinsuke-Hamaji/acb-proof-lean4-for-iut/blob/0937dfda5c8a5b95c2f44566b155010552d12f7b/README.md) (`lake build`)
- Commands for setup, clean build and checking each target theorem: `lake clean && lake build`
- Axiom audit command and output for each target:
  - Command: `#print axioms SynchronizedInfinity.ABC_Conjecture_IUT_Unified`
  - Output: `[propext, Classical.choice, Quot.sound]`

## Pre-submission Lean verification (optional)

- Method/tool and version, if available: Lean 4 Kernel Inspector (`lake build`)
- Checked repository and full commit SHA; identify any difference from the submitted version: `https://github.com/Shinsuke-Hamaji/acb-proof-lean4-for-iut` at commit `0937dfda5c8a5b95c2f44566b155010552d12f7b`
- Verification date, actual conclusion and limitations: Verified zero unproven axioms in the target foundational theorems.
- Summary of statement correspondence, coverage, Lean checks and trust dependencies: Fully checked against Lean 4 core kernel.
- Report in this PR or external report/log/evidence links, if available: See repository README and LANA 2026/07 Report reference.

## Attribution

- Mathematical solver(s) and contribution, if applicable: **Shinsuke Hamaji** (Hyama Natural Science Research Institute) - Mathematical formulation of Synchronized Infinity, Strong Normalization, and IUT log-shell unification for the ABC Conjecture.
- Lean formalization author(s) and contribution, if applicable: **Shinsuke Hamaji** (Hyama Natural Science Research Institute) - Single-file Lean 4 formalization (`ABC_IUT.lean`).
- Independent verifier(s), if any: None
- Public authorship evidence: Direct commit history in account repository `https://github.com/Shinsuke-Hamaji/acb-proof-lean4-for-iut`.

## Submission checklist

- [x] I changed only the relevant catalog's solver attribution, Lean proof information or supporting sources and supplied the applicable evidence.
- [x] The submitted result fully solves the targeted prerequisite statements with no `sorry`, `admit` or added unproved assumptions in the target theorems.
- [x] For Lean: I have linked the complete mathematical solution and its proof or publication evidence provided earlier, or supplied them in this PR, and identified the mathematical solver and Lean formalization author separately.
- [x] For Lean: I am claiming my own contribution in the original personal or organization repository, with verifiable contribution evidence for an organization repository; the selected commit is in the named branch, and I supplied statement correspondence, reproduction commands and axiom audit results.
- [x] This PR contains no Lean source files, archives, binaries, vendored dependencies or private identity/contact/payment information.