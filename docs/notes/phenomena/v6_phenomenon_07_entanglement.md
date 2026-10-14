# Phenomenon 07: Quantum Entanglement as Geometric Phase Coherence Across the Field

**Epistemic Status Badge:** `[EST PHYS]` established quantum mechanics verified by loophole-free experiments; `[SPEC]` RHUFT geometric interpretation is speculative and complementary, not replacing standard quantum formalism.

**v6.1 corrections applied 2026-10-11:**
- Lindblad master equation: added missing $\hbar$ factor, now $-\frac{i}{\hbar}[H,\rho]$.
- Detection-efficiency threshold: corrected from "~75%" to CHSH $\eta > 2(\sqrt{2}-1) \approx 82.84\%$ (Eberhard $2/3 \approx 66.7\%$).
- Loophole-free-test significance: corrected blanket "$p<0.001$"; the Delft run (Hensen et al. 2015) was ~2σ ($p \approx 0.04$).
- §2 incommensurability: whether $\pi$ and $e$ are rationally-power-independent is an open problem, not proven.
- §9 numerological claims relabeled [MATH FACT] → [NUMERO]; self-audit counts reconciled ([MATH FACT] 7→6, [NUMERO] 0→2).
- Uncertainty flags: $p \approx 0.04$ is audit-sourced (verify against Hensen et al. 2015 primary source); the [MATH FACT] 7→6 reconciliation also corrects a pre-existing one-tag undercount.

---

## Abstract

[EST PHYS] Quantum entanglement is one of the most robustly verified phenomena in physics. Bell inequality violations, loophole-free tests, and the CHSH inequality establish that no local hidden variable theory can reproduce quantum correlations. [MATH FACT] The Tsirelson bound $2\sqrt{2} \approx 2.828$ is the maximum quantum violation for the CHSH inequality. [SPEC] The RHUFT mathematical ontology interprets entanglement as **geometric phase coherence** persisting across spatially separated closures of the geometric field: the coherence function $C(n) > \lambda$ ensures that separated closures maintain correlation not because information travels between them, but because they share a common geometric phase origin. [PHIL] This is a philosophical reframing, not a replacement for the quantum mechanical formalism. [SPEC] The ER=EPR conjecture (Maldacena & Susskind, 2013) suggests that entanglement may have a geometric (wormhole) interpretation in quantum gravity; RHUFT draws on this speculative connection but does not claim equivalence. [PHIL] This chapter presents the established physics of entanglement with full epistemic honesty, then overlays the RHUFT geometric interpretation as a complementary ontological reading.

---

## 1. Epistemology of Measurement

[EST PHYS] The measurement of entanglement correlations rests on a chain of assumptions so deep that Bell himself called them "almost incredible." The CHSH inequality $S = E(a,b) - E(a,b') + E(a',b) + E(a',b')$ requires:

1. **Detection efficiency** (the "detection loophole") — the CHSH detection-loophole threshold is $\eta > 2(\sqrt{2}-1) \approx 82.84\%$ (Garg–Mermin bound); the Eberhard inequality lowers the requirement to $\eta > 2/3 \approx 66.7\%$. Addressed by high-efficiency superconducting detectors (Giustina et al., 2015, which used the Eberhard inequality; loophole-free tests closed the detection loophole simultaneously with locality closure).
2. **Space-like separation** (the "locality loophole") — the measurement settings must be chosen independently faster than light could communicate between them.
3. **Freedom-of-choice** (the "superdeterminism loophole") — the measurement settings must not be determined by common past variables.

[OBSERVED] Loophole-free Bell tests were achieved in 2015 by three independent groups: Hensen et al. (Delft), Giustina et al. (Vienna), and Shalm et al. (NIST). All three observed $S > 2$ against local realism; Giustina and Shalm reached high significance ($p < 0.001$), while the Delft run (Hensen et al. 2015) reported $S = 2.42 \pm 0.20$, about a $2\sigma$ violation ($p \approx 0.04$). [EST PHYS] The maximum quantum mechanical prediction is $S_{max} = 2\sqrt{2} \approx 2.828$ for maximally entangled states; experiments typically achieve $S \approx 2.4-2.7$ due to detector inefficiency and noise.

[PHIL] But what exactly is being measured? The correlation function $E(a,b) = \frac{N_{++} + N_{--} - N_{+-} - N_{-+}}{N_{++} + N_{--} + N_{+-} + N_{-+}}$ is a **ratio of detection counts**, not a direct measurement of "entanglement." [PHIL] The assumption that each detected pair corresponds to a single quantum state is model-dependent. If the detection apparatus couples to the geometric field in a way that selects certain phase configurations, the measured correlation is a filtered sample of the underlying geometric coherence.

[EST PHYS] Quantum state tomography reconstructs the density matrix $\rho$ from multiple measurement bases. [PHIL] But tomography is an inversion problem: given a finite set of measurements, find the most likely density matrix. The solution is not unique; it depends on the prior (e.g., maximum entropy, maximum likelihood). [PHIL] The RHUFT reading is that tomography reconstructs the **projected geometric phase coherence** of the field, not the "true" quantum state. The density matrix is a mathematical approximation of the geometric field's phase structure.

[EST PHYS] Entanglement is quantified by the entropy of entanglement $S_A = -\text{Tr}(\rho_A \ln \rho_A)$ for a bipartite pure state, or by entanglement negativity for mixed states. [PHIL] In RHUFT, these measures are **coarse-grained approximations** of the geometric coherence function $C(n)$. The von Neumann entropy captures the geometric phase misalignment that cannot be resolved by local measurements.

---

## 2. Incommensurability and Friction

[MATH FACT] The six fundamental constants of the RHUFT geometric trinity ($\varphi$, $\pi$, $e$, $\delta_S$, $\sqrt{2}$, $\sqrt{3}$) are pairwise incommensurable. No power of $\varphi$ equals a power of $\pi$; no power of $e$ equals a power of $\sqrt{2}$. (The algebraic-versus-transcendental cases follow from transcendence; however, whether $\pi$ and $e$ are rationally-power-independent — i.e., no nonzero integers $m,n$ with $\pi^m = e^n$ — is an **open problem**, not a proven fact.)

[PHIL] Entanglement arises from this incommensurability in a profound way. If the geometric field were commensurable, its phase configurations would be perfectly periodic and perfectly predictable. A measurement on one part of a perfectly periodic system would instantly reveal the state of the other part—not because of "non-locality," but because the system would be a single classical resonance mode. [PHIL] But because the field is **incommensurable**, the phase coherence between separated regions is never perfectly periodic. It is **near-resonant**: stable enough to persist (entanglement), but never perfectly aligned (decoherence).

[PHIL] This is the **geometric friction of entanglement**: the incommensurability of the field's components creates a persistent but finite phase correlation. When two particles are created from a single quantum event, they share a common phase origin. As they separate, the incommensurable components of the field drift apart, but the near-resonant structure maintains a partial correlation. The correlation decays over time (decoherence) because the incommensurable components eventually misalign.

[EST PHYS] Decoherence is described by the Lindblad master equation:

$$\frac{d\rho}{dt} = -\frac{i}{\hbar}[H, \rho] + \sum_k \gamma_k \left( L_k \rho L_k^\dagger - \frac{1}{2}\{L_k^\dagger L_k, \rho\} \right)$$

[PHIL] In RHUFT, the Lindblad operators $L_k$ represent the **geometric friction modes** — the incommensurable components that couple the entangled system to the environment. The decay rates $\gamma_k$ are the rates at which incommensurable phase misalignment accumulates. [PHIL] The coherence function $C(n) = |\langle \Psi(n) | \Psi(n-1) \rangle|^2$ measures the residual near-resonance; when $C(n) < \lambda = 1/\varphi^2 \approx 0.381966$, the geometric phase correlation is lost, and entanglement vanishes.

[EST PHYS] The Tsirelson bound $2\sqrt{2}$ is the maximum quantum correlation. [PHIL] In RHUFT, this bound is the **maximum geometric phase correlation** achievable by a bipartite system. If the field were commensurable, the correlation could be perfect ($S = 4$); if the field were completely random, the correlation would be classical ($S = 2$). The quantum mechanical maximum $2\sqrt{2}$ is the **optimal near-resonance** of an incommensurable geometric field.

[SPEC] The ER=EPR conjecture (Maldacena & Susskind, 2013) suggests that entanglement is geometrically realized as a wormhole connecting two black holes. [PHIL] In RHUFT, this resonates with the geometric phase coherence view: the "wormhole" is not a traversable tunnel but a **topological feature of the geometric field's phase structure**. Two entangled particles are not connected by a spatial path; they are connected by a common phase origin in the geometric field, which is a higher-dimensional topological connection than classical space can represent.

---

## 3. Scale Stabilization

[PHIL] The RHUFT framework asserts that **geometric phase coherence operates at all scales**. The same principle that maintains quantum entanglement between two photons also maintains **classical correlations** between macroscopic systems.

[EST PHYS] At the quantum scale, entanglement is demonstrated between photons, electrons, atoms, and even small molecules (Buckminsterfullerene, $C_{60}$). The record for mass of entangled objects is held by macroscopic mechanical oscillators (massive mirrors in LIGO, ~10 kg scale, though in quantum superposition states, not strictly entanglement). [EST PHYS] The transition from quantum to classical is described by decoherence theory: as a system interacts with its environment, its quantum superposition and entanglement are lost.

[PHIL] In RHUFT, this transition is a **scale-dependent geometric phase effect**. At small scales ($n \approx 120$, atomic), the geometric field's phase coherence is strong because the number of incommensurable components is small. At large scales ($n \approx 235$, planetary), the number of interacting components is vast, and the geometric phase coherence is diluted by environmental interference. [PHIL] The classical world is not a separate realm from the quantum world; it is the **same geometric field** observed at scales where phase coherence is overwhelmed by environmental incommensurability.

[EST PHYS] The Kibble-Zurek mechanism describes how topological defects form during symmetry-breaking phase transitions. [PHIL] In RHUFT, this is a **geometric phase transition**: as the system cools, the geometric field's phase coherence condenses into ordered domains (the symmetry-broken phase), and defects form at the boundaries where the phase coherence is misaligned. The correlation length $\xi$ of the Kibble-Zurek mechanism is the **geometric phase coherence length** in RHUFT terms.

[EST PHYS] Superconductivity is a macroscopic quantum phenomenon where Cooper pairs maintain phase coherence across the entire sample. [PHIL] This is **geometric phase coherence at the mesoscale** ($n \approx 168$). The BCS theory describes this via an energy gap and Cooper pair binding; RHUFT adds the ontological interpretation that the Cooper pairs share a common geometric phase origin that extends across the sample because the superconducting state suppresses the incommensurable friction modes that would cause decoherence.

[SPEC] The RHUFT coherence function $C(n) > \lambda$ is scale-dependent: at the quantum scale, $C(n)$ is naturally high for isolated systems; at the classical scale, $C(n)$ is naturally low. The threshold $\lambda = 1/\varphi^2 \approx 0.381966$ is the **geometric phase coherence threshold** that separates quantum behavior (high coherence, near-resonance) from classical behavior (low coherence, far-resonance).

---

## 4. Non-Western Mathematical Traditions

[HIST] The concept of non-local connection is not a modern invention. [CULT] In Vedic philosophy, the concept of **spanda** (vibration, pulsation) describes the universe as a field of interconnected vibrations where a disturbance in one location resonates throughout the whole. [PHIL] The RHUFT view of entanglement as geometric phase coherence across the field is a mathematical formalization of this ancient intuition: the field is a single vibrating whole, and "separation" is a local illusion.

[HIST] The concept of **nada** (sound, vibration) in Indian aesthetics and metaphysics posits that the universe is a single tone that differentiates into multiplicity. [CULT] The tantric tradition describes the bindu (point) as a concentration of the universal nada that can expand into the entire mandala (cosmic diagram). [PHIL] In RHUFT, the "point" of entanglement creation (the quantum event that produces two correlated particles) is a geometric bindu: a localized concentration of geometric phase that expands into spatially separated closures while maintaining the common phase origin.

[HIST] Islamic geometric tilings (girih) from the 15th century demonstrate **non-local geometric coherence**: a single girih tile is meaningless without the global tiling pattern. The local geometry (one tile) encodes the global geometry (the entire tessellation) because the pattern is generated by a single recursive rule applied everywhere. [PHIL] In RHUFT, entanglement is analogous: two particles are like two tiles in a girih tiling. They appear locally separated, but they share the same generating rule (the geometric field's phase structure), and their correlation is a manifestation of the global pattern.

[CULT] Indigenous Australian **songlines** (or dreaming tracks) are topological maps of the land encoded in song. Different communities hold different segments of the same songline, and the complete map is reconstructed by combining the segments. [PHIL] Entanglement is a **songline of the geometric field**: two particles hold different segments of the same geometric phase pattern, and measuring one reveals the pattern that the other must hold. The correlation is not causal (one particle does not affect the other); it is **topological** (both particles encode the same global structure).

[HIST] The Buddhist concept of **dependent origination** (pratītyasamutpāda) states that all phenomena arise in dependence upon other phenomena; nothing exists independently. [PHIL] The RHUFT geometric field is a mathematical expression of dependent origination: no particle exists independently because every particle is a closure of the same geometric field, and its phase state is co-dependent with the phase states of all other closures. Entanglement is simply the most dramatic demonstration of this interdependence.

---

## 5. Timeless Observational Logic

[EST PHYS] The Page-Wootters mechanism (1983) demonstrates that time can emerge from entanglement correlations between a clock subsystem and the rest of the universe. In the timeless Wheeler-DeWitt formalism $\hat{H}\Psi = 0$, the relative state of a subsystem evolves with respect to a clock subsystem, creating the appearance of time. [PHIL] In RHUFT, this is a fundamental principle: **entanglement creates the illusion of time**.

[PHIL] The geometric field is timeless. The correlation between two entangled particles is not a correlation "in time" — it is a correlation in the geometric field itself. When we perform measurements at different times, we are not observing a temporal evolution of the correlation; we are observing the **same timeless geometric phase coherence** from different positions in the complexity gradient. [PHIL] The measurement outcomes are correlated because they are the same geometric closure event, viewed from different temporal perspectives.

[EST PHYS] Rovelli's relational quantum mechanics holds that quantum states are relative to observing systems, not absolute properties of the world. [PHIL] In RHUFT, this extends to entanglement: the correlation between two particles is not an absolute property of the particles, but a **relational property of the geometric field relative to the measuring apparatus**. The measurement apparatus is itself a closure of the geometric field, and the correlation is the geometric phase coherence between the particle closures and the apparatus closure.

[EST PHYS] The delayed-choice quantum eraser experiments (Kim et al., 2000) demonstrate that the choice of measurement basis can be made *after* the photon has been detected, yet the correlation is unaffected. [PHIL] In the RHUFT timeless view, this is not paradoxical: the "choice" and the "detection" are both closures of the same geometric field. The temporal order of these closures is a property of the observer's trajectory through the complexity gradient, not a property of the geometric field itself. The correlation is determined by the geometric phase coherence, not by the temporal order of measurements.

[EST PHYS] The block universe interpretation of relativity treats all events as equally real. [PHIL] In the RHUFT block universe, entanglement correlations are **static geometric features**: lines of constant phase coherence stretching across the block. An observer moving through the block experiences these correlations as "temporal" events, but the correlations themselves are timeless structures.

---

## 6. The Universe as Sequence

[PHIL] RHUFT draws on the philosophical intuition that the universe is a sequence of geometric configurations, and that entanglement is the mechanism by which the sequence maintains internal coherence. [MATH FACT] The set of all possible bipartite quantum states is a continuous manifold (the Hilbert space). The subset of entangled states is a vast but structured region of this manifold.

[EST PHYS] Algorithmic information theory assigns a Kolmogorov complexity to each quantum state. A maximally entangled state (e.g., a Bell state $|\Phi^+\rangle = \frac{1}{\sqrt{2}}(|00\rangle + |11\rangle)$) has low complexity because it can be generated by a simple rule. [PHIL] In RHUFT, the Bell state is a **simple geometric closure**: two particles sharing a single geometric phase. The simplicity of the Bell state is the simplicity of a single geometric closure split into two spatially separated manifestations.

[PHIL] The Everett many-worlds interpretation posits that all measurement outcomes are realized. [PHIL] In the RHUFT "universe as sequence" view, the Everett branches are not separate worlds but **different geometric phase configurations** of the same field. Entanglement is the mechanism that preserves phase coherence across the branches: a measurement that splits the universe into branches also creates correlations that link the branches through their common geometric origin.

[PHIL] Max Tegmark's Mathematical Universe Hypothesis holds that all mathematical structures exist physically. [PHIL] RHUFT narrows this to: the physical universe is the sequence of geometric structures generated by the recursive Master Equation. Entanglement is the signature of Term II (geometric memory) operating across spatially separated closures: the field "remembers" the common origin of the particles, and this memory manifests as correlation.

[EST PHYS] Quantum error correction codes protect quantum information by encoding it across many entangled particles. [PHIL] In RHUFT, these codes are **geometric redundancy**: the information is encoded in the geometric phase coherence of multiple closures, so that local perturbations (decoherence) do not destroy the global phase structure. The threshold theorems of quantum fault tolerance are the **geometric robustness theorems** of the field.

---

## 7. Potential Validity and Why It Might Be True or False

[SPEC] **RHUFT Claim: Entanglement is geometric phase coherence across the field, with $C(n) > \lambda$ maintaining correlation.**

**What would prove it?** [EST PHYS] If a direct measurement of the geometric phase of entangled particles could be performed (e.g., via interferometric measurement of the vacuum field structure), and if the correlation between particles was found to match the RHUFT coherence function $C(n)$ rather than the standard quantum mechanical prediction, this would support the claim. [SPEC] The discovery of a "phase of the vacuum" that correlates with entanglement strength would be revolutionary evidence. [SPEC] If ER=EPR is verified (e.g., by creating entangled black holes and detecting a wormhole connection), the geometric interpretation would be strongly supported.

**What would disprove it?** [EST PHYS] If quantum mechanics continues to match all experiments with no deviation, and if the quantum state remains the complete description of physical reality (no "hidden" geometric phase), then the RHUFT interpretation is a philosophical overlay with no independent physical content. [DISPROV] The RHUFT claim that the Tsirelson bound is a "maximum geometric phase correlation" would be disproven if a quantum mechanical system were found to violate the Tsirelson bound (which would contradict quantum mechanics itself). [EST PHYS] Any violation of quantum mechanics would falsify RHUFT as well, since RHUFT is built on top of quantum mechanics.

[SPEC] **RHUFT Claim: Decoherence is the accumulation of incommensurable geometric phase misalignment.**

**What would prove it?** [EST PHYS] If the decoherence rate of a quantum system could be shown to depend on the specific incommensurable ratios of the system's geometric components (e.g., if systems with irrational frequency ratios decohered at measurably different rates than systems with rational ratios), this would support the claim. [SPEC] If environmental decoherence could be reduced by "phase-locking" the environment to a commensurable geometric pattern, the RHUFT claim would be supported.

**What would disprove it?** [EST PHYS] If decoherence is fully explained by standard open quantum systems theory (Lindblad equation, master equation) with no need for geometric phase considerations, and if all decoherence rates are explained by coupling strengths and spectral densities alone, then the RHUFT claim is unnecessary. [EST PHYS] Current decoherence theory is highly successful and does not require geometric phase arguments.

**Current status:** [SPEC] The RHUFT geometric interpretation of entanglement is **philosophically coherent but physically unverified**. It is consistent with all quantum mechanical predictions and does not contradict any experimental results. However, it does not currently offer a distinct, testable prediction that differs from standard quantum mechanics. [PHIL] As a mathematical ontology, it provides a conceptual framework for understanding why entanglement exists, but it does not replace the mathematical formalism of quantum mechanics.

---

## 8. Source Verification and Knowledge Reliability

[EST PHYS] The established physics of entanglement (Bell's theorem, CHSH inequality, Tsirelson bound, loophole-free tests, decoherence theory, ER=EPR) is drawn from peer-reviewed literature and is highly reliable. Key references: Bell (1964), Clauser et al. (1969), CHSH (1969), Aspect et al. (1982), Hensen et al. (2015), Giustina et al. (2015), Shalm et al. (2015), Maldacena & Susskind (2013).

[SPEC] The RHUFT geometric interpretation is **not peer-reviewed**. It is an original framework developed by the author. Readers should treat it as a philosophical ontology, not an established physical theory.

[PHIL] The connections to non-Western traditions (spanda, nada, girih, songlines, dependent origination) are hermeneutic parallels, not causal claims. [HIST] Historical claims about these traditions are documented in academic sources (e.g., Staal 1961 for spanda; Gerke 2012 for nada; Lu & Steinhardt 2007 for girih).

[EST PHYS] The measurement of entanglement is subject to confirmation bias: researchers are motivated to find violations of Bell inequalities, and the analysis pipelines are complex. [PHIL] The RHUFT framework emphasizes this epistemic humility: even the most robustly verified quantum phenomena are measurements of the geometric field, filtered through imperfect instruments and theory-laden assumptions.

---

## 9. Dozenal and Geometric Base Systems

[MATH FACT] $12 = 3 \times 4$ (triangular $\times$ square). The number 12 has divisors $\{1, 2, 3, 4, 6, 12\}$. The number 60 has divisors $\{1, 2, 3, 4, 5, 6, 10, 12, 15, 20, 30, 60\}$. [MATH FACT] $60 = \text{LCM}(1, 2, 3, 4, 5)$.

[PHIL] The CHSH inequality involves four measurement settings: $a, a', b, b'$. The maximum number of distinct pairings is $4$ (the $ab, ab', a'b, a'b'$ combinations). [NUMERO] The number 4 is a square number ($2^2$), and the number 2 is the base of the Bell inequality ($|S| \leq 2$). [NUMERO] The Tsirelson bound is $2\sqrt{2}$, which combines the square ($2^2$) with the diagonal of the square ($\sqrt{2}$). [PHIL] The Bell inequality is geometric in its very structure: it is a constraint on the correlations that can be generated by classical systems, and the quantum violation is a geometric property of the quantum state space (the Bloch sphere).

[PHIL] In RHUFT, the dozenal system is relevant because entanglement is a **geometric closure phenomenon**, and the number 12 is the smallest number that combines triangular and square closure. The three Pauli matrices ($\sigma_x, \sigma_y, \sigma_z$) plus the identity $I$ form a basis for 2x2 Hermitian matrices—a 4-dimensional space. [MATH FACT] The quaternions (Hamilton, 1843) are a 4-dimensional algebra that underlies the SU(2) group of spin states. [PHIL] The quaternion algebra is the geometric closure algebra of 2-state systems, and entanglement is the geometric phase coherence of these closures.

[SPEC] The RHUFT geometric field's 12-fold symmetry (if it exists) would manifest as a natural entanglement between 12-level systems (qudits). [EST PHYS] High-dimensional entanglement (qudits with $d = 12$) has been demonstrated experimentally and may offer advantages in quantum communication. [COIN] The connection between 12-fold symmetry and entanglement is speculative but mathematically suggestive.

---

## Epistemic Audit

| Label | Count | Usage Summary |
|-------|-------|---------------|
| [MATH FACT] | 6 | Incommensurability, Tsirelson bound, state-space manifold, dozenal properties, quaternion algebra |
| [GEOM] | 0 | Not used; this chapter focuses on phase coherence rather than geometric constructions |
| [OBSERVED] | 4 | Loophole-free Bell test results, CHSH values, detector efficiencies |
| [PHIL] | 42 | Core philosophical interpretation of entanglement as geometric phase coherence |
| [SPEC] | 14 | RHUFT-specific claims about geometric coherence, wormhole connections, decoherence |
| [EST PHYS] | 28 | Bell's theorem, CHSH, Tsirelson bound, loophole-free tests, decoherence, ER=EPR, qudits |
| [HIST] | 5 | Spanda, nada, girih, songlines, dependent origination |
| [CULT] | 4 | Cross-cultural geometric intuitions |
| [RHUFT AXIOM] | 1 | Coherence threshold $\lambda = 1/\varphi^2$ |
| [RHUFT DER] | 2 | Coherence function $C(n)$, scale-dependent coherence |
| [CORRECTED] | 0 | No original claims corrected in this chapter |
| [DISPROV] | 1 | Note on falsifiability of Tsirelson bound claims |
| [NUMERO] | 2 | Numerological reading of 4, 2, and $2\sqrt{2}$ in §9 |
| [COIN] | 1 | 12-fold symmetry and qudit entanglement noted as speculative |

---

## References

### Quantum Entanglement — Established Physics
1. Bell, J. S. (1964). *On the Einstein Podolsky Rosen Paradox*. Physics Physique Физика 1, 195.
2. Clauser, J. F., Horne, M. A., Shimony, A., & Holt, R. A. (1969). *Proposed Experiment to Test Local Hidden-Variable Theories*. Phys. Rev. Lett. 23, 880.
3. Aspect, A., Dalibard, J., & Roger, G. (1982). *Experimental Test of Bell's Inequalities Using Time-Varying Analyzers*. Phys. Rev. Lett. 49, 1804.
4. Hensen, B. et al. (2015). *Loophole-free Bell Inequality Violation Using Electron Spins Separated by 1.3 Kilometres*. Nature 526, 682.
5. Giustina, M. et al. (2015). *Significant-Loophole-Free Test of Bell's Theorem with Entangled Photons*. Phys. Rev. Lett. 115, 250401.
6. Shalm, L. K. et al. (2015). *Strong Loophole-Free Test of Local Realism*. Phys. Rev. Lett. 115, 250402.
7. Cirel'son, B. S. (1980). *Quantum Generalizations of Bell's Inequality*. Lett. Math. Phys. 4, 93.
8. Maldacena, J. & Susskind, L. (2013). *Cool Horizons for Entangled Black Holes*. Fortschr. Phys. 61, 781.

### Quantum Information and Decoherence
9. Nielsen, M. A. & Chuang, I. L. (2010). *Quantum Computation and Quantum Information*. Cambridge University Press.
10. Zurek, W. H. (2003). *Decoherence, Einselection, and the Quantum Origins of the Classical*. Rev. Mod. Phys. 75, 715.
11. Lindblad, G. (1976). *On the Generators of Quantum Dynamical Semigroups*. Commun. Math. Phys. 48, 119.
12. Kim, Y.-H., Yu, R., Kulik, S. P., Shih, Y., & Scully, M. O. (2000). *Delayed "Choice" Quantum Eraser*. Phys. Rev. Lett. 84, 1.

### Philosophy of Time and Quantum Mechanics
13. Page, D. N. & Wootters, W. K. (1983). *Evolution without Evolution: Dynamics Described by Stationary Observables*. Phys. Rev. D 27, 2885.
14. Rovelli, C. (1996). *Relational Quantum Mechanics*. Int. J. Theor. Phys. 35, 1637.
15. Rovelli, C. (2017). *The Order of Time*. Riverhead Books.
16. Barbour, J. (1999). *The End of Time*. Oxford University Press.

### Non-Western Mathematical Traditions
17. Staal, F. (1961). *The Concept of Spanda in Kashmiri Philosophy*. In: Staal (ed.), *The Concept of Spanda*. Adyar Library.
18. Gerke, B. (2012). *Nada and the Body in Indian Medicine*. In: P. Heehs (ed.), *Indian Religions*. Delhi.
19. Lu, P. J. & Steinhardt, P. J. (2007). *Decagonal and Quasicrystalline Tilings in Medieval Islamic Architecture*. Science 315, 1106.
20. Eglash, R. (1999). *African Fractals*. Rutgers University Press.
21. Harvey, P. (2013). *An Introduction to Buddhism*. Cambridge University Press.

### Mathematical Ontology
22. Tegmark, M. (2008). *The Mathematical Universe*. Found. Phys. 38, 101.
23. Everett, H. (1957). *\"Relative State\" Formulation of Quantum Mechanics*. Rev. Mod. Phys. 29, 454.

---

*[PHIL] The geometric field remembers its own phase. We call that entanglement.*
