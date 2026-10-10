# Week 04 — NLP, Embeddings, and Semantic Search

**Planned dates:** 2–8 November 2026  
**Status:** Not started

## Goal
Understand how text is represented numerically and retrieve semantically similar sentences with a pretrained model.

## Learning objectives
- [ ] Explain tokenization at a high level.
- [ ] Explain embeddings and cosine similarity conceptually.
- [ ] Generate embeddings using a pretrained model.
- [ ] Compare ranked results and identify retrieval errors.

## Core concepts
- Text normalization and tokenization
- Sparse keyword representations vs dense embeddings
- Vector similarity and cosine similarity
- Pretrained sentence embeddings
- Top-k ranking and semantic search
- Qualitative evaluation and failure examples

## Resources
- [Sentence Transformers documentation](https://sbert.net/)
- [Hugging Face Learn](https://huggingface.co/learn)
- [3Blue1Brown — Neural Networks series](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)

Choose one primary resource first. Record the exact lesson you accessed and the date in `LEARNING_LOG.md`. Page availability does not guarantee that a video plays in every region or that the course remains free. If an item is unavailable, document the substitution in `RESOURCES.md`.

## Daily plan
1. Learn tokens and why text needs numeric representations.
2. Compare keyword search with semantic search on examples.
3. Run a documented Sentence Transformers example.
4. Create a small corpus and generate embeddings.
5. Implement similarity ranking and top-k results.
6. Test paraphrases, ambiguity, and unrelated queries.
7. Document examples, setup, and limitations.

## Weekly build
Create a small semantic sentence search utility: embed a short FAQ/corpus, accept a query, rank likely matches, and show similarity scores.

## Testing and evaluation
- [ ] Paraphrase queries retrieve relevant examples when supported by the model.
- [ ] Unrelated queries are not claimed as guaranteed matches.
- [ ] Model/version and setup are documented.
- [ ] At least five queries and results are recorded.

Record the commands actually run and observed output. If a check is manual, record the input and what happened.

## Interview / self-explanation questions
- What is an embedding?
- How can sentences with different words have similar embeddings?
- What does cosine similarity measure and not prove?

Answer these in your own words. Revisit any question you cannot explain without notes.

## Deliverables
- [ ] Working code or notebook
- [ ] README with setup/run instructions and example output
- [ ] Tests or appropriate evaluation with actual results
- [ ] Resource attribution, data provenance, and known limitations
- [ ] Learning-log entry and weekly reflection
- [ ] Evidence link added to `PROGRESS.md`

## Completion criteria
- [ ] Embeddings use a documented model.
- [ ] Top-k ranking works.
- [ ] Five or more sample queries are tested.
- [ ] Keyword and semantic search are compared.
- [ ] Limitations are explicitly documented.

A week is completed only after implementation, verification, documentation, and review. Watching videos or generating starter code is not sufficient.

## Reflection prompts
- What can I now explain or build without copying?
- What was the most difficult bug or concept, and how did I investigate it?
- What remains incomplete?
- What is the next smallest action?

See [`ROADMAP.md`](../ROADMAP.md), [`PROGRESS.md`](../PROGRESS.md), [`LEARNING_LOG.md`](../LEARNING_LOG.md), and [`WEEKLY_REVIEWS.md`](../WEEKLY_REVIEWS.md).
