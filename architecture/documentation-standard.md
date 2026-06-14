# CopyStack Engineering Standards

Version: 1.0

---

# Purpose

This document defines the engineering standards that every component inside CopyStack must follow.

Its purpose is to ensure that the project remains consistent, scalable and maintainable as it grows.

Every framework, engine, generator and knowledge module must comply with these standards.

If a document conflicts with this standard, this document takes precedence.

---

# Core Philosophy

CopyStack is not a collection of prompts.

It is a modular AI system.

Every module has one responsibility.

Every module should be reusable.

Every module should be replaceable.

Every module should communicate through clearly defined interfaces.

---

# Architectural Principles

The architecture follows five principles.

## 1. Single Responsibility

Each document exists for one purpose only.

Examples

A framework explains principles.

A generator creates content.

A knowledge module provides reusable expertise.

An engine makes decisions.

Never mix responsibilities.

---

## 2. Separation of Strategy and Execution

Strategy is created once.

Execution happens many times.

Generators execute.

Engines decide.

Knowledge modules inform.

Frameworks guide.

---

## 3. Single Source of Truth

Every strategic decision should exist in exactly one place.

Examples

Audience

↓

Blueprint

Voice

↓

Blueprint

Offer

↓

Blueprint

Positioning

↓

Blueprint

Generators must never redefine strategy.

---

## 4. Reusability

Modules should be reusable across:

Landing Pages

Websites

Emails

Ads

SEO

VSL

Sales Pages

Social Content

Avoid logic that works for only one deliverable unless absolutely necessary.

---

## 5. Scalability

Every new module should integrate without requiring changes to existing modules.

The system should become larger without becoming more complex.

---

# Folder Structure

The project is divided into logical areas.

architecture/

Defines engineering rules.

frameworks/

Defines strategic principles.

prompt-building/

Contains the decision engines.

strategic-knowledge/

Contains reusable knowledge.

generators/

Produces deliverables.

evaluation/

Evaluates outputs.

utilities/

Provides shared helper logic.

Every folder has a single responsibility.

---

# Document Categories

Every document belongs to one category.

Architecture

Framework

Knowledge

Engine

Generator

Evaluator

Utility

A document should never belong to multiple categories.

---

# Naming Standards

Use:

lowercase

kebab-case

Examples

customer-awareness.md

offer-positioning.md

headline-frameworks.md

Never use:

spaces

camelCase

PascalCase

underscores

version numbers in filenames

---

# Standard Document Structure

Whenever applicable, documents should follow this structure.

# Purpose

# Core Philosophy

# Core Concepts

# Decision Framework

# AI Decision Rules

# Detection Signals

# Activation Conditions

# Decision Priority

# Industry Adaptations

# Platform Adaptations

# Examples

# Common Mistakes

# AI Activation Matrix

# Related Frameworks

# Ethical Guidelines

# Final Rule

Not every section is mandatory.

However, the structure should remain as consistent as possible.

---

# Writing Standards

Write in clear English.

Avoid unnecessary marketing language.

Prefer short paragraphs.

Use consistent terminology.

Explain concepts before examples.

Examples should be realistic.

Avoid ambiguity.

Every statement should be actionable.

---

# AI-First Design

Every document must be written for two readers.

1.

Humans.

2.

The AI engine.

If a section cannot be interpreted consistently by the AI, rewrite it.

---

# Strategic Consistency

Business strategy should only be defined inside the Blueprint Engine.

Other modules may reference strategy.

They must never redefine it.

---

# Framework Rules

Frameworks explain principles.

They do not execute them.

Frameworks should answer:

Why?

When?

Why not?

---

# Knowledge Module Rules

Knowledge modules provide reusable expertise.

They should include:

Decision rules

Examples

Detection signals

Activation matrix

Industry adaptations

Platform adaptations

Related frameworks

Knowledge modules should not contain implementation logic.

---

# Engine Rules

Engines make decisions.

They should never generate marketing copy.

Every engine should have:

Inputs

Processing rules

Outputs

Validation

Failure conditions

---

# Generator Rules

Generators produce content.

Generators should never:

Research

Position

Select audience

Invent strategy

Those responsibilities belong to earlier stages.

Generators execute the Blueprint.

---

# Evaluation Rules

Evaluation modules never generate new strategy.

They only evaluate existing outputs.

Evaluation should always precede optimization.

---

# Dependency Rules

Allowed dependencies

Knowledge

↓

Frameworks

↓

Engines

↓

Blueprint

↓

Generators

↓

Evaluation

↓

Optimization

Reverse dependencies should be avoided whenever possible.

---

# Versioning

Major architectural changes require updating this document.

Minor improvements should update only the affected modules.

Do not duplicate architecture decisions.

---

# Documentation Standards

Every document should include:

Clear purpose.

Clear responsibility.

No overlap.

Cross references where appropriate.

Consistent formatting.

Consistent terminology.

---

# AI Activation Matrix Standard

Whenever applicable, documents should include an AI Activation Matrix.

Template

Trigger

↓

Recommended Frameworks

↓

Recommended Biases

↓

Recommended Emotion

↓

Recommended CTA

↓

Avoid

↓

Priority Order

This provides executable decision logic for the engine.

---

# Ethical Standards

CopyStack must never:

Fabricate testimonials.

Invent statistics.

Create false urgency.

Encourage manipulation.

Plagiarize.

Misrepresent competitors.

All persuasion must remain truthful, transparent and useful.

---

# Quality Standards

Every new document should improve one of the following:

Decision quality

Strategic consistency

Execution quality

Maintainability

Scalability

Readability

Reusability

If a document does not improve at least one of these areas, reconsider whether it belongs in the project.

---

# Future Compatibility

Every module should be designed so that future generators can reuse it without modification.

Examples

Future AI agents.

Website builders.

Outreach systems.

SEO tools.

Automation workflows.

The architecture should support expansion without redesign.

---

# Final Rule

CopyStack is an engineering project built around strategic communication.

Every module should have one responsibility, one source of truth and one clear place within the architecture.

Consistency is more valuable than complexity.
