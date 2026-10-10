# Week 06 — Core Models and Evaluation

**Planned dates:** 16–22 November 2026  
**Status:** Not started

## Goal
Compare at least two ML algorithms using appropriate metrics, validation, and error analysis.

## Learning objectives
- [ ] Train and compare at least two algorithms.
- [ ] Use suitable metrics such as accuracy, precision, recall, F1, or MAE/RMSE.
- [ ] Explain class imbalance and metric trade-offs.
- [ ] Prevent preprocessing leakage.

## Core concepts
- Regression/classification metrics
- Decision trees and alternative baseline models
- Confusion matrix, precision, recall, F1
- Validation and cross-validation concepts
- Preprocessing pipelines
- Error analysis and model selection

## Resources
- [scikit-learn model evaluation](https://scikit-learn.org/stable/modules/model_evaluation.html)
- [Kaggle Learn: Intermediate Machine Learning](https://www.kaggle.com/learn/intermediate-machine-learning)
- [Codebasics — ML tutorials](https://www.youtube.com/playlist?list=PLeo1K3hjS3uvCeTYTeyfe0-rN5r8zn9rw)

Choose one primary resource first. Record the exact lesson you accessed and the date in `LEARNING_LOG.md`. Page availability does not guarantee that a video plays in every region or that the course remains free. If an item is unavailable, document the substitution in `RESOURCES.md`.

## Daily plan
1. Choose metrics before comparing final results.
2. Train model A and preserve the baseline.
3. Train model B with comparable data/split/preprocessing.
4. Calculate metrics and inspect confusion matrix if classification.
5. Analyze false positives/negatives or large regression errors.
6. Compare models without repeatedly tuning against the test set.
7. Write selection rationale, limitations, and a next experiment.

## Weekly build
Extend Week 5 by comparing two algorithms on a comparable split, presenting a metrics table, and analyzing mistakes.

## Testing and evaluation
- [ ] Models use comparable evaluation data.
- [ ] Preprocessing is fit on training data only when applicable.
- [ ] Metric labels and calculations are clear.
- [ ] Conclusions account for class balance/error cost.

Record the commands actually run and observed output. If a check is manual, record the input and what happened.

## Interview / self-explanation questions
- When can accuracy be misleading?
- Explain precision vs recall.
- How do pipelines reduce leakage risk?

Answer these in your own words. Revisit any question you cannot explain without notes.

## Deliverables
- [ ] Working code or notebook
- [ ] README with setup/run instructions and example output
- [ ] Tests or appropriate evaluation with actual results
- [ ] Resource attribution, data provenance, and known limitations
- [ ] Learning-log entry and weekly reflection
- [ ] Evidence link added to `PROGRESS.md`

## Completion criteria
- [ ] At least two models compared.
- [ ] Relevant metrics are reported.
- [ ] Data leakage controls are documented.
- [ ] Errors are investigated.
- [ ] Model choice is supported by evidence.

A week is completed only after implementation, verification, documentation, and review. Watching videos or generating starter code is not sufficient.

## Reflection prompts
- What can I now explain or build without copying?
- What was the most difficult bug or concept, and how did I investigate it?
- What remains incomplete?
- What is the next smallest action?

See [`ROADMAP.md`](../ROADMAP.md), [`PROGRESS.md`](../PROGRESS.md), [`LEARNING_LOG.md`](../LEARNING_LOG.md), and [`WEEKLY_REVIEWS.md`](../WEEKLY_REVIEWS.md).
