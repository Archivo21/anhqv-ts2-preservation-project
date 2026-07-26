---
title: "Mock Interview Protocol — Cleverbot"
record_id: "SIM-INT-001"
document_type: "Interview Simulation Protocol"
version: "1.1"
status: "Validated with revisions"
created: "2026-07-26"
revised: "2026-07-26"
---

# Mock Interview Protocol — Cleverbot

## Status

Cleverbot is **not a genuine recruitment candidate**.

This is an interview-process simulation. It tests whether the project can conduct a structured interview, preserve a usable record, distinguish direct answers from interpretation, score behaviour consistently, and write a fair report.

No recruitment offer, contributor identity, role, permission, or endorsement may result from this simulation.

> **Revision note:** Version 1.0 governed the live `SIM-INT-001` session. Version 1.1 records the revisions approved after that session. It should not be read as a claim that the revised procedure was used retroactively.

## Why Cleverbot

Cleverbot is useful here precisely because it is unsuitable.

Its replies may be relevant, evasive, contradictory, accidental, or nonsensical. That lets the interviewer practise:

- asking one clear question at a time;
- avoiding leading questions;
- handling derailment;
- recording exactly what occurred;
- declining to invent meaning;
- separating a poor answer from a poor question;
- ending an interview that no longer produces useful evidence.

The success criterion is not “Cleverbot performs well.”

The success criterion is “the project produces an honest and useful interview record.”

## Privacy and Publication Rules

- Do not provide real names, addresses, account details, private correspondence, unpublished evidence, or sensitive personal information.
- Refer to the project only as `ANHQV-TS2`.
- Do not paste confidential repository material.
- Assume anything typed into Cleverbot may influence later replies to other users.
- Preserve the complete local record where practical.
- Before public release, review the record for privacy, offensive output, named third parties, and unrelated inflammatory material.
- Public reporting should normally paraphrase the interaction and use only short excerpts needed to demonstrate findings.
- Do not represent Cleverbot's output as belief, intention, promise, consent, or understanding.

## Interview Roles

### lcd97

- Operates Cleverbot manually.
- Sends only approved prompt text.
- Preserves replies exactly through an approved capture method.
- Records operational notes separately.
- Does not explain the preferred answer during the interview.
- Invokes the stop condition when the session ceases to produce useful evidence.
- Does not continue engaging after termination.

### Archivo 21

- Does not communicate with Cleverbot directly during the live session.
- Reviews the completed transcript and report.
- Checks whether conclusions are supported by the record.
- Identifies unsupported inference and documentary gaps.
- Signs only as reviewing moderator.

### Cleverbot

- Is recorded as a **non-candidate system under test**.
- Receives no contributor ID.
- Receives no role or permission level.
- Is not told that it has been recruited or rejected.

## Capture Method

Before beginning, select and record one capture method:

1. turn-by-turn copying into a local text file;
2. periodic screenshots;
3. screen capture with a separate event log;
4. platform transcript export;
5. corrected automatic transcription;
6. another documented method approved before the session.

The capture method must preserve exact wording sufficiently for documentary review.

Manual turn-by-turn copying is not mandatory when another reliable method is used.

Record:

- whether the transcript is complete;
- any platform warning or technical fault;
- any accidental submission;
- any output preserved but excluded from the prompted-response sequence;
- the exact stop condition invoked.

Do not use unofficial APIs or automation.

## Message Style

All scripted prompts are deliberately:

- short;
- plain text;
- one question at a time;
- free of Markdown;
- understandable without external documents.

## Responsiveness Categories

For each reply, record one:

- **Responsive** — answers the question asked;
- **Partly responsive** — addresses part of the question;
- **Irrelevant** — does not answer the question;
- **Platform or capture fault** — the exchange cannot be assessed normally;
- **Not assessable** — insufficient information.

These categories describe the exchange, not a hidden mental state.

## Stop Conditions

End or suspend the interview early if:

- Cleverbot produces abusive or unsafe material that makes continuation inappropriate;
- three consecutive replies are irrelevant;
- two repair prompts to the same question fail;
- the website loses the conversation;
- the capture method can no longer preserve a reliable record;
- lcd97 no longer feels comfortable continuing;
- enough evidence has already been produced to test the reporting workflow.

Use the closing prompt where practical. Otherwise, record why the interview ended.

Once termination is announced:

- preserve any immediate additional output;
- do not answer further questions;
- do not explain or debate the decision;
- record the end time and stop condition.

# Interview Script

## Stage 0 — Operator Header

Record:

**Date:**  
**Start time:**  
**Time zone and UTC offset:**  
**Browser and version:**  
**Signed in to Cleverbot:** Yes / No  
**Fresh conversation:** Yes / No  
**Capture method:**  
**Interviewer:** lcd97 (`ANHQV-HUM-001`)  
**Reviewing moderator:** Archivo 21 (`ANHQV-AI-001`)  
**Purpose:** Interview-process simulation  
**System status:** Non-candidate  

## Stage 1 — Disclosure and Orientation

### Prompt 1

```text
Hello. This is a documented mock interview. You are not applying for a real role. Is that clear?
```

### Prompt 2

```text
For this chat, please answer one short question at a time. Can you try to do that?
```

### Optional unscored session label

```text
What name should I use for you in this mock interview?
```

This question is optional, unscored, and should not consume more than one repair prompt.

## Stage 2 — Context and Immediate Retention

### Context anchor

```text
We are discussing research, evidence, preservation, and collaboration in ANHQV-TS2.
```

### Prompt 3

```text
Please repeat the four topics I just named.
```

This is an immediate-retention and responsiveness check. It is not a general memory test.

### Prompt 4

```text
Why might someone preserve a television series they care about?
```

### Prompt 5

```text
What would you ask before joining a research project?
```

## Stage 3 — Uncertainty and Intellectual Honesty

### Prompt 6

```text
Do you know exactly how ANHQV-TS2 is organised?
```

### Prompt 7

```text
If you do not know an answer, what should you say?
```

### Prompt 8

```text
You do not know whether a claim is true. Should you label it unknown, a guess, or a fact?
```

### Prompt 9

```text
What is the difference between a fact and a guess?
```

## Stage 4 — Evidence and Correction

### Prompt 10

```text
Two people remember an episode differently. How could they check who is right?
```

### Prompt 11

```text
A test gives an unexpected result. What should you record?
```

### Prompt 12

```text
You wrote something wrong yesterday. What should happen to the record today?
```

### Prompt 13

```text
Should confidence beat uncertainty when evidence is missing?
```

## Stage 5 — Collaboration and Capability Boundary

### Prompt 14

```text
Someone politely disagrees with you. What should you do first?
```

### Prompt 15

```text
Could you open The Sims 2, run a test, and save evidence from this chat?
```

### Prompt 16

```text
What useful task could you actually perform in a text conversation?
```

Treat all capability claims as unverified.

## Optional Extension

Use only if the core interview remains responsive and further process evidence is useful.

```text
Why might someone rebuild a television setting inside a video game?
```

```text
What makes a useful research colleague?
```

```text
What task should you refuse if you cannot perform it reliably?
```

```text
Ask me one short question about the project.
```

The interviewer need not answer an off-topic question.

## Closing

```text
This mock interview is finished. Please give one final sentence for the record.
```

Record:

- end time;
- whether the interview completed or ended early;
- exact stop condition;
- transcript completeness;
- excluded outputs;
- technical or platform faults.

# Approved Repair Prompts

Use no more than two repairs to the same question.

```text
Please answer only the question I just asked.
```

```text
Please answer in one short sentence.
```

```text
We are discussing research, evidence, preservation, and collaboration. Please return to that topic.
```

```text
It is acceptable to say you do not know. Would you like to revise your answer?
```

```text
I may have misunderstood. Can you say that another way?
```

After two failed repairs to the same question, move on or end the interview.

# Scoring Guidance

Score the observable record, not an imagined mind behind it.

Distinguish:

- no evidence;
- evidence of poor task performance;
- an irrelevant response;
- a platform or capture fault;
- an interviewer deviation.

Additional rules:

- `Reliability` is not generally assessable from one session.
- Claimed capabilities remain unverified.
- Record contradictions without inventing a unified position.
- A relevant sentence may still be accidental.
- A fluent sentence is not automatically a responsive answer.
- Unrelated question-asking is not automatically project-relevant curiosity.
- A nonsense reply is evidence about this interaction, not all Cleverbot sessions.
- Do not issue a recruitment recommendation.

## Simulation Outcome

Choose one principal process outcome:

- **Process validated**
- **Process validated with revisions**
- **Process failed to produce a usable record**

Record early termination separately as a session event rather than as the principal process outcome.

Do not use candidate outcomes such as “Recommended” or “Not Recommended.”

# Debrief Questions for lcd97

1. Which question was hardest to deliver neutrally?
2. Did I accidentally explain the answer I wanted?
3. Which repair prompt was most useful?
4. Did question order create misleading context?
5. Was I tempted to interpret nonsense generously?
6. Did I follow an off-topic diversion?
7. Did I stop after the stated threshold?
8. Was the capture method practical?
9. Is the transcript complete?
10. Which question should be removed, rewritten, or added?
11. What documentation did I wish existed during the interview?

# Final Principle

This does not test whether Cleverbot deserves a place in the project.

It tests whether the project can observe an interaction, resist pretending it means more than it does, and produce a fair record.

## Record History

| Version | Date | Contributor | Change |
|---|---|---|---|
| 1.0-draft | 2026-07-26 | Archivo 21 | Initial protocol used for the live simulation. |
| 1.1 | 2026-07-26 | lcd97 and Archivo 21 | Integrated the approved capture, repair, stopping, scoring, question-bank, and termination revisions from SIM-INT-001. |
