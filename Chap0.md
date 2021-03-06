# Chapter 00: the Gap between Machine Learing Text Book and Engineering

Why to learn the course and do other practices

- Data Science in practice are much broader than just Machine Learning
  - eg.
    - Data Mining (mining features and information from data)
    - Social Science (expirements, conterfactuals, ecnonometric modeling tricks, etc)
    - Recommendation System, Search Enginee, etc -> cannot just formulate as a classification problem
    - more fields/sub-fileds in "Machine Learning" such as NLP, knowledge representation, Reinforcement Learning etc
- From Theory to implementation
  - C++, linux...system knowledge required
    - popular packages (Scikit-Learn, Tensow-flow) is not nessearly efficient and effective enough
      - eg. bugs in AdamW, RAdam, etc
  - **debugging skills** and experience
    - data problems
    - code details
    - training/tuning tricks
    - different tools
- Requires **Math Knowledge** than traditional SDE
  - from Linear Algebra, calculus to code
  - derive formulas needed in daily work
  - one theory used and modified in many models
    - eg. **Bayesian inference, Variational inference**
- Requires more **full-stack** engineering skills than traditional
  - need to understand all aspects including business problem, data pipeline, black-box learning procedures and results
    - common tricks in algorithm, implementations and data
- Baseline model is not enough in pracitce
  - **Model Tuning** could be hard
  - Babysitting models
  - use pretrained models
  - tune based on data - very very hard
- From learning algorithm to production model
  - many winining models in *Kaggle* does not **scale**
    - parallel computing, Big Data, model distribution
  - online vs offline
    - many models cannot be easily planted to production system
- Research Skills
  - read papers
    - evaluate (# of reference, source, background), fast reading
  - code in papers