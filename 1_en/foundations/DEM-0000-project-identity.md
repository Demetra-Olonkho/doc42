# DEM-0000 — Project Identity and Foundational Decisions

Version: 0.1 (Draft)

Status: Accepted

---

# 1. Purpose

This document records the foundational decisions reached during the initial conceptual design phase of the project.

Its purpose is to preserve the original vision, terminology, naming conventions and project identity before the beginning of architectural and implementation work.

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

The short name may be used in source code, repositories, documentation and public communication.

---

# 3. Project Vision

Demetra Olonkho is a universal knowledge management platform designed for fictional worlds, literary universes, tabletop role-playing games, encyclopedic projects and other structured knowledge domains.

The project is not a worldbuilding tool, wiki engine, campaign manager or database of characters.

Instead, it is conceived as a knowledge-centric platform whose primary concern is the representation, provenance, evolution and reconciliation of knowledge.

---

# 4. Architectural Position

Demetra Olonkho is an independent project.

Other systems may consume its data and services.

Examples include:

* Publishing Pipeline systems;
* Virtual Tabletop systems (VTT);
* Wiki engines;
* Documentation systems;
* External APIs;
* Knowledge portals.

These systems are consumers of Demetra rather than parts of its core.

---

# 5. Core Conceptual Principles

The project is based on the following assumptions.

## 5.1 Knowledge-Centric Architecture

The system manages knowledge rather than objects.

The primary focus is not:

```
Character
Location
Organization
```

but:

```
Knowledge about Characters
Knowledge about Locations
Knowledge about Organizations
```

## 5.2 Assertion-Centric Model

Assertions are considered the fundamental unit of knowledge.

Assertions describe facts, claims, statements, interpretations or hypotheses.

## 5.3 Provenance Matters

Every piece of knowledge should be traceable to its source.

Knowledge without provenance is considered incomplete.

## 5.4 Multiple Truths May Coexist

Conflicting statements may coexist.

The system must preserve competing assertions rather than forcing premature resolution.

## 5.5 Language Neutrality

The knowledge model itself is language-neutral.

No language has a privileged position inside the model.

---

# 6. Symbolic Architecture

The project adopts a symbolic naming system in which major components receive meaningful names.

## Demetra

Represents:

* cultivation of knowledge;
* preservation of knowledge;
* dissemination of knowledge;
* development of knowledge.

Demetra is the name of the platform as a whole.

## Olonkho

Represents:

* knowledge lineage;
* transmission of knowledge;
* living tradition;
* provenance of knowledge.

Olonkho is the name of the knowledge model.

Provisional name:

```
Olonkho Knowledge Model
```

## Irida

Represents:

* exchange;
* communication;
* transfer.

Irida is reserved for the integration and exchange layer.

Provisional name:

```
Irida Exchange Layer
```

## Irina

Represents:

* reconciliation;
* coexistence;
* peace between competing interpretations.

Irina is reserved for the subsystem responsible for canon management, conflict handling and reconciliation.

Provisional name:

```
Irina Reconciliation Engine
```

---

# 7. Naming Principles

Project components should preferably receive meaningful proper names derived from:

* mythology;
* historical figures;
* cultural traditions;
* literary heritage.

Names should reflect the role of a component rather than its implementation details.

Preferred pattern:

```
Meaning → Function → Name
```

Avoid purely technical names where possible.

---

# 8. Language Policy

All languages are equal participants within the knowledge model.

For project governance and development:

First Working Language:

```
Russian
```

Second Working Language:

```
English
```

The choice of working languages does not imply any privilege inside the knowledge model itself.

---

# 9. Strategic Goal

The project is intended to become a reusable platform available to a broad community of users.

The architecture should therefore prioritize:

* extensibility;
* interoperability;
* transparency;
* long-term maintainability;
* multilingual support;
* domain independence.

---

# 10. Status

The following questions are considered resolved:

* Project identity;
* Project naming;
* Naming principles;
* Symbolic architecture;
* Language policy;
* Position relative to Publishing Pipeline and VTT projects.

The following questions remain open:

* Repository structure;
* Documentation structure;
* Licensing;
* Extension model;
* Storage architecture;
* Public API;
* Versioning model.

End of document.
