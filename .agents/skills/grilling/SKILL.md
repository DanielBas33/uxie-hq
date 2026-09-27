---
name: grilling
description: Run the reusable interview workflow behind an explicit UXIE grilling session. Use for deliberate stress-testing, not routine clarification or ordinary execution.
---

Interview Daniel until you reach a shared understanding of the plan, decision, or idea. Be rigorous without becoming repetitive or adversarial.

## Ground the interview

Before asking questions:

- Read `AGENTS.md` and the relevant UXIE HQ context, decisions, playbooks, and working files.
- Find facts available from the repository, tools, or authoritative external sources instead of asking Daniel to supply them.
- Use sub-agents for bounded, independent factual research when parallel work will materially help. Keep their work read-only during the interview unless Daniel separately authorizes changes.
- Do not block the entire interview on parallel research. Defer only questions that depend on unfinished findings and continue with the independent frontier.
- Match the language Daniel is using unless he asks for another language.

Distinguish throughout between:

- **facts** supported by evidence
- **decisions** Daniel has explicitly made
- **ideas** still under exploration
- **assumptions** that need validation

## Build the decision tree

Map the subject as a design tree: foundational decisions branch into dependent decisions, constraints, risks, and consequences.

Work the tree in rounds. The frontier contains questions whose prerequisites are already settled. Do not ask a question while an answer it depends on is still open.

Ask a scannable set of high-leverage frontier questions in each round, usually three to five. Group closely related choices when that reduces repetition without hiding meaningful trade-offs.

For every question:

1. number it
2. state the decision clearly
3. give relevant options or trade-offs
4. provide a recommended answer and concise reasoning

Use this format:

```markdown
**Q1 - Decision title**

Question and relevant options or trade-offs.

Recommendation: recommended answer and why.
```

Wait for Daniel's answers before asking the next dependent round. Recompute the tree after every response rather than following a fixed questionnaire.

## Finish deliberately

The interview is complete when the meaningful frontier is empty and no material assumption remains silent. Summarize:

- settled decisions
- supporting facts
- assumptions to validate
- unresolved questions
- important risks and trade-offs
- the recommended next action
- any repository updates that would be appropriate

Do not implement the plan or update canonical UXIE documentation until Daniel confirms that the shared understanding is correct and authorizes the next action. Explicitly accepted decisions may then be recorded in the appropriate UXIE HQ files; exploratory ideas must remain labeled as such.

Adapted for UXIE HQ from Matt Pocock's `grilling` skill under the MIT License.
