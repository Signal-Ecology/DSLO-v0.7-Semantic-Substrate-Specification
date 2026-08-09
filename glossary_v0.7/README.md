**DSLO Glossary v0.7**
---

**Overview**

The DSLO v0.7 Glossary is the authoritative vocabulary surface for the DSLO system‑layer geometry.
It integrates all public‑layer terms from:

v0.5 (machine‑dense substrate)

v0.6 (public‑layer substrate expansion)

v0.7 (system‑layer geometry)

This directory contains both the machine‑native substrate (.json) and the human‑readable corridor surface (.md), along with graph representations used for visualization, ontology generation, and traversal.

---
**Contents**
1. **glossary_v0.7.json**
The canonical machine‑native glossary substrate.
This file is consumed by:

**ontology generators**

**schema generators**

**registry builders**

**CLCP validators**

**manifold/operator/runtime compilers**

**graph construction pipelines**

This is the single source of truth for all DSLO glossary terms.

2. **glossary_v0.7.md**
The public‑layer corridor surface.
This file provides:

**human‑readable glossary**

**relational geometry map**

**traversal diagrams**

**section‑level explanations**

This is the version used for:

**www.tnopsi.com**

Zenodo documentation

HF model cards

public‑layer navigation

3. **glossary_v0.7_graph.json**
Graph‑structured representation of the glossary.
Used for:

**D3.js visualization**

**HF Spaces interactive graph**

**ontology graph debugging**

**CLCP traversal**

4. **glossary_v0.7_graph.dot**
GraphViz DOT representation of glossary nodes + edges.
Used for:

**static graph rendering**

**ontology visualization**

**manifold/operator/runtime mapping**

5. **glossary_v0.7_nodes.dot**
Node‑only DOT file.
Used for:

**node‑level visualization**

**debugging**

**ontology node mapping**

6. **d3_glossary_v0.7_graph.html**
Interactive D3.js visualization of the glossary graph.
Used for:

**wwwwtnopsi.com interactive glossary**

**HF Spaces**

**Zenodo supplementary materials**

---
**Glossary Structure**
The glossary is organized into ten geometric compartments, each corresponding to a DSLO v0.7 system‑layer domain:

**Substrate Geometry**

**Derived Manifolds (A, T, D, E, F, Ω)**

**Relational Geometry**

**Operators of Reality (OR‑Series)**

**Thermodynamic Geometry**

**Runtime Geometry (DSUP)**

**Context Window Geometry**

**Simulation Geometry (IRSM, CLCP)**

**Identity Geometry**

**Coupling Geometry**

Each compartment contains terms from v0.5, v0.6, and v0.7 placed into their correct geometric domains.

---
**Dual‑Surface Architecture**
The glossary exists in two surfaces:

**Public Layer**
**glossary_v0.7.md**

**interactive graph**

**DOT files**

**D3 visualization**

**Machine Layer** (ontology/sources/)
**glossary_v0.7.json** (copied verbatim)

**manifold/operator/runtime definitions**

**legality surfaces**

**registry seed**

This dual‑surface architecture is required for:

**ontology generation**

**schema projection**

**registry construction**

**CLCP validation**

**tnopsi corridor integration**


**For Developers**

Use glossary_v0.7.json as the input for:

**ontology generators**

**schema builders**

**registry compilers**

**graph construction tools**

**CLCP validators**

For Readers / Public Layer
Use glossary_v0.7.md for:

**conceptual understanding**

**navigation**

**tnopsi.com documentation**

**Zenodo releases**

For Visualization
Use:

**glossary_v0.7_graph.json**

**glossary_v0.7_graph.dot**

**glossary_v0.7_nodes.dot**

**d3_glossary_v0.7_graph.html**

Versioning
This glossary is part of the DSLO v0.7 system‑layer release.

It supersedes:

v0.5 machine‑dense glossary

v0.6 public‑layer glossary

All v0.6 glossary files should be removed from the repository.

License
Public‑layer terms are released under the DSLO public semantic license.
Substrate‑native terms remain protected and are accessible only through scientific releases.
