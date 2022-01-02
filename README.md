## GWU_DNSC 6314: Course Outline

Materials for an introduction to machine learning.

* Lecture 1: Preliminaries, Feature Engineering and Feature Selection
* Lecture 2: Penalized Regression
* Lecture 3: Model Assessment and Selection
* Lecture 4: Decision Trees
* Lecture 5: Artificial Neural Networks
* Lecture 6: Other Estimators: Support Vector Machines (SVM) k-Nearest-Neighbors, etc.

Corrections or suggestions? Please file a [GitHub issue](https://github.com/jphall663/GWU_ML/issues/new).

***

## Lecture 1:

![Extraction of a single principal component from two correlated model inputs.](/img/pca.png)
<sub><sup>**Source:** [Lecture 1 feature extraction example.](?flush_cache=true)</sup></sub>

### Lecture 1 Class Materials

* [Syllabus](https://raw.githubusercontent.com/jphall663/GWU_rml/master/Syllabus_PH_Responsible_Machine_Learning_MSBA%20_v4.pdf)
* [Lecture Notes](tex/lecture_1.pdf)
* [Assignment 1](https://raw.githubusercontent.com/jphall663/GWU_rml/master/assignments/tex/assignment_1.pdf)
  * [Model evaluation notebook](https://nbviewer.jupyter.org/github/jphall663/GWU_rml/blob/master/assignments/eval.ipynb)
  * [Full evaluations results](https://github.com/jphall663/GWU_rml/blob/master/assignments/model_eval_2021_06_25_13_04_19.csv)
* Software Examples:
  * [Building from Penalized GLM to Monotonic GBM](https://nbviewer.jupyter.org/github/jphall663/GWU_rml/blob/master/lecture_1.ipynb?flush_cache=true)
  * [Simple Explainable Boosting Machine Example](https://nbviewer.jupyter.org/github/jphall663/GWU_rml/blob/master/lecture_1_ebm_example.ipynb?flush_cache=true)


### Lecture 1 Suggested Software

* Python [explainable boosting machine (EBM)/GA2M](https://github.com/interpretml/interpret)
* R [`gam`](https://cran.r-project.org/web/packages/gam/index.html)
* `h2o` [penalized GLM](https://docs.h2o.ai/h2o/latest-stable/h2o-docs/data-science/glm.html) (R and Python)
* Monotonic gradient boosting machine (GBM): [`h2o`](https://docs.h2o.ai/h2o/latest-stable/h2o-docs/data-science/algo-params/monotone_constraints.html) and [`xgboost`](https://xgboost.readthedocs.io/en/latest/tutorials/monotonic.html) (R and Python)
* R [`rpart`](https://cran.r-project.org/web/packages/rpart/index.html)
* Python [`skope-rules`](https://github.com/scikit-learn-contrib/skope-rules)

### Lecture 1 Suggested Reading

* **Introduction and Background**:
  * [*Stop Explaining Black Box Machine Learning Models for High Stakes Decisions and Use Interpretable Models Instead*](https://www.nature.com/articles/s42256-019-0048-x)
  * **[Responsible Artificial Intelligence](https://www.springer.com/gp/book/9783030303709)** - Sections 2.1-2.5, Chapter 7

* **Interpretable Machine Learning Techniques**:
  * **Interpretable Machine Learning** - [Chapter 4](https://christophm.github.io/interpretable-ml-book/simple.html)
  * [*Accurate Intelligible Models with Pairwise Interactions*](http://www.cs.cornell.edu/~yinlou/papers/lou-kdd13.pdf)
  * [*This Looks Like That: Deep Learning for Interpretable Image Recognition*](https://arxiv.org/pdf/1806.10574.pdf)

* **Links from Lecture 1**:
  * [EU AI Regulation Proposal](https://digital-strategy.ec.europa.eu/en/library/proposal-regulation-laying-down-harmonised-rules-artificial-intelligence)
  * [FTC Guidance (2021)](https://www.ftc.gov/news-events/blogs/business-blog/2021/04/aiming-truth-fairness-equity-your-companys-use-ai)

***

Some materials Copyright Patrick Hall and the H2O.ai team 2017-2020.  
