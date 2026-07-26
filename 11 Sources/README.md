---
title: "Sources"
document_type: "Source Governance"
version: "1.0"
status: "Active"
---

# Sources

This directory records external material used to preserve, reconstruct, study, and simulate the world of *Aquí no hay quien viva* through *The Sims 2*.

It exists to answer five questions:

1. What is the source?
2. Why is it useful?
3. How reliable is it?
4. How may the project use it?
5. Where can a future researcher find or verify it?

A source record describes a source. It does not automatically endorse every claim contained within that source.

## Project Principle

ANHQV is the project's cultural subject and emotional centre.

*The Sims 2* is the medium, laboratory, and simulation system through which that world is reconstructed and investigated.

The source system must accommodate both sides without treating either as secondary.

Examples include:

- broadcast episodes and official releases;
- scripts, interviews, press material, and production records;
- fan archives, community recollections, and specialist knowledge;
- game manuals, technical documentation, mods, and source code;
- live Sims 2 experiments and recorded observations;
- physical objects such as DVDs, magazines, packaging, and promotional material.

## Directory Structure

```text
11 Sources/
├── README.md
├── Registry.md
├── Records/
│   ├── README.md
│   ├── audiovisual/
│   ├── people/
│   ├── physical-media/
│   ├── print/
│   ├── software/
│   └── web/
│       ├── README.md
│       └── anhqv-eu.md
├── Templates/
│   ├── README.md
│   ├── source-record-template.md
│   ├── permission-record-template.md
│   └── archive-capture-template.md
└── Rights/
    ├── README.md
    ├── permissions/
    │   └── README.md
    └── licences/
        └── README.md
```

Archived copies of source material do not belong in this directory. Authorised or otherwise lawful captures should be stored separately under `Archive/` or another designated archive location, with the source and capture records linking to them.

## Source Classes

Source classes describe provenance, not quality.

### Primary Source

Material directly produced by the work, production, software, event, or person being studied.

Examples:

- an ANHQV episode;
- official credits;
- a Sims 2 executable or package file;
- an original interview;
- a recorded project experiment.

### Secondary Source

Material that analyses, summarises, catalogues, or interprets primary material.

Examples:

- a fan archive;
- an episode guide;
- an academic article;
- a technical tutorial;
- a retrospective.

### Tertiary or Discovery Source

Material mainly useful for locating other information or generating research leads.

Examples:

- indexes;
- unsourced lists;
- search results;
- community compilations;
- general encyclopaedia entries.

A source may occupy more than one class. Its record should explain how the project intends to use it.

## Evidence Status

A source record and an evidence claim are different things.

Registering a website confirms that the website exists and is relevant. It does not verify each statement published there.

Claims derived from sources should be labelled using one of the following statuses:

- **Unexamined** — recorded but not yet assessed.
- **Lead** — useful as a question or direction for research.
- **Unverified** — specific claim identified but not independently checked.
- **Partially verified** — some supporting evidence exists, but uncertainty remains.
- **Verified** — supported by sufficient identified evidence.
- **Contradicted** — reliable evidence conflicts with the claim.
- **Inconclusive** — investigated without a defensible conclusion.
- **Superseded** — replaced by a later, better-supported account.

## Reliability

Reliability is contextual.

A fan site may be excellent for locating a running joke and poor for establishing an exact broadcast chronology. A DVD may be authoritative about its own contents while differing from the original television transmission. A live game test may accurately describe one configured environment without proving universal Sims 2 behaviour.

Each record should identify:

- strengths;
- limitations;
- likely biases;
- temporal scope;
- required verification;
- known contradictions;
- technical or legal barriers.

Confidence should never be inferred from polished writing alone.

## Citation and Attribution

Each source-derived claim should identify, where applicable:

- source record ID;
- exact page, episode, chapter, timestamp, file, or object;
- author or operator;
- publication or capture date;
- access date;
- relevant edition, region, patch level, or configuration;
- whether the statement is quotation, paraphrase, observation, or inference.

Precise citations allow a future contributor to reproduce the path from source to conclusion.

## Rights and Preservation

Registration is not permission to copy.

Before storing or publishing source material, determine:

- who owns it;
- what licence applies;
- whether the project has explicit permission;
- whether third-party material is embedded;
- whether personal information or public comments require special treatment;
- whether preservation, quotation, or distribution is lawful in the intended context.

Permission and licence records belong under `Rights/`.

Archive-capture documentation belongs with the source governance records, while captured data itself belongs in the archive.

## Naming

Use lowercase filenames with hyphens for source records.

Examples:

```text
anhqv-eu.md
season-1-dvd-spain.md
the-sims-2-ultimate-collection.md
presidencia-interview-2026.md
```

Do not include dates in a source-record filename unless the date distinguishes the source itself. Capture dates belong in archive paths and capture records.

## Adding a Source

1. Copy `Templates/source-record-template.md`.
2. Assign a unique source record ID.
3. Describe the source and its project value.
4. Record reliability, verification, rights, and access notes.
5. Add it to `Registry.md`.
6. Link any permission, licence, or archive-capture records.
7. Update the record when material circumstances change.

## Review

A source record should be reviewed when:

- the source moves, disappears, or changes ownership;
- its legal terms change;
- a capture is created;
- permission is granted or withdrawn;
- a major claim is verified or contradicted;
- the project changes how it uses the source;
- a contributor identifies an important omission or error.

The source system exists to preserve provenance, not to create ceremonial paperwork. Records should be as detailed as the source requires and no more complicated than the research benefits justify.
