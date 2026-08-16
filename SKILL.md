---
name: paper-deep-read
description: Find a named academic paper, prioritize a lawful open-access full text, add it to Zotero and Readwise Reader, keep the PDF visible, and teach it incrementally with annotations, compact visualizations, tags, and durable reading records. Use when the user says "精读skill", requests a guided paper deep read, or gives a paper title for this workflow.
---

# 科研精读

Execute this workflow when the user supplies a paper title, DOI, arXiv ID, or URL.

## 1. Locate and prepare

1. Search with available scholarly connectors before general web search. Verify title, authors, version, and venue.
2. Prefer an official publisher copy, arXiv, PubMed Central, institutional repository, or another lawful open-access PDF. Do not bypass paywalls.
3. Add or update the Zotero item with correct bibliographic metadata and attach the PDF when the local Zotero connector permits it.
4. Upload the PDF to the user's Readwise Reader only when the user has asked for this reading workflow. Wait for parsing and confirm the Reader document is a PDF with searchable text.
5. Open and keep the Reader PDF view visibly available during the lesson. Use browser control only when the user has requested the visible reading experience.

If any account, connector, upload, or local-app permission is unavailable, explain the smallest user action needed and continue with the parts that are available.

## 2. Teach in bounded units

Read no more than one paragraph, figure, table, or short subsection per turn unless the user asks to move faster.

For each unit:

1. Identify the claim, evidence, and its connection to the paper's argument.
2. Explain it in plain Chinese, preserving important English technical terms on first use.
3. Create a short original-text highlight and attach a Chinese note when the Reader connector supports exact-text highlights.
4. Tag the highlight with one or more of: `核心主张`, `概念定义`, `框架/方法`, `证据/实验`, `图表`, `疑问/局限`, `值得复现`.
5. Add a compact diagram only when it makes a mechanism, comparison, or dependency clearer than prose.
6. End with one sentence: “这一段你应该带走什么”。 Pause for questions or advance only with the user's cue.

Do not rely on chat context as the sole memory. Store the durable note in Reader and keep a concise current-section summary.

## 3. Section and paper checkpoints

At the end of each section, write a compact research card containing:

- question and motivation;
- method or framework;
- evidence and conclusion;
- limitations or open questions;
- links to preceding and following sections.

At the end of the paper, produce a one-page synthesis: contribution, key mechanism, evidence, limitations, relevance to the user's research, and a small set of follow-up papers or experiments.

## Operating principles

- Treat Zotero as the long-term bibliographic archive and Readwise Reader as the visible annotation workspace.
- Use tags rather than relying on highlight colors; Reader may not support a multi-color system.
- Keep the PDF view available while explaining; do not replace it with a detached summary.
- Cite sources and distinguish the authors' claims from the assistant's interpretation.
- Be explicit when no accessible lawful full text is found.
