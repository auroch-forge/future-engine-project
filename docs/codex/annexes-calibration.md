# Future Engine Codex  
## Part V — Annexes & Calibration  

*The annex is where the scaffolding is exposed: provenance, calibration, and the technical record that keeps the Future Engine accountable.*

---

### Provenance & Sources  

Every datum in the Engine is archived with:  
* Source and author.  
* Timestamp of retrieval.  
* License and usage terms.  
* Classification (factual, human-produced, speculative).  
* Confidence levels and known limitations.  

This archive grows with each cycle, forming a transparent lineage of inputs.  

---

### Evaluation & Calibration  

The Engine is judged continuously against the past.  

* **Rolling Backtests** — Past data are forecast forward, then compared to reality.  
* **Cross-Validation** — Multiple folds and temporal splits to test robustness.  
* **Calibration Plots & Reliability Diagrams** — Measuring how well probabilities align with outcomes.  
* **Scoring Metrics** — Brier score, log loss, CRPS.  
* **Change-Point Detection** — Identifying regime shifts in real time.  
* **Public Scoring** — Past forecasts remain published for external audit.  

---

### Pilot Phase — Blank Years  

Before its first public release, the Engine runs two accelerated “blank year” cycles:  
* Each compressed into six months.  
* Full thousand-year horizon tested.  
* Outputs kept internal, not published.  
* Used to refine narrative density, black swan integration, and coherence.  

---

### Black Swan Generator  

A dedicated module ensures futures are not sterile:  
* Historical analogies — improbable events that nonetheless occurred.  
* Speculative foresight — imaginative contributions kept in a separate stream.  
* Stochastic shocks — random injections to mimic chance.  
* **Plausibility filters** prevent derailment; only events that enrich realism enter the weave.  

---

### Technical Stack  

* **Storage** — Columnar store (parquet), graph database for TKG, tile-indexed arrays for grids.  
* **Pipelines** — Containerized, reproducible DAGs.  
* **Modeling** — Probabilistic programming (Stan, Pyro), TS frameworks, ONNX export.  
* **UI** — Public website with publications and provenance.  
* **Security** — All open-source licenses respected, sensitive data aggregated.  

---

### Limits  

* Beyond ~20 years, uncertainty expands sharply.  
* Black swans resist probability; they are handled narratively, not mathematically.  
* The ritual forbids manual editing: once generated, a year’s timeline is canon.  

---

**The annex is not garnish: it is the proof of integrity. Without calibration and provenance, the Future Engine would be an oracle. With them, it is a civic record.**
