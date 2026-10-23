# Simulation Settings

Supplementary material for **Continuity Capability and Recovery in VPP-Supported Local Systems**.

This repository provides a supplementary PDF documenting the resource operating parameters, regulation settings, frequency-security limits, and cost coefficients used in the paper's case studies. The document should be read alongside the manuscript for the system model, optimization formulation, and case-study scenarios.

## Contents

The supplementary PDF contains parameter tables, cost functions, and references covering:

* **Resource operating parameters:** scheduled synchronous-generator (SG) and grid-forming (GFM) output; energy storage system (ESS) ratings, state-of-charge limits, and efficiency; electric vehicle (EV) battery ratings, connection patterns, and state-of-charge requirements; and thermostatically controlled load (TCL) ratings, comfort limits, and thermal-parameter sources.
* **Regulation settings:** communication latencies, resource-response time constants, and the bounds on the resource-specific parameters αᵢ.
* **Frequency-security and support settings:** frequency-deviation and rate-of-change-of-frequency (RoCoF) limits, GFM dynamic headroom, and inertia and damping bounds.
* **Cost settings:** quadratic load-support, reserve, and inertia/damping support cost functions and their coefficients.

## Modeling Conventions

* Dynamic power and frequency deviations are expressed in per unit on **100 MW** and **50 Hz** bases.
* The EV and TCL fleets are represented as aggregate virtual batteries.
* Resource responses following communication delays use first-order dynamics. The reported communication latencies are mean values; simulation delays are sampled from the distributions cited in the parameter document.
* Power arguments in the cost functions are expressed in **MW**, and the time-step duration is expressed in **hours**. The incremental load-support cost includes the time-step duration; the reserve cost follows the separate expression given in the document.
* The inertia/damping support cost is charged once over the maintenance window.

## Access the Document

Open the PDF from the repository's file list to view the supplementary simulation settings, or download it for offline reading.

## 

