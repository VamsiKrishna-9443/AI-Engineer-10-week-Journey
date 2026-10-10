# 10-Week Roadmap and Acceptance Criteria

Dates use a Monday–Sunday study week. Adjust dates if life or work requires it; do not rush past a build just to keep the calendar.

## Week 1 — Python foundations (12–18 Oct)
**Learn:** variables, types, conditionals, loops, functions, input/output, debugging.  
**Build:** a command-line number guessing game or tip calculator.  
**Deliver:** runnable code, clear input validation, at least a few tests, README, reflection.  
**Done when:** a new user can run it from the README and you can explain every function.

## Week 2 — Practical Python + Git/GitHub (19–25 Oct)
**Learn:** lists, dictionaries, sets/tuples, file handling, exceptions, modules, virtual environments, Git commits/branches.  
**Build:** improve Week 1's project; add a feature that saves and reads results from a file.  
**Deliver:** clean project structure, tests, README, Git history, screenshots or sample output.  
**Done when:** setup works from a fresh clone and no secrets or unnecessary files are committed.

## Week 3 — Data handling with Pandas (26 Oct–1 Nov)
**Learn:** NumPy basics, DataFrames, loading CSV files, filtering, grouping, missing values, type conversion, exploratory analysis.  
**Build:** analyze a public, appropriately licensed dataset in a notebook and answer three specific questions.  
**Deliver:** reproducible notebook, dataset source/license, data-quality summary, charts, findings, limitations.  
**Done when:** another person can follow how raw data became each result.

## Week 4 — Text, NLP, embeddings (2–8 Nov)
**Learn:** tokenization, vectors/embeddings, cosine similarity, semantic vs. keyword search.  
**Build:** a small semantic-search program using a sentence-transformers model and a list of example sentences/documents.  
**Deliver:** runnable script/notebook, similarity scores, examples where it works and fails.  
**Done when:** you can explain embeddings, similarity scoring, and why nearest does not always mean correct.

## Week 5 — ML foundations (9–15 Nov)
**Learn:** features/labels, train/validation/test, leakage, baselines, supervised learning, overfitting, generalization.  
**Build:** a baseline classification model on Iris, Titanic, or another public dataset.  
**Deliver:** data split, baseline metrics, training code, saved evaluation output, limitations.  
**Done when:** you can describe what the model predicts and what your score does—and does not—prove.

## Week 6 — Core models and evaluation (16–22 Nov)
**Learn:** regression vs. classification, logistic/linear regression, decision trees, random forests, precision/recall/F1, confusion matrix, cross-validation, pipelines.  
**Build:** compare at least two models on the same task using a consistent split and metric.  
**Deliver:** comparison table, reasoning for metric selection, error analysis, reproducible pipeline.  
**Done when:** the comparison is fair and you can explain false positives/false negatives in the chosen problem.

## Week 7 — LLM fundamentals (23–29 Nov)
**Learn:** tokens, next-token prediction, context windows, transformers/attention at a high level, sampling, hallucinations, embeddings.  
**Build:** a concise explainer in your own words plus a tiny experiment that shows how prompts/context affect output.  
**Deliver:** `LLM_FUNDAMENTALS.md`, experiment notes, sources, misconceptions corrected.  
**Done when:** you can explain how an LLM produces text without describing it as a search engine or claiming it knows every fact.

## Week 8 — Prompting, GenAI APIs, responsible AI (30 Nov–6 Dec)
**Learn:** prompt structure, system/user messages, structured output, retries/timeouts, cost/latency awareness, evaluation, privacy and safety.  
**Build:** an article summarizer that compares three prompt strategies. Use an API or a locally/hosted free model.  
**Deliver:** `.env.example` (no real key), setup guide, sample input/output, prompt comparison, failure cases, basic tests.  
**Done when:** errors are handled, secrets are excluded, and you can justify which prompt performs best against a simple rubric.

## Week 9 — RAG and vector databases (7–13 Dec)
**Learn:** document loading, chunking, embeddings, vector retrieval, top-k, grounding, citations, retrieval failure modes.  
**Build:** “chat with a PDF” over public/sample documents using Chroma or FAISS and an LLM.  
**Deliver:** ingestion/retrieval/answer flow, source references in answers, a small evaluation set of questions, known limitations.  
**Done when:** answers can be traced to retrieved context and the app admits when evidence is missing.

## Week 10 — Agents and capstone (14–20 Dec)
**Learn:** tool/function calling, agent loop, orchestration, guardrails, evaluation, API/UI integration, deployment basics.  
**Recommended capstone:** **Source-Grounded AI Knowledge Assistant** — upload public documents, retrieve relevant chunks, answer with citations, and expose it through a simple UI or API. Avoid using private company/customer files.  
**Deliver:** polished repo, architecture diagram, environment setup, tests/evaluation results, known limitations, a 60-second demo, and a final retrospective.  
**Done when:** a reviewer can run or try the app, understand the architecture, inspect evidence, and see honest evaluation results.

## Suggested weekly rhythm

- **Session 1:** study concepts and write notes (60–90 min).
- **Session 2:** follow one focused tutorial or official lesson (60–90 min).
- **Session 3:** implement independently (90–120 min).
- **Session 4:** debug, test, evaluate, and document (90–120 min).
- **Session 5:** review concepts, commit, and write the weekly reflection (45–60 min).

## Important scope note

Ten weeks is a strong foundation and portfolio sprint, not a guarantee of mastery. Continue afterward with deeper ML/DL, statistics, deployment, monitoring, experiment tracking, and interview practice.
