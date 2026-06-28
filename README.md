# AI EPD Benchmark Assistant

An AI-powered decision support tool that helps Product Managers benchmark Environmental Product Declarations (EPDs), evaluate methodological comparability, and generate evidence-based sustainability insights for business decisions.

---

## Why this project exists

Comparing EPDs is currently a manual, time-consuming, and expertise-heavy process.

Product Managers often need to answer questions like:

* Can we claim our product is more sustainable than competitors?
* Which environmental indicators are actually comparable?
* Is this comparison reliable enough for marketing or strategic decisions?

However, the process requires:

* Reading long PDF documents
* Understanding LCA methodology (EN 15804, PCR, system boundaries)
* Manually extracting data into Excel
* Interpreting differences across datasets and assumptions

This creates a gap between **business decision needs** and **LCA technical complexity**.

---

## What this project does

This tool helps users:

* Extract structured data from EPD PDFs
* Compare environmental indicators (GWP-total, fossil, biogenic, luluc)
* Evaluate methodological comparability (PCR, FU, system boundary)
* Identify evidence behind differences in lifecycle stages
* Support decision-making for sustainability claims

---

## Core idea

This is not just a comparison tool.

It is a **decision support system for sustainability claims**.

It helps answer:

> “Can this comparison be used for business decisions, and how reliable is it?”

---

## Key outputs

* Structured EPD metadata extraction
* Lifecycle impact comparison (A1–A3, A1–A5, A–C, A–D)
* Evidence-based explanation of differences
* Recommendation on claim suitability:

  * Internal benchmark
  * Marketing claim review required
  * Not suitable for comparison

---

## Project structure

* `docs/` → Product logic, PRD, decision framework
* `prompts/` → AI prompt templates
* `sample_epds/` → Example EPD PDFs
* `outputs/` → Generated comparison reports
* `screenshots/` → UI or result examples

---

## Status

MVP design phase (no code implemented yet)

---

