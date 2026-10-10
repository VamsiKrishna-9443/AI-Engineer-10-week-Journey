# Week 05 — Machine Learning Foundations

**Planned dates:** 9–15 November 2026  
**Status:** Not started

## Goal
Understand supervised learning, feature/target separation, data splits, baselines, and generalization.

## Learning objectives
- [ ] Explain features and target labels.
- [ ] Create and justify a train/test split.
- [ ] Train a simple scikit-learn model.
- [ ] Identify overfitting and data leakage risks.

## Core concepts
- Supervised vs unsupervised learning
- Features and labels
- Train/validation/test splits
- Regression and classification
- Baselines and generalization
- Overfitting, underfitting, data leakage
- Basic scikit-learn pipeline

## Resources
- [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course)
- [Kaggle Learn: Intro to Machine Learning](https://www.kaggle.com/learn/intro-to-machine-learning)
- [StatQuest — Machine Learning playlist](https://www.youtube.com/playlist?list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF)
- [Machine Learning Specialization — Coursera](https://www.coursera.org/specializations/machine-learning-introduction) (check current access/audit terms)

Choose one primary resource first. Record the exact lesson you accessed and the date in `LEARNING_LOG.md`. Page availability does not guarantee that a video plays in every region or that the course remains free. If an item is unavailable, document the substitution in `RESOURCES.md`.

## Daily plan
1. Learn features, labels, classification, and regression.
2. Understand why data must be held out for testing.
3. Complete selected Intro to ML exercises.
4. Choose data, target, and features; document preprocessing.
5. Train a baseline model and make predictions.
6. Compute a suitable metric and inspect leakage risks.
7. Explain the workflow and what the metric does/does not tell you.

## Weekly build
Train a baseline model on Iris, Titanic, or another suitable public dataset; explain target/features, splitting, metric, and limitations.

## Testing and evaluation
- [ ] Train/test partitions do not overlap.
- [ ] Target is not accidentally included as an input feature.
- [ ] Code runs in a clean environment.
- [ ] A suitable metric and baseline are recorded.

Record the commands actually run and observed output. If a check is manual, record the input and what happened.

## Interview / self-explanation questions
- Why keep a test set separate?
- What is overfitting?
- What is data leakage and why is it dangerous?

Answer these in your own words. Revisit any question you cannot explain without notes.

## Deliverables
- [ ] Working code or notebook
- [ ] README with setup/run instructions and example output
- [ ] Tests or appropriate evaluation with actual results
- [ ] Resource attribution, data provenance, and known limitations
- [ ] Learning-log entry and weekly reflection
- [ ] Evidence link added to `PROGRESS.md`

## Completion criteria
- [ ] Feature/target choice is explained.
- [ ] Split is appropriate and reproducible.
- [ ] Metric and baseline are recorded.
- [ ] Overfitting and leakage are discussed.
- [ ] Notebook/script can be rerun.

A week is completed only after implementation, verification, documentation, and review. Watching videos or generating starter code is not sufficient.

## Reflection prompts
- What can I now explain or build without copying?
- What was the most difficult bug or concept, and how did I investigate it?
- What remains incomplete?
- What is the next smallest action?

See [`ROADMAP.md`](../ROADMAP.md), [`PROGRESS.md`](../PROGRESS.md), [`LEARNING_LOG.md`](../LEARNING_LOG.md), and [`WEEKLY_REVIEWS.md`](../WEEKLY_REVIEWS.md).
