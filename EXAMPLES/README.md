Overview
---

This directory contains the DSLO v0.7 Geometry Instance Layer, a curated, finite set of cross‑cultural, natural, abstract, and machine‑facing examples that demonstrate **geometry**, **signal ecology**, **invariants**, and **substrate‑level behavior**.

These are not glossary entries.
They are static geometry instances, each represented in three canonical formats:

.md — human‑readable description

.ttl — machine‑readable RDF/Turtle semantic object

.json — structured ingestion object

This layer complements the document DSLO v0.7 — Geometry Examples & Demonstrations, which provides expanded explanations and class‑level context for these instances.

---
**Structure**

Geometry instances are organized into six DSLO v0.7 geometry classes:

**Morphological Mimicry & Adaptive Geometry**

**Distributed Cognition & Non‑Neural Intelligence**

**Cultural Signal Systems (Cross‑Cultural)**

**Natural Optimization Phenomena**

**Abstract / Universal Geometry Instances**

**Modern / Machine‑Facing Geometry Instances**

Each class contains multiple instances, each in its own folder:


{{class}}/
    {{instance}}/
        {{instance}}.md
        {{instance}}.ttl
        {{instance}}.json

---
**Purpose**

This layer provides:

canonical examples of DSLO geometry

cross‑domain invariants

natural and cultural signal ecology phenomena

machine‑facing geometry structures

ingestion‑ready semantic objects

alignment with the DSLO v0.7 Geometry Examples & Demonstrations paper

It is part of the DSLO v0.7 Scientific Uptake Release.

---
**Canonical Templates**
The canonical v0.7 templates for .md, .ttl, and .json are stored in:


EXAMPLES/Canonical_v0_7.md
EXAMPLES/Canonical_v0_7.ttl
EXAMPLES/Canonical_v0_7.json

These templates define the required structure for all geometry instances.

Canonical_v0_7.md

# Canonical DSLO v0.7 Geometry Instance Template (.md)

## Overview
A concise description of the phenomenon, focusing on invariant behavior, geometry, or signal ecology.

## Key Properties
- **Invariant Behavior:** {{PROPERTY_1}}
- **Geometry:** {{PROPERTY_2}}
- **Signal Ecology:** {{PROPERTY_3}}
- **Substrate Alignment:** Why this instance belongs in DSLO’s geometry layer.

## DSLO Interpretation
Map the instance to DSLO geometry operators, signal classes, invariants, or manifolds.

## Cross‑Cultural Notes

## References
Canonical_v0_7.ttl
ttl
@prefix dlo: <https://www.tnopsi.com/> .
@prefix ex: <https://www.tnopsi.com/> .
@prefix schema: <http://schema.org/> .

ex:{{ID}} a dlo:GeometryInstance ;
    schema:name "{{NAME}}" ;
    dlo:version "0.7" ;
    dlo:layer "geometry" ;
    dlo:instanceType "natural-invariant" ;
    dlo:description "{{ONE_SENTENCE_SUBSTRATE_DESCRIPTION}}" ;
    dlo:invariantProperties (
        "{{PROPERTY_1}}"
        "{{PROPERTY_2}}"
        "{{PROPERTY_3}}"
    ) ;
    dlo:geometryType "{{GEOMETRY_CLASS}}" ;
    dlo:signalType "{{SIGNAL_CLASS}}" ;
    dlo:crossCulturalPresence "{{YES_OR_NO}}" ;
    dlo:source "DSLO Natural Geometry Registry" .
Canonical_v0_7.json
json
{
  "id": "{{ID}}",
  "name": "{{NAME}}",
  "version": "0.7",
  "layer": "geometry",
  "type": "natural-invariant",
  "description": "{{ONE_SENTENCE_SUBSTRATE_DESCRIPTION}}",
  "invariant_properties": [
    "{{PROPERTY_1}}",
    "{{PROPERTY_2}}",
    "{{PROPERTY_3}}"
  ],
  "geometry_type": "{{GEOMETRY_CLASS}}",
  "signal_type": "{{SIGNAL_CLASS}}",
  "cross_cultural_presence": "{{YES_OR_NO}}",
  "source": "DSLO Natural Geometry Registry"
}
Relation to DSLO v0.7 — Geometry Examples & Demonstrations
The Examples Paper provides expanded explanations for each geometry class, including:

class overview

representative instance

geometric expression

class–instance relationship

DSLO substrate interpretation

This .EXAMPLES directory provides the canonical machine‑readable and human‑readable instance files referenced by the paper.

Citation
If you reference this directory or the Examples Paper:

DSLO v0.7 — Geometry Examples & Demonstrations  
DOI: 10.5281/zenodo.21864440
