# Naming

This document defines canonical names and identifiers used by the ANHQV × The Sims 2 Preservation Project.

Consistent naming protects links, provenance, searchability, and institutional memory.

## Project Name

**Canonical name:** ANHQV × The Sims 2 Preservation Project  
**Canonical short name:** `ANHQV-TS2`  
**Project nickname:** *Aquí Sims Hay Quien Viva*  
**Recommended GitHub repository name:** `anhqv-ts2-preservation-project`

`ANHQV` abbreviates *Aquí no hay quien viva* and refers to the television series. `ANHQV-TS2` refers to the project.

*Aquí Sims Hay Quien Viva* is the project's affectionate public nickname. It may appear in headings, descriptions, videos, and community material, but the canonical title and short name should remain available wherever ambiguity matters.


## Series and Game Titles

Use:

- *Aquí no hay quien viva* on first formal mention;
- `ANHQV` after the title is established;
- *The Sims 2* for the game;
- `Sims 2` only where the shorter form reads naturally.

Use Spanish diacritics whenever the format supports them.

## Desengaño 21

Use **Desengaño 21** in prose and paths.


## Contributor Names and Identifiers

| Display name | Contributor ID | Identity |
|---|---|---|
| lcd97 | `ANHQV-HUM-001` | Human |
| Archivo 21 | `ANHQV-AI-001` | Language-model contributor |

Use `lcd97` as the canonical display name. `LCD97` may be used stylistically.

Use `Archivo 21` as the persistent contributor identity. `ChatGPT` describes an implementation family and does not uniquely identify a project contributor.

Contributor IDs use:

```text
ANHQV-[IDENTITY]-[NUMBER]
```

Current identity codes:

- `HUM` — human;
- `AI` — artificial-intelligence contributor.

Additional codes should be documented before use.

## Experiment Identifiers

Experiments use an uppercase prefix and three digits:

```text
EXP001
EXP002
EXP003
```

The canonical folder pattern is:

```text
EXP### - Descriptive Name
```

Runs use:

```text
EXP001-R01
EXP001-R02
```

Identifiers remain stable even when titles improve. Never reuse a number.

## Source and Related Identifiers

```text
SRC-[FORM]-[SHORT-NAME]-[NUMBER]
PERM-[SHORT-NAME]-[NUMBER]
CAP-[FORM]-[SHORT-NAME]-[YYYYMMDD]-[NUMBER]
```

Example:

```text
SRC-WEB-ANHQV-EU-001
```

## Dates and Times

Use ISO dates in filenames and metadata:

```text
YYYY-MM-DD
```

Use full timestamps where time matters, recording the time zone in the associated experiment or capture record.

## Files and Directories

- Use `.md` for Markdown.
- Use `README.md` for directory landing pages.
- Preserve numbered top-level directories until a planned migration replaces them.
- Prefer clear descriptive names over unexplained abbreviations.
- Avoid `final`, `latest`, `misc`, and `New folder`.
- Use lowercase hyphenated filenames for source records and machine-oriented records.
- Use British English in project-authored prose: `licence` as a noun, `license` as a verb.

## Versions

Use:

```text
1.0-draft
1.0
1.1
2.0
```

The Recruitment Pack is stored without a version number in its path. Its documents and review history record the active version.

## Renaming Policy

Before renaming an established file or directory:

1. identify inbound links and references;
2. preserve Git history where possible;
3. update indexes and records;
4. add a changelog entry when discoverability or compatibility changes;
5. avoid bundling unrelated content changes into the same rename commit.

Correct names matter. Traceable history matters more.
