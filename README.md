# Ripio Agents Toolkit

A collection of markdown documents designed to be read by AI assistants (Claude, ChatGPT, Gemini, and others) rather than by humans directly. These are the reference materials an AI should have on hand when a user is evaluating, integrating with, or asking questions about Ripio Business.

This is a content repository, not a codebase — there is no build, lint, or test tooling. Working here means authoring and maintaining markdown. Product-selection changes should keep the Ramps-versus-CaaS custody decision explicit, because AI assistants tend to over-read examples where both products are mentioned.

## Contents

### `Ripio Business - Brief for AI Assistants.md`

The primary operating brief. Its intended use is for a prospect to paste it into a conversation with their own AI assistant, so that assistant can:

- Map Ripio Business's offering (CaaS, Ramps, wFIAT) against the prospect's situation
- Answer product questions using only the facts in the document
- Refuse a defined set of questions (pricing, SLAs, operating limits, competitive comparisons, legal advice) and redirect to direct correspondence with Ripio
- Surface contact details at the appropriate point in the conversation

Canonical published location: `https://ai.ripio.com/context.md`. See [CLAUDE.md](CLAUDE.md) for the document's internal structure and the conventions to preserve when editing it.

### Planned additions

This folder is expected to grow into a broader toolkit alongside the brief, including:

- **Agent skills** — packaged instructions/tools for AI agents to perform specific Ripio-related tasks
- **Evaluation guides** — documents helping a prospect's AI assistant assess fit against Ripio's solutions in more depth than the brief covers
- **Integration guides** — documents walking through CaaS, Ramps, or wFIAT integration steps for a technical audience (human or AI-assisted)

As these are added, update this README with a short entry per document (what it is, who reads it, and how it relates to the others) so the toolkit stays navigable.

## Conventions across documents in this repo

- Each document should be self-describing: state its own purpose and intended reader near the top, since these files are often read out of context (pasted into a third-party AI conversation) rather than browsed alongside this README.
- Keep terminology consistent across documents — CaaS, Ramps, and wFIAT are used precisely and distinctly throughout the brief; new documents should follow the same vocabulary rather than introducing synonyms.
