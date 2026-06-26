# DEM-P0001

# Entity Identification and Passport System

Status: Draft

Version: 0.1

---

# English Version

## 1. Purpose

This document defines a preliminary model for identification, description, and interconnection of entities within the Demetra Olonkho project.

The document is a draft intended to support discussion and future standardization.

---

## 2. Background

During the design of Demetra Olonkho it became clear that the system must operate not only with physical artifacts such as files and documents, but also with logical constructs such as topics, concepts, requirements, decisions, and relationships.

Therefore, a unified model is required.

---

## 3. Core Principles

### 3.1 Entity

An Entity is any object within the knowledge model that can be identified, described, and linked to other objects.

Each entity shall possess:

* an identifier;
* a type;
* a lifecycle state;
* attributes;
* relationships.

---

### 3.2 Physical Entity

A Physical Entity has a direct representation in an information carrier.

Examples:

* Discussion Space;
* Discussion;
* Message;
* Document;
* File;
* Repository.

---

### 3.3 Logical Entity

A Logical Entity exists as a result of interpretation, analysis, or structuring of information.

Examples:

* Topic;
* Thread;
* Concept;
* Requirement;
* Decision;
* Term;
* Relation.

---

### 3.4 Equality of Entities

Physical and logical entities are equal participants in the knowledge model.

Physical existence does not imply greater importance.

---

## 4. Entity Identifiers

Every entity shall possess a unique identifier.

Identifiers belong to entities rather than their representations.

Multiple representations may exist for a single entity while preserving a single identifier.

---

## 5. Entity Passport

An Entity Passport is a standardized description of an entity.

A passport is not an entity itself.

A passport is a documented representation of an entity.

Its purpose is to provide:

* identification;
* description;
* state information;
* relationship information.

---

## 6. Entity Types and Document Types

Entity types and document types shall be treated as distinct categories.

Entity type examples:

* PROJECT;
* ORGANIZATION;
* DISCUSSION;
* TOPIC;
* THREAD;
* DOCUMENT;
* PERSON.

Document type examples:

* PASSPORT;
* REGISTRY;
* SPECIFICATION;
* REPORT;
* LOG.

---

## 7. Knowledge Provenance

Knowledge provenance is considered a fundamental principle.

Within discussion environments, the Message is the primary unit of knowledge origin.

Topics, concepts, requirements, decisions, and other logical entities may be derived from one or more messages.

---

## 8. Discussion Structure

Discussions are considered collections of messages.

Topics and threads are not message containers.

Instead, they are logical entities identified across sets of messages.

A single message may belong to multiple topics and threads simultaneously.

---

## 9. Preliminary Model

Entity

↓

Identifier

↓

Passport

↓

Relations

↓

Representations

---

## 10. Self-Application

Demetra Olonkho is considered one of the first consumers of its own knowledge model.

Project documentation and design artifacts may adopt this model before a software implementation exists.
