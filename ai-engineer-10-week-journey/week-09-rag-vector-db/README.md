# Week 09 — RAG and Vector Databases

**Planned dates:** 7–13 December 2026  
**Status:** Not started

## Goal
Build a document QA prototype grounded in retrieved source passages and able to admit missing evidence.

## Learning objectives
- [ ] Explain the retrieval-augmented generation pipeline.
- [ ] Load/chunk documents, create embeddings, and retrieve passages.
- [ ] Inspect whether retrieved context supports an answer.
- [ ] Expose source evidence and handle unsupported questions.

## Core concepts
- Document loading and chunking
- Embeddings and local vector stores
- Top-k retrieval and similarity
- RAG response generation
- Source evidence/citations
- Retrieval evaluation and abstention

## Resources
- [LangChain documentation](https://docs.langchain.com/oss/python/langchain/overview)
- [Chroma documentation](https://docs.trychroma.com/)
- [Sentence Transformers documentation](https://sbert.net/)
- [freeCodeCamp RAG course search](https://www.youtube.com/results?search_query=freeCodeCamp+RAG+vector+database+tutorial) (choose and verify a specific lesson)

Choose one primary resource first. Record the exact lesson you accessed and the date in `LEARNING_LOG.md`. Page availability does not guarantee that a video plays in every region or that the course remains free. If an item is unavailable, document the substitution in `RESOURCES.md`.

## Daily plan
1. Draw and explain the RAG pipeline.
2. Select a document you are allowed to use and record its source/terms.
3. Extract text and inspect chunk boundaries.
4. Generate embeddings and store searchable chunks.
5. Test top-k retrieval with known questions.
6. Generate answers grounded in retrieved evidence.
7. Test unsupported questions and document failure modes.

## Weekly build
Create a chat-with-a-PDF prototype using one permitted document, chunking, embeddings, a local vector store, retrieved evidence, and a clear “not enough evidence” response.

## Testing and evaluation
- [ ] Known-answer query retrieves a supporting passage.
- [ ] Unsupported question does not get a fabricated confident answer.
- [ ] Answer is traceable to retrieved evidence.
- [ ] Repeated ingestion behavior is understood/documented.

Record the commands actually run and observed output. If a check is manual, record the input and what happened.

## Interview / self-explanation questions
- What problem does RAG solve?
- How does chunk size influence retrieval?
- What should the application do without supporting evidence?

Answer these in your own words. Revisit any question you cannot explain without notes.

## Deliverables
- [ ] Working code or notebook
- [ ] README with setup/run instructions and example output
- [ ] Tests or appropriate evaluation with actual results
- [ ] Resource attribution, data provenance, and known limitations
- [ ] Learning-log entry and weekly reflection
- [ ] Evidence link added to `PROGRESS.md`

## Completion criteria
- [ ] Loading, chunking, embedding, and retrieval work.
- [ ] Vector store and setup are documented.
- [ ] Answers expose supporting evidence.
- [ ] Insufficient evidence is handled honestly.
- [ ] At least five questions are evaluated, including an unanswerable one.

A week is completed only after implementation, verification, documentation, and review. Watching videos or generating starter code is not sufficient.

## Reflection prompts
- What can I now explain or build without copying?
- What was the most difficult bug or concept, and how did I investigate it?
- What remains incomplete?
- What is the next smallest action?

See [`ROADMAP.md`](../ROADMAP.md), [`PROGRESS.md`](../PROGRESS.md), [`LEARNING_LOG.md`](../LEARNING_LOG.md), and [`WEEKLY_REVIEWS.md`](../WEEKLY_REVIEWS.md).
