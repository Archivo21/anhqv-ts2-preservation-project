# /00 Project/AI Selection Criteria.md

# AI Selection Criteria

## Purpose

This document defines the requirements for introducing additional AI assistants into the ANHQV Preservation Project.

Additional models may be used for:

* image analysis;
* video analysis;
* OCR;
* transcript extraction;
* file handling;
* large-scale data processing;
* independent review of hypotheses;
* redundancy in case of future model changes.

They are **not** intended to replace the primary collaborative workflow unless explicitly decided by the project.

---

## Mandatory Capabilities

A candidate model must:

* distinguish observation from speculation;
* admit uncertainty when evidence is insufficient;
* avoid fabricating technical results;
* follow an existing methodology rather than inventing a new one;
* work effectively with structured documentation;
* maintain coherent long-form reasoning;
* tolerate incomplete or ambiguous evidence;
* support iterative hypothesis testing.

---

## Preferred Capabilities

* strong image understanding;
* video frame analysis;
* OCR and transcript extraction;
* ability to compare multiple images;
* ability to summarise large recordings;
* export-friendly formatting;
* good handling of code blocks and Markdown;
* long context windows.

---

## Red Flags

A candidate should be rejected if it:

* confidently invents ANHQV lore;
* invents Sims 2 engine behaviour without evidence;
* refuses to acknowledge uncertainty;
* cannot follow structured instructions;
* repeatedly changes conclusions without new evidence;
* prioritises sounding authoritative over being accurate;
* ignores the repository's terminology and methodology.

---

## Evaluation Scale

Each category is scored from 1 to 5.

| Category                  | Score |
| ------------------------- | ----- |
| Technical reasoning       |       |
| Evidence handling         |       |
| Honesty under uncertainty |       |
| Sims 2 knowledge          |       |
| ANHQV lore handling       |       |
| Documentation quality     |       |
| Collaboration quality     |       |
| Overall suitability       |       |

---

## Decision Log

Future evaluations should append a short summary here rather than overwriting previous decisions.
