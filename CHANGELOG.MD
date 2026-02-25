# 📋 CHANGELOG — AEGIS: The Crystal Labyrinth

All notable changes to the AEGIS cryptographic system.

---

## v10.15 — THE KRAKEN · PG(11,4) · THE OCEAN (Final) `2026-02-25`

**All three exit gates GREEN for the first time.**

### Added
- **Cross-Line Mixing** (ChatGPT R6): 10% of columns carry mixed DNA from different lines via `H[j] ← H[j] + α·H[k]`. Destroys spectral separability while preserving owner decryption through tracked mixing mask.
- **Phantom Tide** (Claude): Tidal zones that oscillate the statistical signature — Zone A natural, Zone B inverted, Zone C equalized. Global attacks average to zero; local attacks drown in the next zone.
- **Second Counter-Illumination** (R6 consensus 3/3): Post-trap re-anchoring to theoretical Hamming target. Applied after all perversities to close the stealth gap.

### Changed
- Model B gap: 0.0180 → **0.0084** (✅ below 0.01 target)
- Cohen d: 0.0279 → **0.0184** (34% improvement)
- Corruption self-calibrated from 77.4% → **74.2%** (Phantom Tide equalization)
- 26,367 coordinate fixes from second Counter-Illumination pass

### Metrics
```
Gap: 0.0084 ✅ | Cohen d: 0.0184 | Entropy: 2.0000 | Attacks: 10/10
Decrypt: OK ✓ | Runtime: 3.4s | ISD: 2^287 | GL(12,4): 287 bits
```

---

## v10.14 — THE KRAKEN · PG(11,4) · Dead Man's Hand `2026-02-25`

### Added
- **Dead Man's Hand** (Claude): 100 columns with shared first 3 coordinates forming phantom cluster + 5 ultra-bait columns forming fake perfect line. Observation destroys the state.
- **AEGIS Cryptographic License v1.0** with the Kraken Clause
- Architect signature block with cryptographic SIG hash

### Metrics
```
Gap: 0.0180 ⚠ | Cohen d: 0.0279 | Entropy: 2.0000 | Attacks: 10/10
```

---

## v10.13 — THE KRAKEN · PG(11,4) · Creative Perversities `2026-02-25`

### Added
- **Siren Song** (300 traps): False clusters from cross-line column similarity
- **Echo Chamber** (200 traps): Mutual mirror pairs creating infinite analysis loops
- **Bermuda Triangle** (150 traps): Fake GF(4)-linear structure on triplets

### Result
Perversities *improved* metrics — structured fake patterns beat random noise.

### Metrics
```
Gap: 0.0180 | Cohen d: 0.0279 | Entropy: 2.0000 | Attacks: 10/10
```

---

## v10.12 — THE KRAKEN · PG(11,4) · Gemini Fixes `2026-02-25`

### Fixed
- **Counter-Illumination**: Theoretical anchor (DIM×3/4 = 9.0) instead of sample mean
- **Decrypt**: Global hash lookup + syndrome-based search (O(n) vs O(n²))
- **Squid Ink**: Expanded threshold from hardcoded `dist<2` to `dist < max(2, THEO_TARGET-5)`

### Changed
- Decrypt from FAIL → **OK ✓** (17 raw candidates → 4 after tie-breaker)
- Gap from 0.1140 → **0.0200** (10× improvement)

### Metrics
```
Gap: 0.0200 | Cohen d: 0.0310 | Corruption: 77.4% | Attacks: 10/10
```

---

## v10.11 — THE KRAKEN · PG(11,4) · First Ocean `2026-02-25`

### Added
- **Streaming architecture**: PG(5,16) → PG(11,4) lazy evaluation
- Only 64,677 columns materialized (1.2% of 5.5M total)
- Full PG(11,4) scale: 5,592,405 points, 1,118,481 spread lines

### Issues
- Decrypt: FAIL (streaming asymmetry, 3 candidates found but O(n²) limited)
- Gap: 0.1140 (5.7× worse than PG(7,4))

---

## v10 — THE KRAKEN · PG(7,4) · Full Battery `2026-02-25`

### Added
- 4 bio-traps: Vortex, Squid Ink, Glass Frog, Counter-Illumination
- [20] Spectral Subspace Attack (ChatGPT R5 design)
- [21] IGCR Attack (Grok R5 design)
- Mimic Octopus adaptive decoys (later removed — KS test failure)

### Metrics
```
Scale: PG(7,4) = 21,845 points | Gap: 0.0048 | Cohen d: 0.0073
Corruption: 65.8% | Attacks: 8/8 | GL(8,4): 127 bits
```

---

## v9.3 — THE LEVIATHAN · Proper Semifield `2026-02-24`

### Fixed
- [FIX-6] Proper Knuth binary semifield (not isotopic scramble)
- [FIX-7] Full T-invariance across all 273 spread lines
- [FIX-8] Noisy decryption from corrupted H, not clean Hc
- [FIX-9] Centralizer test: dim(C) = 18 = n²/2

### Metrics
```
Scale: PG(5,4) = 1,365 points | Attacks: 16/18 defended
Corruption: 38.8% | Gap: 0.0590 | GL(6,4): 71 bits
```

---

## v9.1 — THE LEVIATHAN · Post-Audit `2026-02-24`

### Fixed
- [FIX-1] Conic-based regulus for Hall spread
- [FIX-2] Monolithic T (was block-diagonal)
- [FIX-3] PRF-deterministic Gaslight (was 32/100 collisions → 0/100)

---

## v8 — THE HYDRA `2026-02-23`

Multi-head corruption: introduced parallel corruption phases (entropy flood, classic mixing, bio-inspired, anti-quantum, structural). First version with biologically-inspired traps.

---

## v7 — THE CHIMERA `2026-02-22`

Hybrid spread architecture: combined Desarguesian and non-Desarguesian spread fragments. Introduced Model B (public matrix + hidden partition). First multi-AI audit round.

---

## v6 — THE BASILISK `2026-02-21`

Introduced the corruption engine with multiple phases. First version to achieve >30% corruption with clean decryption. Added gaslight detection metric.

---

## v5 — THE PHOENIX `2026-02-20`

Recovery from failed v4. Rebuilt core around GF(4) arithmetic. Introduced proper spread generation from projective geometry. First working decryption.

---

## v4 — THE MINOTAUR `2026-02-19`

Labyrinth structure for key hiding. Failed — overly complex with no real security gain. Abandoned.

---

## v3 — THE SPHINX `2026-02-18`

Question-based challenge protocol. Introduced the idea of adversarial testing. First attempts at formal metrics (Cohen d, gap analysis).

---

## v2 — THE GRIFFIN `2026-02-17`

Dual-nature system (algebraic + geometric). Introduced the concept of spread-based encryption. Toy scale only (PG(3,4)).

---

## v1 — THE SEED `2026-02-16`

First prototype. Basic GF(4) matrix with random corruption. No formal geometry. Proof of concept that noise injection could hide structure.

> *"Every ocean begins with a single drop."*
