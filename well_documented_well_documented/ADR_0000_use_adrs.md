# ADR 0000: Use Architecture Decision Records

* Status: proposed
* Deciders: @jfahne
* Date: 2024-08-31

## Context and Problem Statement

As the Well Documented project begins, it is salient that decisions about documentation of 
the project itself are considered architectural decisions. Given that this project targets
creating a standard that improves on existing standards as one of its missions, the only way
to use an existing documentation standard for architectural decisions is to use one that is 
easy to change or integrate. What standard most approximates what a standard produced 
by this project may look like and is easy to extend, modify, or migrate from?

## Decision Drivers

* Need to document decisions about documentation standards
* Ability to extend, modify, or migrate from chosen standard
* Standard should be written in plain text

## Considered Options

* [Michael Ngyard's ADR Template](https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/locales/en/templates/decision-record-template-by-michael-nygard)
* [MADR](https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/locales/en/templates/decision-record-template-of-the-madr-project)
* Creating a new standard before beginning to document decisions

## Decision Outcome

Chosen option: "[MADR](https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/locales/en/templates/decision-record-template-of-the-madr-project)"
, because MADR is a good balance of sensibly verbose defaults and the ability to be simple and clean 
for smaller decisions. It is plain text by virtue of being markdown and can be evolved 
in the future readily as it is minimally prescriptive.

### Positive Consequences

* Easy to change or extend in the future
* Written in plain text as is desired for all project documents
* Has existing ecosystem of examples and tools to simplify writing 

### Negative Consequences

* Requires a future ADR to pull documents back towards produced standards
* It is a mutable record and relies on backrefs for superseding decisions.

