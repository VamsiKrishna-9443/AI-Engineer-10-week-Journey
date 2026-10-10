# Week 10 — Agents, Frameworks, Capstone

**Planned dates:** 14–20 December 2026  
**Status:** Not started

## Goal
Understand bounded tool-using agent loops and ship one end-to-end capstone with tests, evaluation, and reproducible documentation.

## Learning objectives
- [ ] Distinguish a single model call, RAG pipeline, and agent loop.
- [ ] Give an agent a small set of explicit tools.
- [ ] Validate tool arguments and define stop conditions.
- [ ] Package a capstone with tests, evidence, and limitations.

## Core concepts
- Agent model/tool/observation loop
- Function calling and input validation
- Frameworks only when justified
- Boundaries, stop conditions, timeouts
- Reliability evaluation and failure analysis
- Reproducible capstone setup and demo

## Resources
- [Hugging Face AI Agents Course](https://huggingface.co/learn/agents-course/en/unit0/introduction)
- [LangChain Agents documentation](https://docs.langchain.com/oss/python/langchain/agents)
- [Microsoft Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners)

Choose one primary resource first. Record the exact lesson you accessed and the date in `LEARNING_LOG.md`. Page availability does not guarantee that a video plays in every region or that the course remains free. If an item is unavailable, document the substitution in `RESOURCES.md`.

## Daily plan
1. Choose a capstone option and define user, problem, and acceptance tests.
2. Design a minimal architecture and list allowed tool inputs/outputs.
3. Implement one end-to-end vertical slice before adding abstractions.
4. Add input validation, limits, timeouts, and stop conditions.
5. Test core flow, tool/model errors, unsupported questions, and safety boundaries.
6. Polish README, architecture, setup instructions, evaluation, and demo.
7. Review all ten weeks and write an honest retrospective and next plan.

## Weekly build
Recommended capstone: an evidence-grounded AI research assistant over permitted documents that retrieves sources, summarizes findings, links claims to evidence, validates tool inputs, and admits insufficient evidence. Alternatives: a RAG chatbot over allowed resume/company documents or an agent for one bounded workflow.

## Testing and evaluation
- [ ] Core flow works on documented example inputs.
- [ ] Tool inputs are validated and tool scope is bounded.
- [ ] Failure stops safely or reports a clear error.
- [ ] Claims are supported by evidence when grounding is promised.
- [ ] Fresh setup works or the exact blocker is documented.

Record the commands actually run and observed output. If a check is manual, record the input and what happened.

## Interview / self-explanation questions
- When is a deterministic pipeline better than an agent?
- How would you validate tool arguments?
- How do you evaluate agent reliability and prevent runaway loops?

Answer these in your own words. Revisit any question you cannot explain without notes.

## Deliverables
- [ ] Working code or notebook
- [ ] README with setup/run instructions and example output
- [ ] Tests or appropriate evaluation with actual results
- [ ] Resource attribution, data provenance, and known limitations
- [ ] Learning-log entry and weekly reflection
- [ ] Evidence link added to `PROGRESS.md`

## Completion criteria
- [ ] Capstone runs with documented setup.
- [ ] Success and failure cases are tested.
- [ ] Tool use has boundaries and stop conditions.
- [ ] Evaluation evidence and limitations are included.
- [ ] Statuses for all weeks match actual evidence.

A week is completed only after implementation, verification, documentation, and review. Watching videos or generating starter code is not sufficient.

## Reflection prompts
- What can I now explain or build without copying?
- What was the most difficult bug or concept, and how did I investigate it?
- What remains incomplete?
- What is the next smallest action?

See [`ROADMAP.md`](../ROADMAP.md), [`PROGRESS.md`](../PROGRESS.md), [`LEARNING_LOG.md`](../LEARNING_LOG.md), and [`WEEKLY_REVIEWS.md`](../WEEKLY_REVIEWS.md).
