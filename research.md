---
layout: default
title: "Research"
permalink: /research/
description: "Research framework: spatial data, environmental text, local knowledge, GeoAI, LLM/RAG and decision support."
---

<div class="kicker">Research architecture</div>

# Research

My strategic research program is organized around **Spatial-Textual Environmental Intelligence (ST-EI)** for coastal resource and environmental management in the Vietnamese Mekong Delta.

> Core principle: combine **where** an environmental process occurs, **what** documents and communities say about it, **what evidence** supports the interpretation, and **how** the result can support a decision.

<div class="notice"><strong>Status:</strong> ST-EI is a strategic research framework for 2026–2036. It describes a planned methodological direction, not a claim that every component has already been built.</div>

## Six-layer method architecture

<div class="research-grid">
  <div class="card"><div class="eyebrow">Layer 01</div><h3>Spatial data</h3><p>Satellite imagery, land-use maps, DEM, salinity/flood/erosion layers, environmental monitoring and field-survey points. Methods: GIS, PostGIS, GeoJSON, QGIS/WebGIS, spatial analysis and composite indicators.</p></div>
  <div class="card"><div class="eyebrow">Layer 02</div><h3>Textual data</h3><p>EIA reports, plans, environmental status reports, earlier research, articles, community interviews, local news and policy documents. Methods: classification, NER, relation extraction, topic modeling and evidence-aware summarization.</p></div>
  <div class="card"><div class="eyebrow">Layer 03</div><h3>Local knowledge</h3><p>Community experience on salinity adaptation, livelihood transitions, cropping calendars, water sources, mangroves, aquaculture and ecotourism. Human-in-the-loop annotation and field validation are central.</p></div>
  <div class="card"><div class="eyebrow">Layer 04</div><h3>GeoAI</h3><p>Land-use/change analysis, environmental hotspots and resource–livelihood risk zones. Priority is given to fit-for-purpose, interpretable models and expert validation rather than model complexity for its own sake.</p></div>
  <div class="card"><div class="eyebrow">Layer 05</div><h3>LLM / RAG</h3><p>Document question answering, evidence synthesis, source-grounded report generation and natural-language retrieval. Planned controls include source tracking, audit logs and evaluation of correctness, completeness and grounding.</p></div>
  <div class="card"><div class="eyebrow">Layer 06</div><h3>Decision support</h3><p>Risk maps, survey priorities, intervention zones, adaptive-livelihood models and environmental-management reports delivered through a GIS–AI dashboard and policy scenarios.</p></div>
</div>

## Core research objects

- Coastal resource and environmental management.
- Climate-change adaptation, salinity intrusion, flooding and sea-level rise.
- Sustainable and adaptive livelihoods: coconut, salt-making, aquaculture and climate-smart agriculture.
- Mangrove conservation, ecotourism and coastal/island systems.
- Vietnamese environmental text, local knowledge and policy evidence.

## Planned data products

| Product family | Strategic name | Intended function |
|---|---|---|
| Corpus | Vietnamese Coastal Environmental Corpus | Labeled environmental, livelihood, climate, planning and community text with metadata |
| Ontology | Environmental Resource Ontology VN | LOCATION, RESOURCE, HAZARD, LIVELIHOOD, ADAPTATION, IMPACT, POLICY, EVIDENCE |
| NLP | NER / RE / classification pipeline | Extract entities, relations, topics and evidence from Vietnamese documents |
| GeoAI | Land-use / risk / hotspot models | Detect land-use change, salinity/flood/erosion risks and environmental hotspots |
| LLM/RAG | Environmental RAG assistant | Source-grounded retrieval, evidence synthesis and document Q&A |
| DSS | GIS–AI decision-support dashboard | Integrate maps, knowledge layers, documents and survey recommendations |

## Geographic focus

The core study region is the **Mekong Delta coastal zone**, with emphasis in the strategic LLKH on **Ben Tre, Tra Vinh, coastal Vinh Long, Can Gio, Kien Giang and Ly Son**. The program is intentionally place-based: AI methods are treated as tools inside environmental-geographic inquiry rather than as an independent pure-AI research agenda.
