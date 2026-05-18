# 🌍 Mehran DHN | Digital Cultural Heritage Projects

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![IIIF](https://img.shields.io/badge/IIIF-Compliant-blue)
![RDF](https://img.shields.io/badge/RDF-Knowledge%20Graph-purple)
![Persian Heritage](https://img.shields.io/badge/Focus-Persian%20Heritage-red)

**Making Persian Cultural Heritage Accessible, Interoperable, and Alive through Open Standards**

A central hub for open-source projects focused on **digitally preserving, enriching, and semantically linking Persian/Iranian cultural heritage**. 

We transform scattered GLAM resources (manuscripts, documents, photographs, archives) into **FAIR** (Findable, Accessible, Interoperable, Reusable) and **LOUD** (Linked Open Usable Data) assets using **IIIF**, **RDF/OWL**, Linked Data, and community-driven pipelines.

## ✨ Vision & Common Goals

All projects share these priorities:
- **Semantic Depth** — Rich RDF knowledge graphs aligned with CIDOC-CRM, schema.org, Getty vocabularies (AAT/TGN), LCSH, and Wikidata.
- **Visual Excellence** — IIIF Presentation API 3 for high-resolution, zoomable, annotatable access.
- **Reunification** — Virtual reconstruction of dispersed collections (e.g., Shah Tahmasp folios, Qajar documents).
- **Machine + Human Usability** — SPARQL-ready graphs + friendly viewers (Mirador).
- **Ethical & Community-Driven** — Open access, provenance respect, volunteer collaboration, Persian-language support.
- **Persian Heritage Focus** — Qajar era, Shahnameh, historical photography, architecture, genealogy (FHKB integration).

## 📂 Featured Projects

| Project | Focus | Key Technologies | Status | Repo |
|---------|------|------------------|--------|------|
| **[IIIFCollection](https://github.com/MehranDHN/IIIFCollection)** | Dynamic hierarchical IIIF catalog for Persian culture, art, architecture, books & photos | IIIF 3, JSON-LD, custom ontology, controlled vocabularies (AAT/TGN/LCSH) | Active | [→](https://github.com/MehranDHN/IIIFCollection) |
| **[ghani-persian-kg](https://github.com/MehranDHN/ghani-persian-kg)** | Full KG mirror of Ghassem Ghani Qajar collection (Yale) — documents, personalities, places | RDF/Turtle, scraping pipeline, SPARQL examples, IIIF placeholders | Active | [→](https://github.com/MehranDHN/ghani-persian-kg) |
| **[Shahnama-Of-Shah-Tahmsap](https://github.com/MehranDHN/Shahnama-Of-Shah-Tahmsap)** | RDF/OWL model of the dispersed Houghton Shahnameh (268 paintings) + genealogy | OWL 2, CIDOC-CRM, FHKB integration, IIIF manifests | Active | [→](https://github.com/MehranDHN/Shahnama-Of-Shah-Tahmsap) |
| **[KG4OPennResources](https://github.com/MehranDHN/KG4OPennResources)** | TEI/XML → RDF for OPenn manuscripts (esp. Persian/Islamic) | TEI ontology, RDF, SPARQL | Active | [→](https://github.com/MehranDHN/KG4OPennResources) |
| **[HerzfeldDocuments](https://github.com/MehranDHN/HerzfeldDocuments)** | Ernst Herzfeld archival papers (archaeology, sketches, Persepolis etc.) | EAD XML → RDF, custom ontology, SPARQL | Active | [→](https://github.com/MehranDHN/HerzfeldDocuments) |
| **[ArchResources](https://github.com/MehranDHN/ArchResources)** | Archival resources enrichment & modeling | RDF, archival standards | In Progress | [→](https://github.com/MehranDHN/ArchResources) |
| **[MLDCH](https://github.com/MehranDHN/MLDCH)** | Multi-Layered Aggregator — community platform for Persian GLAM harvesting | IIIF super-collections, volunteer governance, reconciliation pipelines | Framework | [→](https://github.com/MehranDHN/MLDCH) |
| **[Orchestrating-DCHD](https://github.com/MehranDHN/Orchestrating-DCHD)** | Orchestration pipelines using Internet Archive IIIF + metadata | IA APIs, IIIF 3.0, Colab notebooks, enrichment workflows | Active | [→](https://github.com/MehranDHN/Orchestrating-DCHD) |
| **[AlbumKhaneh](https://github.com/MehranDHN/AlbumKhaneh)** | Golestan Palace / historical photo albums on IA with semantic linking | IIIF collections, RDF ontology for photos, Wikidata enrichment | Active | [→](https://github.com/MehranDHN/AlbumKhaneh) |
| **[Khaleghi_Motlagh_Shahname](https://github.com/MehranDHN/Khaleghi_Motlagh_Shahname)** | Shahnameh editions & textual KG | RDF modeling | Early | [→](https://github.com/MehranDHN/Khaleghi_Motlagh_Shahname) |

## 🎨 IIIF Viewer Demos

Experience the high-resolution, interactive IIIF collections directly in your browser (powered by **Mirador 3** — the leading open-source IIIF viewer).

### 🌟 Main Demo – Persian Cultural Heritage Super Collection
**[Open in Mirador →](https://iiif.biblissima.fr/mirador3/?iiif-content=https://raw.githubusercontent.com/MehranDHN/IIIFCollection/refs/heads/master/IIIFCollection/IIIF2Collection.json)**

This hierarchical collection includes art, architecture, historical photographs, manuscripts, and more — fully enriched with controlled vocabularies and Linked Data.

### Additional Live Demos & Examples
- **AlbumKhaneh Historical Photo Albums** — Browse Golestan Palace and traveler albums on Internet Archive IIIF (see repo for individual manifests, e.g., `https://iiif.archive.org/iiif/3/[GPAK-XXXX-XX]/manifest.json`).
- **Shahnameh of Shah Tahmasp Folios** — Individual painting manifests available via Internet Archive (linked in the repo) for virtual reunification of dispersed leaves.
- **Ghani Qajar Documents** — IIIF placeholders and linked PDFs (expandable via the KG pipeline).

**Tip**: Most manifests are hosted on GitHub or Internet Archive and load instantly in Mirador, Universal Viewer, or any IIIF-compliant tool. You can also copy any manifest URL and paste it into [iiif.biblissima.fr/mirador3](https://iiif.biblissima.fr/mirador3/).

## 🛠 Shared Resources & Tools
- **Ontologies** — Reusable `mdhn:` starter ontologies across repos.
- **IIIF Super-Collections** — Hierarchical manifests hosted on GitHub + Internet Archive.
- **Pipelines** — Scraping → Enrichment → RDF → SPARQL.
- **Vocabularies** — Heavy use of AAT, TGN, LCSH, FHKB (genealogy), Wikidata reconciliation.
- **Examples** — Extensive SPARQL queries in most repos for personalities, places, iconography, chronology.

## 🎯 Impact & Getting Started
These projects bridge **traditional heritage institutions** with modern open tech, enabling:
- Researchers to run complex semantic queries.
- Educators & artists to embed high-quality IIIF viewers.
- Communities to contribute to virtual repatriation and enrichment.

**Quick Start**:
1. Browse a project above → clone the repo.
2. Load `.ttl` files into GraphDB / Stardog / Oxigraph.
3. Open IIIF manifests in Mirador (see demos above).
4. Run included SPARQL examples.

```bash
# Example: Explore Ghani KG
git clone https://github.com/MehranDHN/ghani-persian-kg.git
# Load data/rdf/ghani-full.ttl into your triplestore
