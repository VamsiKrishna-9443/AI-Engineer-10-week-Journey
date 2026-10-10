# My 10-Week AI Engineer Journey

A public learning journal for turning AI/ML knowledge into practical AI engineering skills. This repository tracks study notes, experiments, weekly builds, evaluations, and lessons learned.

**Roadmap source:** [The 10-Week AI Engineer Roadmap (with videos you can actually watch)](https://medium.com/@id.shivanjali/the-10-week-ai-engineer-roadmap-with-videos-you-can-actually-watch-e2e831b75d18) by Shivanjali Verma.

**Planned dates:** 12 October – 20 December 2026  
**Target pace:** 6–8 focused hours/week alongside other responsibilities; aim for 10–12 hours/week if available.  
**Rule:** Build something every week. Watching a course alone does not count as completing a week.

## My goal

Become a capable, job-ready AI engineer by demonstrating that I can work with data, train and evaluate ML models, build LLM-powered applications, implement RAG, and deliver a documented end-to-end project.

## Progress dashboard

Update [`PROGRESS.md`](./PROGRESS.md) every study day and at the end of each week.

| Week | Focus | Status | Evidence |
|---|---|---|---|
| 01 | Python foundations | Not started | [Week 01](./week-01-python-foundations/README.md) |
| 02 | Practical Python + Git/GitHub | Not started | [Week 02](./week-02-python-git/README.md) |
| 03 | Pandas and data analysis | Not started | [Week 03](./week-03-pandas-data/README.md) |
| 04 | NLP, embeddings, semantic similarity | Not started | [Week 04](./week-04-nlp-embeddings/README.md) |
| 05 | ML foundations | Not started | [Week 05](./week-05-ml-foundations/README.md) |
| 06 | Models and evaluation | Not started | [Week 06](./week-06-models-evaluation/README.md) |
| 07 | LLM fundamentals | Not started | [Week 07](./week-07-llm-fundamentals/README.md) |
| 08 | Prompting, APIs, responsible AI | Not started | [Week 08](./week-08-genai-api/README.md) |
| 09 | RAG and vector search | Not started | [Week 09](./week-09-rag-vector-db/README.md) |
| 10 | Agents and capstone | Not started | [Week 10](./week-10-agents-capstone/README.md) |

## Repository layout

```text
.
├── README.md                 # Portfolio landing page
├── ROADMAP.md                # Weekly goals, tasks, acceptance criteria
├── PROGRESS.md               # Checklist and weekly status
├── LEARNING_LOG.md           # Daily learning journal
├── PROJECTS.md               # Project portfolio index
├── RESOURCES.md              # Study links
├── WEEKLY_REVIEWS.md         # Weekly review template
├── requirements-dev.txt      # Lightweight dev tools
├── week-01-.../README.md     # Weekly notes, evidence, reflection
└── week-10-.../README.md
```

When you build a weekly project, keep its source code and README in that week's folder, or link to a separate focused repository from the weekly page.

## First-time local setup

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements-dev.txt
```

On Windows, activate with `.venv/\Scripts/activate`. Individual weeks may require additional packages.

## Weekly definition of done

- [ ] I can explain the core ideas in my own words without copying the tutorial.
- [ ] The weekly build runs from a clean setup using documented commands.
- [ ] The README explains the problem, approach, setup, example output, limitations, and what I learned.
- [ ] Tests or measurable evaluation are included where appropriate.
- [ ] I made meaningful commits that reflect my work.
- [ ] I updated `PROGRESS.md`, the weekly page, `LEARNING_LOG.md`, and `WEEKLY_REVIEWS.md`.
- [ ] I listed any gaps honestly rather than marking unfinished work complete.

## GitHub habits

Use small, meaningful commits. Examples:

```bash
git add .
git commit -m "docs(week-01): record Python learning goals"
git commit -m "feat(week-01): implement number guessing game"
git commit -m "test(week-01): cover input validation"
```

Never commit API keys, passwords, `.env` files, private datasets, company code, or personal documents. Use `.env.example` with placeholder values instead.

## Weekly review questions

1. What can I now explain or build that I could not do before?
2. What evidence proves it (code, tests, metrics, demo, notes)?
3. What was difficult, and how did I debug it?
4. What remains incomplete?
5. What will I change next week?

---

*This is a starter tracker, not a claim that any week is already complete. Update it as you do the work.*
