# Repository Guidelines

## Recording Policy

Record:

- first successful reproductions;
- unexpected behaviour;
- procedures that depend on movement or timing;
- evidence that cannot be adequately described with text alone;
- comparisons between ANHQV sources and reconstruction decisions;
- demonstrations intended for publication;
- failed attempts whose conditions may explain later results.

Do not routinely record:

- loading screens;
- repeated successful tests with no changed variable;
- ordinary gameplay unrelated to research;
- behaviour already documented unless testing a new condition.

## Raw and Published Media

Raw recordings are evidence. Public videos are edited publications.

They must not be treated as the same object.

Raw files should:

- remain unchanged;
- retain original filenames where practical;
- receive checksums and an inventory;
- remain outside ordinary Git history when large or private;
- have at least one independent backup when irreplaceable.

Published edits should:

- preserve the relevant evidential sequence;
- remove irrelevant private material;
- label cuts, speed changes, captions, overlays, and audio processing;
- identify the source recording;
- include an edit log;
- never replace the raw evidence.

## File Retention Categories

### Permanent

Irreplaceable evidence, milestone recordings, source permissions, canonical decisions, and release artefacts.

### Reference

Useful comparisons, benchmarks, working exports, and replaceable source copies.

### Working

Temporary recordings, caches, drafts, and intermediates that may be deleted after the relevant evidence and decisions are documented.

## Experiment Naming

Experiments use:

```text
EXP### - Descriptive Name
```

Examples:

```text
EXP001 - Two Click Foundations
EXP002 - Lightwell
```

Runs use:

```text
EXP001-R01
EXP001-R02
```

Do not reuse identifiers.

## Source and Evidence Links

A conclusion should link to the smallest useful evidence unit:

- episode and timestamp;
- experiment and run;
- source-record ID and page;
- file and checksum;
- image, frame, measurement, or package.

## GitHub Policy

The public GitHub repository should contain documentation, small rights-cleared assets, reviewable data, and publication artefacts.

Raw MKV and AVI recordings are excluded initially. Large binaries should use a documented release or preservation channel rather than being committed casually.

## Changes

Use Git history for ordinary development and the changelog for changes that affect project meaning, method, compatibility, or public use.
