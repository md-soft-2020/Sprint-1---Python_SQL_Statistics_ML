# Sprint_1 : Python_SQL_Statistics_ML

The goal is to build a small, tested Python/SQL data workflow and evaluate a simple ML baseline, not to start with agents or advanced deep learning.

Core concepts to learn

### Python

Language fluency: lists, dictionaries, sets, comprehensions, loops, functions, scope and mutability.
Reliable programs: modules, type hints, exceptions, CSV/JSON, environments, testing and debugging.
Data work: pandas filtering/grouping/merging, missing values, dates and NumPy array shapes/vectorization.
Integration basics: parameterized SQL, HTTP/JSON, response validation and timeouts.
Readiness test: independently parse an imperfect file, validate it, aggregate it and test failure cases.

### SQL

You do not need to repeat basic SELECT syntax. Strengthen:
Grain, keys and joins: prevent one-to-many joins from multiplying your results.
NULLs and calculations: conditional aggregation, safe division, weighted averages and correct denominators.
Window functions: partition/order, explicit frames, tie-breaking, LAG and running totals.
Feature tables: deduplication, date windows and using only information available at prediction time.
Performance basics: query plans, filtering and pre-aggregation.
Readiness test: produce one row per request and verify your SQL results independently in Python.

### Statistics

Learn mean/median/quantiles, variance/standard deviation, weighted means, probability and conditional probability, sampling bias, confidence intervals, and correlation versus causation.
Readiness test: explain what a statistic measures, its denominator, its uncertainty and what it cannot establish.

### Machine learning

Learn features versus targets, regression versus classification, training versus inference, train/validation/test splits, preprocessing pipelines, data leakage, baselines, linear/logistic regression, overfitting and evaluation metrics.

Readiness test: compare a simple model with a baseline on untouched test data and explain its errors. A high score is not required; a trustworthy evaluation is.
