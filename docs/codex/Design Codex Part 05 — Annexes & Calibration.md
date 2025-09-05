# FUTURE ENGINE Design Codex

## Part V — Annexes & Calibration

*The annex is where the scaffolding is exposed: provenance, calibration, and the technical record that keeps FUTURE ENGINE accountable.*

---

### Provenance & Sources

Every datum in FUTURE ENGINE is archived with:

* Source and author
* Timestamp of retrieval
* License and usage terms
* Classification (factual, human-produced, speculative)
* Confidence levels and known limitations

This archive grows with each cycle, forming a transparent lineage of inputs.

---

### Evaluation & Calibration

FUTURE ENGINE is judged continuously against the past.

* **Rolling Backtests** — Past data are forecast forward, then compared to reality.
* **Cross-Validation** — Multiple folds and temporal splits to test robustness.
* **Calibration Plots & Reliability Diagrams** — Measuring how well probabilities align with outcomes.
* **Scoring Metrics** — Brier score, log loss, CRPS.
* **Change-Point Detection** — Identifying regime shifts in real time.
* **Public Scoring** — Past forecasts remain published for external audit.

---

### Pilot Phase — Blank Years

Before its first public release, FUTURE ENGINE runs two accelerated “blank year” cycles:

* Each compressed into six months, made possible by omitting Part II (the invited essays) from the publication cycle. Only Part I (the narrative timeline) and Part III (the technical annex) are generated.
* Full thousand-year horizon tested.
* Outputs kept internal, not published.
* Used to refine narrative density, black swan integration, and coherence.

---

### Black Swan Generator

A dedicated module ensures futures are not sterile:

* **Historical analogies** — improbable events that nonetheless occurred.
* **Speculative foresight** — imaginative contributions kept in a separate stream.
* **Stochastic shocks** — random injections to mimic chance.

**Plausibility filters** prevent derailment; only events that enrich realism enter the weave.

---

### Technical Stack

* **Hardware** — FUTURE ENGINE is designed with a local-first architecture in mind. It runs on non-proprietary hardware, such as GPU-enabled local clusters or open infrastructure, ensuring long-term control, transparency, and auditability. Cloud-based deployment remains possible, but is not foundational. With GPU acceleration. No proprietary hardware is required. Deployments can scale horizontally to accommodate data volume and model complexity.
* **Storage** — Columnar store (parquet), graph database for TKG, tile-indexed arrays for grids.
* **Pipelines** — Containerized, reproducible DAGs.
* **Modeling** — Probabilistic programming (Stan, Pyro), TS frameworks, ONNX export.
* **UI** — Public website with publications and provenance.
* **Security** — All open-source licenses respected, sensitive data aggregated.

---

### Continuity & Canon

* The output of FUTURE ENGINE is not probabilistic forecasting but stepwise emulation. As such, the concept of increasing uncertainty over time is not structurally applicable. The narrative remains continuous and methodologically coherent across the full thousand-year span.

* While black swans are introduced narratively, their consequences are explicitly modeled. Their disruption affects downstream indicators, altering causal pathways and interacting mathematically with the system's internal structure. Their role is not decorative, but systemic.

* The ritual forbids manual editing: once generated, a year’s timeline is canon. Even black swans, however improbable, are not overwritten once integrated into the weave.

---

**The annex is not garnish: it is the proof of integrity. Without calibration and provenance, FUTURE ENGINE would be an oracle. With them, it is a civic record.**
