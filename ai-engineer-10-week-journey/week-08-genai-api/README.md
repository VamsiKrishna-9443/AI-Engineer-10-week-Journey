# Week 08 — Prompting, GenAI APIs, Responsible AI

**Planned dates:** 30 November–6 December 2026  
**Status:** Not started

## Goal
Build a Python generative-AI application, compare prompts systematically, handle failures safely, and record responsible-AI concerns.

## Learning objectives
- [ ] Write prompts with explicit task, context, constraints, and output format.
- [ ] Call a model API or clearly document a mocked alternative.
- [ ] Handle missing configuration and API errors safely.
- [ ] Evaluate outputs for fidelity, bias, privacy, and unsupported claims.

## Core concepts
- Prompt structure and structured outputs
- API requests, timeouts, error handling, rate limits
- Environment variables and key hygiene
- Prompt comparison and evaluation rubric
- Bias, safety, privacy, responsible use

## Resources
- [DeepLearning.AI — ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) (open directly to verify access)
- [Microsoft Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners)
- [Anthropic Academy](https://academy.claude.com/) (optional; terms may vary)

Choose one primary resource first. Record the exact lesson you accessed and the date in `LEARNING_LOG.md`. Page availability does not guarantee that a video plays in every region or that the course remains free. If an item is unavailable, document the substitution in `RESOURCES.md`.

## Daily plan
1. Draft a summarization prompt and define what “good” means.
2. Review provider documentation and safe key configuration.
3. Implement a minimal API call and clear timeout/error handling.
4. Compare three prompt versions on identical input.
5. Score fidelity, coverage, concision, and unsupported claims.
6. Test empty/long input, API failure, and privacy boundaries.
7. Document setup, cost/usage limits, results, and limitations.

## Weekly build
Build a Python article summarizer that compares three prompts on the same article using a rubric. Never commit an API key.

## Testing and evaluation
- [ ] Missing key/config gives useful instructions.
- [ ] Response format matches expectations.
- [ ] API errors are handled without secret leakage.
- [ ] Three prompts are evaluated with the same rubric.
- [ ] Privacy and hallucination limits are documented.

Record the commands actually run and observed output. If a check is manual, record the input and what happened.

## Interview / self-explanation questions
- What makes a prompt testable?
- How should API keys be stored?
- How can a summary be evaluated beyond fluency?

Answer these in your own words. Revisit any question you cannot explain without notes.

## Deliverables
- [ ] Working code or notebook
- [ ] README with setup/run instructions and example output
- [ ] Tests or appropriate evaluation with actual results
- [ ] Resource attribution, data provenance, and known limitations
- [ ] Learning-log entry and weekly reflection
- [ ] Evidence link added to `PROGRESS.md`

## Completion criteria
- [ ] Three prompt versions compared on same input.
- [ ] A model call or documented mock works.
- [ ] No secrets are committed.
- [ ] Expected failure paths are handled.
- [ ] Responsible AI and limitations are described.

A week is completed only after implementation, verification, documentation, and review. Watching videos or generating starter code is not sufficient.

## Reflection prompts
- What can I now explain or build without copying?
- What was the most difficult bug or concept, and how did I investigate it?
- What remains incomplete?
- What is the next smallest action?

See [`ROADMAP.md`](../ROADMAP.md), [`PROGRESS.md`](../PROGRESS.md), [`LEARNING_LOG.md`](../LEARNING_LOG.md), and [`WEEKLY_REVIEWS.md`](../WEEKLY_REVIEWS.md).
