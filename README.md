# 🎯 SWE / ML / Data Science Interview Prep

A structured checklist tracking my progress across algorithms, ML theory, statistics, and SQL — built for software, ML, and data science interviews.

---

## 📊 Progress Tracker

| Area | Topics |
|---|---|
| Algorithms & Data Structures | Arrays · Strings · Hash Maps · Stacks · Linked Lists · Trees · Heaps · Graphs · DP · Sorting · Backtracking |
| ML Theory | Linear Models · Trees · SVMs · Neural Nets · Unsupervised · Probabilistic · Sequence · Regularization · Evaluation |
| Statistics & Probability | Foundations · Distributions · Descriptive · Inferential · A/B Testing · Causal Inference |
| SQL | Core · Joins · Aggregations · Window Functions · CTEs · Optimization · Analytics Patterns |

---

## 🧮 Algorithms & Data Structures

### Arrays & Strings
- [ ] Two pointers (same direction, opposite direction)
- [ ] Sliding window (fixed size, variable size)
- [ ] Prefix sums & difference arrays
- [ ] Kadane's algorithm (maximum subarray)
- [ ] String manipulation (anagrams, palindromes, substring search)
- [ ] Matrix traversal (spiral, diagonal, rotation)

### Hash Maps & Sets
- [ ] Frequency counting
- [ ] Two-sum pattern and variants
- [ ] Grouping / bucketing
- [ ] Detecting cycles or duplicates

### Stacks & Queues
- [ ] Monotonic stack (next greater element, histogram area)
- [ ] Queue via two stacks
- [ ] Deque / sliding window maximum
- [ ] Expression evaluation & parenthesis matching

### Linked Lists
- [ ] Fast & slow pointers (cycle detection, midpoint)
- [ ] Reversal (full, partial, in k-groups)
- [ ] Merge sorted lists
- [ ] Intersection and reordering

### Trees
- [ ] Binary tree traversals (inorder, preorder, postorder — recursive & iterative)
- [ ] Level-order BFS
- [ ] BST operations (insert, delete, validate, kth smallest)
- [ ] Lowest common ancestor
- [ ] Height, diameter, path sum problems
- [ ] Trie (insert, search, prefix matching)
- [ ] Segment tree & binary indexed tree (Fenwick) — range queries

### Heaps & Priority Queues
- [ ] Min-heap / max-heap operations
- [ ] K largest / K smallest elements
- [ ] Merge K sorted lists
- [ ] Top-K frequent elements
- [ ] Two heaps pattern (median of stream)

### Graphs
- [ ] Representations (adjacency list vs matrix)
- [ ] DFS (iterative & recursive)
- [ ] BFS (shortest path in unweighted graphs)
- [ ] Topological sort (Kahn's algorithm, DFS-based)
- [ ] Union-Find / Disjoint Set (path compression, union by rank)
- [ ] Dijkstra's algorithm (weighted shortest path)
- [ ] Bellman-Ford (negative weights)
- [ ] Cycle detection (directed & undirected)
- [ ] Connected components, islands problems

### Dynamic Programming
- [ ] 1D DP (climbing stairs, house robber, coin change)
- [ ] 2D DP (grid paths, edit distance, LCS)
- [ ] Interval DP (burst balloons, matrix chain)
- [ ] Knapsack variants (0/1, unbounded, bounded)
- [ ] DP on trees
- [ ] Bitmask DP
- [ ] Identifying optimal substructure & overlapping subproblems

### Sorting & Searching
- [ ] Merge sort (and its use in inversion count)
- [ ] Quick sort & quickselect (kth largest)
- [ ] Counting sort, radix sort (when to use non-comparison sorts)
- [ ] Binary search (exact match, left/right boundary, on answer space)
- [ ] Search in rotated array

### Backtracking
- [ ] Subsets, permutations, combinations
- [ ] N-queens, Sudoku solver
- [ ] Pruning strategies

---

## 🤖 ML Theory

### Linear Models
- [ ] Linear regression: OLS derivation, normal equation, assumptions (BLUE)
- [ ] Logistic regression: sigmoid, log-loss, gradient derivation
- [ ] Multicollinearity, VIF
- [ ] Generalized linear models

### Tree-Based Methods
- [ ] Decision tree: splitting criteria (Gini, entropy, variance reduction), pruning
- [ ] Bagging & random forests: feature subsampling, out-of-bag error
- [ ] Boosting: AdaBoost, Gradient Boosting (residual fitting)
- [ ] XGBoost / LightGBM internals (histogram-based splits, leaf-wise vs depth-wise growth, DART)
- [ ] Feature importance types (split-based, gain-based, SHAP)

### Support Vector Machines
- [ ] Maximum margin classifier, support vectors
- [ ] Kernel trick (RBF, polynomial)
- [ ] Soft-margin SVM, C parameter
- [ ] When SVMs outperform tree methods

### Neural Networks
- [ ] Forward pass, loss computation
- [ ] Backpropagation derivation (chain rule)
- [ ] Activation functions (ReLU, sigmoid, tanh, GELU) and their gradients
- [ ] Vanishing / exploding gradients
- [ ] Weight initialization (Xavier, He)
- [ ] Batch normalization & layer normalization
- [ ] Dropout & other regularization
- [ ] Optimizers: SGD, momentum, RMSProp, Adam — update rules and intuition
- [ ] Learning rate schedules (warmup, cosine annealing)

### Unsupervised Learning
- [ ] K-means: algorithm, convergence, choosing K (elbow, silhouette)
- [ ] Hierarchical clustering: linkage methods
- [ ] DBSCAN: density reachability, epsilon and min-samples
- [ ] PCA: eigendecomposition, explained variance, when to use
- [ ] t-SNE & UMAP: intuition, use cases and limitations
- [ ] Autoencoders

### Probabilistic & Generative Models
- [ ] Naive Bayes: conditional independence assumption
- [ ] Gaussian Mixture Models & EM algorithm
- [ ] Variational Autoencoders: ELBO, reparameterization trick
- [ ] Basic GAN intuition

### Sequence Models
- [ ] RNN: unrolled computation, BPTT
- [ ] LSTM: gates (forget, input, output), cell state
- [ ] GRU: simplified gating
- [ ] Encoder-decoder & attention mechanism
- [ ] Transformer architecture: self-attention, positional encoding, multi-head attention, feedforward sublayer
- [ ] BERT vs GPT pretraining objectives

### Regularization & Optimization
- [ ] L1 (sparsity, feature selection) vs L2 (weight shrinkage)
- [ ] Elastic net
- [ ] Early stopping
- [ ] Data augmentation as regularization
- [ ] Gradient clipping

### Model Evaluation
- [ ] Classification: accuracy, precision, recall, F1, ROC-AUC, PR-AUC
- [ ] When to prefer PR-AUC over ROC-AUC (class imbalance)
- [ ] Regression: MAE, MSE, RMSE, MAPE, R²
- [ ] Ranking: NDCG, MAP, MRR
- [ ] Cross-validation: k-fold, stratified, time-series splits
- [ ] Calibration: Platt scaling, isotonic regression

### Bias, Fairness & Interpretability
- [ ] Bias-variance tradeoff formally
- [ ] Sources of bias (data, label, model)
- [ ] SHAP values, LIME, partial dependence plots
- [ ] Model cards, responsible ML practices

---

## 📐 Statistics & Probability

### Probability Foundations
- [ ] Sample spaces, events, axioms
- [ ] Conditional probability, Bayes' theorem
- [ ] Law of total probability
- [ ] Independence vs mutual exclusivity

### Distributions
- [ ] Discrete: Bernoulli, Binomial, Poisson, Geometric
- [ ] Continuous: Uniform, Gaussian, Exponential, Beta, Gamma
- [ ] When each arises naturally (e.g. Poisson for rare events, Exponential for wait times)
- [ ] Central Limit Theorem and its implications

### Descriptive Statistics
- [ ] Mean, median, mode — when each is appropriate
- [ ] Variance, standard deviation, IQR
- [ ] Skewness, kurtosis
- [ ] Covariance and correlation (Pearson vs Spearman)

### Inferential Statistics
- [ ] Sampling distributions, standard error
- [ ] Confidence intervals (construction and interpretation)
- [ ] Hypothesis testing framework (null/alternative, test statistic, p-value)
- [ ] Type I error (α) and Type II error (β), statistical power
- [ ] One-sample, two-sample t-tests; paired t-test
- [ ] Chi-squared test (independence, goodness of fit)
- [ ] ANOVA (one-way, assumptions)
- [ ] Non-parametric alternatives (Mann-Whitney, Wilcoxon)

### A/B Testing
- [ ] Experiment design: control vs treatment, randomization
- [ ] Sample size calculation (effect size, power, significance level)
- [ ] Sequential testing & peeking problem
- [ ] Multiple comparisons correction (Bonferroni, FDR/Benjamini-Hochberg)
- [ ] Novelty effects, network effects, interference
- [ ] Metric selection and guardrail metrics

### Regression & Causal Inference
- [ ] Simple vs multiple regression assumptions
- [ ] Heteroskedasticity, autocorrelation
- [ ] Omitted variable bias
- [ ] Difference-in-differences
- [ ] Instrumental variables (intuition)
- [ ] Regression discontinuity (intuition)

---

## 🗄️ SQL

### Core Querying
- [ ] SELECT, WHERE, ORDER BY, LIMIT
- [ ] DISTINCT, aliases
- [ ] Filtering with IN, BETWEEN, LIKE, IS NULL

### Joins
- [ ] INNER, LEFT, RIGHT, FULL OUTER
- [ ] Self joins
- [ ] Cross joins and when they're useful
- [ ] Join on multiple conditions

### Aggregations
- [ ] GROUP BY, HAVING
- [ ] COUNT, SUM, AVG, MIN, MAX
- [ ] Aggregate on filtered groups

### Window Functions
- [ ] ROW_NUMBER, RANK, DENSE_RANK
- [ ] LAG, LEAD (comparing to previous/next rows)
- [ ] NTILE (percentile bucketing)
- [ ] SUM/AVG OVER (running totals, moving averages)
- [ ] PARTITION BY vs ORDER BY within windows

### CTEs & Subqueries
- [ ] WITH clause structure
- [ ] Chaining multiple CTEs
- [ ] Recursive CTEs (org hierarchies, sequences)
- [ ] Correlated vs uncorrelated subqueries

### Data Manipulation
- [ ] INSERT, UPDATE, DELETE
- [ ] CASE WHEN for conditional logic
- [ ] COALESCE, NULLIF, IFNULL
- [ ] String functions (CONCAT, SUBSTRING, TRIM, UPPER/LOWER)
- [ ] Date functions (DATEDIFF, DATE_TRUNC, EXTRACT)
- [ ] Type casting

### Query Optimization
- [ ] How indexes work (B-tree, hash)
- [ ] When indexes hurt vs help
- [ ] EXPLAIN / EXPLAIN ANALYZE
- [ ] Avoiding SELECT *, unnecessary DISTINCT
- [ ] Partitioning and its query implications

### Analytics Patterns
- [ ] Cohort analysis (user retention by signup week)
- [ ] Funnel analysis (step-by-step conversion)
- [ ] Sessionization (grouping events into sessions)
- [ ] Running totals and cumulative metrics
- [ ] Year-over-year / period-over-period comparisons

---

## 📁 Repo Structure

```
interview-prep/
├── README.md                  ← this checklist
├── notes/
│   ├── algorithms.md
│   ├── ml-theory.md
│   ├── statistics.md
│   └── sql.md
├── implementations/
│   ├── logistic_regression.py
│   ├── decision_tree.py
│   └── ...
├── leetcode/
│   ├── two_pointers/
│   ├── dynamic_programming/
│   └── ...
└── projects/
    └── README.md              ← links to project repos
```

---

## 📚 Resources

| Area | Resource |
|---|---|
| LeetCode patterns | [NeetCode.io](https://neetcode.io) |
| ML systems design | *Designing Machine Learning Systems* — Chip Huyen |
| SQL practice | [StrataScratch](https://stratascratch.com) · [Mode](https://mode.com/sql-tutorial) |
| Stats & A/B testing | *Trustworthy Online Controlled Experiments* — Kohavi et al. |
| ML fundamentals | [fast.ai](https://fast.ai) · [CS229 Notes](https://cs229.stanford.edu/notes2022fall/main_notes.pdf) |
