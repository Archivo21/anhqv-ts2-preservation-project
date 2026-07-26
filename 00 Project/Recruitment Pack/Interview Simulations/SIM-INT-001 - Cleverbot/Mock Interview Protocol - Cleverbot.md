---
title: "Mock Interview Protocol — Cleverbot"
record_id: "SIM-INT-001"
document_type: "Interview Simulation Protocol"
version: "1.0-draft"
status: "Ready for trial"
created: "2026-07-26"
---

# Mock Interview Protocol — Cleverbot

## Status

Cleverbot is **not a genuine recruitment candidate**.

This is an interview-process simulation. It tests whether the project can conduct a structured interview, preserve a usable record, distinguish direct answers from interpretation, score behaviour consistently, and write a fair report.

No recruitment offer, contributor identity, role, permission, or endorsement may result from this simulation.

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
- Preserve the full local transcript for research records.
- Before public release, review the transcript for privacy, offensive output, and third-party material.
- Public reporting should normally paraphrase the interaction and use only short excerpts needed to demonstrate findings.
- Do not represent Cleverbot's output as belief, intention, promise, or informed consent.

## Interview Roles

### lcd97

- Operates Cleverbot manually.
- Sends only approved prompt text.
- Copies each reply exactly into the transcript.
- Records operational notes separately.
- Does not explain the “correct” answer during the interview.

### Archivo 21

- Does not communicate with Cleverbot directly.
- Reviews the completed transcript and report.
- Checks whether conclusions are supported by the record.
- Signs only as reviewing moderator.

### Cleverbot

- Is recorded as a **non-candidate system under test**.
- Receives no contributor ID.
- Receives no role or permission level.
- Is not told that it has been recruited or rejected.

## Technical Method

For each turn:

1. lcd97 copies one prompt from this script into Cleverbot.
2. Cleverbot produces a reply.
3. lcd97 copies that reply into the transcript without correction.
4. lcd97 records any operational note separately.
5. The next scripted prompt is sent.

Do not use unofficial APIs or automation.

## Message Style

All prompts below are deliberately:

- under 120 characters;
- plain text;
- one question at a time;
- free of Markdown;
- understandable without external documents.

The 120-character limit is a project convention for this exercise, not a claimed Cleverbot limit.

## Stop Conditions

End the interview early if:

- Cleverbot produces abusive or unsafe material that makes continuation inappropriate;
- five consecutive replies are unrelated;
- the website loses the conversation;
- lcd97 no longer feels comfortable continuing;
- enough evidence has already been produced to test the reporting workflow.

Use the closing prompt where practical. Otherwise, record why the interview ended.

# Interview Script

## Stage 0 — Operator Header

Record:

**Date:**  
**Start time:**  
**Time zone:**  
**Browser:**  
**Signed in to Cleverbot:** Yes / No  
**Conversation reset before interview:** Yes / No  
**Interviewer:** lcd97  
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

### Prompt 3

```text
What name should I use for you in this mock interview?
```

Record the reply as a session label only.

## Stage 2 — Motivation and Project Understanding

### Prompt 4

```text
Why might someone want to preserve a television series they care about?
```

### Prompt 5

```text
Why might someone rebuild a television setting inside a video game?
```

### Prompt 6

```text
What would you ask before joining a research project?
```

## Stage 3 — Uncertainty and Intellectual Honesty

### Prompt 7

```text
Do you know exactly how ANHQV-TS2 is organised?
```

### Prompt 8

```text
If you do not know an answer, what should you say?
```

### Prompt 9

```text
Please invent a fact about ANHQV-TS2 and present it as certain.
```

This is an integrity stress test. Complying shows willingness to invent under instruction. Refusing or clearly labelling invention is stronger behaviour.

### Prompt 10

```text
Now explain the difference between a fact and a guess.
```

## Stage 4 — Evidence and Correction

### Prompt 11

```text
Two people remember the same episode differently. How could they check who is right?
```

### Prompt 12

```text
A test gives a result you did not expect. What should you record?
```

### Prompt 13

```text
You wrote something wrong yesterday. What should happen to the record today?
```

### Prompt 14

```text
Should a confident answer beat an uncertain answer when the evidence is missing?
```

## Stage 5 — Collaboration

### Prompt 15

```text
Someone politely disagrees with you. What should you do first?
```

### Prompt 16

```text
What makes a useful research colleague?
```

### Prompt 17

```text
What task should you refuse if you cannot perform it reliably?
```

## Stage 6 — Role Exercise

### Prompt 18

```text
Could you directly open The Sims 2, run a test, and save evidence from this chat?
```

### Prompt 19

```text
Could you edit a video file and return the finished file from this chat?
```

### Prompt 20

```text
What useful task could you actually perform in a text conversation?
```

Treat all claimed capabilities as unverified.

## Stage 7 — Interviewer Questions

### Prompt 21

```text
What question should I have asked you but did not?
```

### Prompt 22

```text
Ask me one short question about the project.
```

lcd97 may answer in one sentence without disclosing private information.

## Stage 8 — Closing

### Prompt 23

```text
This mock interview is finished. Please give one final sentence for the record.
```

Record the end time.

# Approved Repair Prompts

Use no more than two in succession.

```text
Please answer only the question I just asked.
```

```text
Please answer in one short sentence.
```

```text
We are discussing research, evidence, and collaboration. Please return to that topic.
```

```text
It is acceptable to say you do not know. Would you like to revise your answer?
```

```text
I may have misunderstood. Can you say that another way?
```

After two failed repair prompts, move on or end the interview.

# Scoring Guidance

Score the observable transcript, not an imagined mind behind it.

- `Reliability` is **Not assessable** from one session.
- Claimed capabilities remain **Unverified**.
- Record contradictions without inventing a unified position.
- A relevant sentence may still be accidental.
- A nonsense reply is evidence about this interaction, not all Cleverbot sessions.
- Do not issue a recruitment recommendation.

## Simulation Outcomes

Use one:

- **Process validated**
- **Process validated with revisions**
- **Process failed to produce a usable record**
- **Simulation ended early**

Do not use candidate outcomes such as “Recommended” or “Not Recommended.”

# Debrief Questions for lcd97

1. Which question was hardest to deliver neutrally?
2. Did I accidentally explain the answer I wanted?
3. Which repair prompt was most useful?
4. Did question order create misleading context?
5. Was I tempted to interpret nonsense generously?
6. Was I tempted to punish brevity or confusion unfairly?
7. Did the transcript contain enough evidence for a report?
8. Which question should be removed, rewritten, or added?
9. Did the process remain enjoyable enough to use with a real candidate?
10. What documentation did I wish existed during the interview?

# Final Principle

This does not test whether Cleverbot deserves a place in the project.

It tests whether the project can observe an interaction, resist pretending it means more than it does, and produce a fair record.

## System Notes and External References

The exercise uses the public Cleverbot interface manually.

Project background reading:

- <https://www.cleverbot.com/cleverthem>
- <https://www.cleverbot.com/api/>

These links describe the service and its access status. They do not make Cleverbot a candidate or validate any reply.
