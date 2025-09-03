# Future Engine Codex  
## Part I — Core Architecture  

*A civic-scale forecasting system built to endure across centuries, weaving heterogeneous data into a single, continuous history of the future.*  

---

### Core Principles  

* **Transparency** — All code, data provenance, model cards, and evaluation are published openly. Every input is cited; every method is visible.  
* **Annual Rhythm** — The engine breathes once per year. Data flows in constantly, but a new *Future History* is only generated at the close of the yearly cycle.  
* **One Timeline** — The public artifact is not a branching fan of probabilities, but a single coherent history. Uncertainty is tracked internally, but the story itself is unbroken.  
* **Narrative Voice** — The output is written as a history of the future, in the tone of a venerable elder speaking to the young — intimate, civic, continuous.  
* **Integration, not competition** — Specialized projects and datasets are tributaries; the Engine is the river.  
* **Non-Intervention** — The timeline is never hand-tuned for outcome. Methodology is sovereign. Adjustment happens only in the engine design, never in the generative act itself.  
* **Fixed Horizon** — Each edition spans one thousand years beyond publication. This horizon is immutable, anchoring every volume in the same vast arc.  

---

### Input Sources  

**Factual Data**  
* Macro: World Bank, IMF, UN, national statistics.  
* Earth observation: ECMWF, DestinE, Microsoft Aurora, Aardvark Weather, satellite imagery, AIS/ADS-B.  
* Historical databanks: Seshat Global History Databank, cliodynamic archives.  

**Human-Produced Data**  
* Forecasting platforms: IFs, Metaculus, Good Judgment Project.  
* Event prediction systems: EMBERS, regional monitors.  
* Literature & news: structured by LLM-assisted extraction with citations and uncertainties.  
* Black Swan Stream: deliberately imaginative or speculative inputs, isolated for improbable shocks.  

Each datum carries full provenance: source, timestamp, license, classification, and confidence.  

---

### Data Architecture  

* **Ingestion & Provenance Layer** — Connectors for structured and unstructured data, with point-in-time snapshots to prevent leakage.  
* **World State Store** —  
  * Temporal Knowledge Graph (entities, events, relationships, timestamps).  
  * Spatiotemporal arrays (climate, vegetation, infrastructure).  
  * Feature store (derived indicators, moving averages, lagged features).  
* **Versioning** — All sources and transformations archived, ensuring reproducibility.  

---

### Modeling Framework  

The engine houses a *model zoo*, an ensemble of methods spanning multiple scales:  

* **Time Series & Panel Models** — ARIMA, ETS, boosted trees, transformers (TFT, N-HiTS, PatchTST).  
* **Causal Models** — Bayesian structural time series, SCMs, difference-in-differences.  
* **System Dynamics** — Stock-and-flow models linking energy, economy, and climate.  
* **Agent-Based Models** — Migration, conflict, supply-demand shocks.  
* **Nowcasting** — High-frequency signals estimating present state.  
* **Data Assimilation** — Kalman and ensemble filters merging observation with model state.  
* **Ensembling** — Bayesian model averaging, stacking, and human-in-the-loop adjustments.  

---

### Annual Cycle  

1. **Release** of the Future History volume.  
2. **Analysis** of engine performance, streams, and sources.  
3. **Update** of the engine, integrating lessons learned.  
4. **Retrieval** of refreshed snapshots for all inputs.  
5. **Generation** of the timeline — a single, unique act, no retries.  
6. **Distribution** of the draft to invited essayists.  
7. **Annex Update** with methodology, provenance, calibration.  
8. **Publication** of the new volume.  
9. **Return** to step 1 — the ritual continues indefinitely.  

---

### Long Horizons  

* Yearly steps are consistent whether projecting near or far.  
* Near-term years lean on data; distant years rely more on modeled trajectories.  
* Wide-scale inputs (e.g. climate over centuries) stabilize the weave, constraining detail from narrow-scale streams (e.g. monthly politics).  
* The result is a tapestry: grand arcs hold, fine details are tethered, continuity prevails.  

---

### Limits  

* Beyond ~20 years, uncertainty expands; outputs become pathways, not certainties.  
* Black swans cannot be captured by probability alone; a dedicated module provides structured unpredictability.  
* The ritual forbids manual correction: once a year’s timeline is written, it is canon.  

---

**This is the backbone: the architecture on which all else rests.**
