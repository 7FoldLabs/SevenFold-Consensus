# SevenFold Benchmarks & Development Reports
This folder collects the public-facing benchmark and development artifacts for the
SevenFold Proof of Consensus. These reports are supporting evidence for the Zenodo
papers and show that SevenFold has been implemented and exercised in a real test
environment.

## Included reports

1. **SevenFold Public Verification Benchmark v1.0**  
   File: `SevenFold_Public_Verification_Benchmark_v1.0.pdf`  
   A minimal, self-contained verification scenario that defines the canonical
   5-axis constellation, rotor order `{0, 3, 1, 4, 2}`, and a simple adversarial
   input set. Intended as the first stop for anyone wanting to sanity-check the
   protocol.

2. **SevenFold vs Ethereum Benchmark v1.0**  
   File: `Sevenfold test vs Ethereum.pdf`  
   Side-by-side latency comparison between SevenFold PoC and an Ethereum test
   node. Demonstrates bounded deterministic finality versus probabilistic
   confirmation, using the same hardware and tooling.

3. **SevenFold Genesis Benchmark Report**  
   File: `Sevenfold_White_20251021174119.pdf` (Genesis benchmark scroll)  
   Narrative + data from the first end-to-end SevenFold benchmark run
   (including the initial successful execution at 10:44 AM). Captures early
   measurements and the evolution of the test harness.

4. **SevenFold PoC Development Report**  
   File: `7FoldPoC Dev report.pdf`  
   Engineering notebook for the initial multi-node PoC. Describes the local
   environment, scripts used, observed behavior, and lessons learned while
   bringing the rotor and centroid model to life.

5. **SevenFold Benchmark Snapshot (v0.9)** *(optional)*  
   File: `Benchmark test 7fold copy.pdf`  
   Earlier benchmark snapshot preserved for historical completeness. Useful for
   seeing how the measurement approach evolved over time.

---

For formal definitions and protocol specification, see:

- **SevenFold Proof of Consensus — Whitepaper (v1.0)** – Zenodo DOI:
  `10.5281/zenodo.17914272`  
- **SevenFold Protocol — Canonical Objects and Invariants** – Zenodo DOI:
  `10.5281/zenodo.17940111`  
- **SevenFold Proof of Consensus — Canonical Specification (v2.0)** – Zenodo DOI:
  `10.5281/zenodo.17970561`
