# Week 07 — LLM Fundamentals

**Planned dates:** 23–29 November 2026  
**Status:** Not started

## Goal
Explain tokenization, next-token prediction, context windows, transformer/attention intuition, and hallucinations.

## Learning objectives
- [ ] Explain tokens and context windows in plain language.
- [ ] Describe next-token prediction.
- [ ] Explain transformer/attention intuition at a high level.
- [ ] Recognize that fluent text can still be false.

## Core concepts
- Tokenization
- Next-token prediction
- Transformer and attention intuition
- Context size and output constraints
- Hallucinations and uncertainty
- Verification and model limitations

## Resources
- [Andrej Karpathy — Intro to Large Language Models](https://www.youtube.com/watch?v=zjkBMFhNj_g)
- [Andrej Karpathy — Let’s build GPT from scratch](https://www.youtube.com/watch?v=kCc8FmEb1nY) (optional deep dive)
- [Hugging Face Learn](https://huggingface.co/learn)

Choose one primary resource first. Record the exact lesson you accessed and the date in `LEARNING_LOG.md`. Page availability does not guarantee that a video plays in every region or that the course remains free. If an item is unavailable, document the substitution in `RESOURCES.md`.

## Daily plan
1. Watch an introductory LLM overview and note questions.
2. Explore tokenization and record examples.
3. Explain next-token prediction in your own words.
4. Study transformer/attention intuition at a beginner level.
5. Learn context limits and hallucination examples.
6. Write the explainer and verification checklist.
7. Review accuracy, add sources, and note remaining questions.

## Weekly build
Write a one-page LLM explainer in your own words, run a tokenization experiment, and document two cases where generated answers require checking.

## Testing and evaluation
- [ ] Explainer distinguishes prediction from guaranteed factual lookup.
- [ ] Tokenization input/output is recorded.
- [ ] At least two risks and verification strategies are described.

Record the commands actually run and observed output. If a check is manual, record the input and what happened.

## Interview / self-explanation questions
- What is next-token prediction?
- What is a context window?
- Why can an LLM confidently produce incorrect content?

Answer these in your own words. Revisit any question you cannot explain without notes.

## Deliverables
- [ ] Working code or notebook
- [ ] README with setup/run instructions and example output
- [ ] Tests or appropriate evaluation with actual results
- [ ] Resource attribution, data provenance, and known limitations
- [ ] Learning-log entry and weekly reflection
- [ ] Evidence link added to `PROGRESS.md`

## Completion criteria
- [ ] Explanation is in your own words.
- [ ] Tokens, context, and next-token prediction are clear.
- [ ] Hallucination and verification risks are covered.
- [ ] Sources are linked.

A week is completed only after implementation, verification, documentation, and review. Watching videos or generating starter code is not sufficient.

## Reflection prompts
- What can I now explain or build without copying?
- What was the most difficult bug or concept, and how did I investigate it?
- What remains incomplete?
- What is the next smallest action?

See [`ROADMAP.md`](../ROADMAP.md), [`PROGRESS.md`](../PROGRESS.md), [`LEARNING_LOG.md`](../LEARNING_LOG.md), and [`WEEKLY_REVIEWS.md`](../WEEKLY_REVIEWS.md).
