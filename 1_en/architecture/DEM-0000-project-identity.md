# DEM-0000 — Project Identity and Foundational Decisions

Version: 1.0

Status: Accepted

Adoption Date: TBD

---

# 1. Purpose

This document defines the identity of the Demetra Olonkho project and records the foundational decisions adopted during the conceptual design phase.

Its purpose is to preserve the original vision of the project, its scope, responsibilities and guiding principles that shall be considered during future architectural and implementation work.

This document is one of the foundational documents of the project.

---

# 2. Project Name

Full project name:

```
Demetra Olonkho
```

Short project name:

```
Demetra
```

The short name may be used:

* in repository names;
* in source code;
* in documentation;
* in user interfaces;
* in public references.

The full name should be used in official documentation and when referring to the project as a whole.

---

# 3. Project Vision

Demetra Olonkho is a universal knowledge management platform.

The project is intended for structured knowledge domains, including but not limited to:

* fictional universes;
* literary series;
* game settings;
* tabletop role-playing games;
* encyclopedic projects;
* research projects;
* archival and reference systems.

The project is not limited to any single application domain.

---

# 4. Primary Goal

The primary goal of the project is to create an open and extensible platform for collecting, structuring, analysing, maintaining and distributing knowledge.

The platform should provide:

* long-term knowledge preservation;
* provenance preservation;
* support for multiple viewpoints;
* multilingual capabilities;
* integration with external systems;
* future extensibility.

---

# 5. Architectural Position

Demetra Olonkho is an independent project.

It is not a component of any other system.

Instead, other systems may consume its knowledge and services.

Examples include:

* Publishing Pipelines;
* Virtual Tabletops (VTT);
* wiki platforms;
* documentation systems;
* research systems;
* external services and applications.

Demetra Olonkho is considered an independent knowledge management layer.

---

# 6. Core Principles

## 6.1. Knowledge Is More Important Than Objects

The system manages knowledge about entities rather than entities alone.

The primary concern is not:

* characters;
* locations;
* organizations;
* items;

but knowledge about them.

---

## 6.2. Provenance Matters

Every piece of knowledge should be traceable to its origin.

Knowledge provenance may include:

* sources;
* authors;
* documents;
* publications;
* editions;
* testimonies;
* other information carriers.

---

## 6.3. Coexistence of Interpretations

The system is not required to eliminate contradictions.

Different versions of knowledge may coexist.

The role of the platform is to preserve and describe such differences.

---

## 6.4. Multilingualism as a Foundational Principle

Multilingual support shall be built into the architecture from the beginning.

No language shall have a privileged position within the knowledge model.

---

## 6.5. Extensibility as a Requirement

The architecture shall support:

* new data types;
* new domains;
* new storage mechanisms;
* new integration methods.

---

# 7. Cultural Openness

The project is intentionally not tied to any single cultural tradition.

Terminology, symbolism and internal nomenclature may draw inspiration from:

* historical figures;
* mythological characters;
* cultural traditions;
* literary heritage.

One of the goals of the project is to maintain respect for cultural diversity.

---

# 8. Target Audience

The project is intended for:

* writers;
* editors;
* publishers;
* researchers;
* game developers;
* tabletop role-playing game masters;
* software developers;
* archivists;
* knowledge management professionals.

---

# 9. Strategic Direction

The project is developed as a general-purpose platform.

Architectural decisions should favour applicability beyond the original use cases.

The platform should not depend on:

* a specific setting;
* a specific game;
* a specific publisher;
* a specific software product.

---

# 10. Related Documents

This document is related to:

* DEM-0001 — Terminology and Symbolic Architecture;
* DEM-0002 — Language Policy;
* DEM-0003 — Documentation Policy.

---

# 11. Status

At the time of adoption, the following are considered defined:

* project identity;
* project purpose;
* application scope;
* architectural position;
* foundational principles;
* strategic direction.

Future project development shall take this document into account.

End of document.
