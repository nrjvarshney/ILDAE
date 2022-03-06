# ILDAE: Instance-Level Difficulty Analysis of Evaluation Data

Public repository associated with [ILDAE: Instance-Level Difficulty Analysis of Evaluation Data, ACL 2022](https://arxiv.org/abs/).

# Abstract
Knowledge of questions' difficulty level helps a teacher in several ways, such as estimating students' potential quickly by asking carefully selected questions and improving quality of examination by modifying trivial and hard questions.

_Can we extract such benefits of instance difficulty in Natural Language Processing?_

To this end, we conduct **I**nstance-**L**evel **D**ifficulty **A**nalysis of **E**valuation data (ILDAE) in a large-scale setup of $23$ datasets and demonstrate its five novel applications: 
1. conducting efficient-yet-accurate evaluations with fewer instances saving computational cost and time, 
2. improving quality of existing evaluation datasets by repairing erroneous and trivial instances, 
3. selecting the best model based on application requirements, 
4. analyzing dataset characteristics for guiding future data creation, 
5. estimating Out-of-Domain performance reliably.

Comprehensive experiments for these applications result in several interesting findings, such as evaluation using just _5%_ instances (selected via ILDAE) achieves as high as _0.93_ Kendall correlation with evaluation using complete dataset and computing weighted accuracy using difficulty scores leads to _5.2%_ higher Kendall correlation with Out-of-Domain performance.
We release our computed difficulty scores [https://github.com/nrjvarshney/ILDAE](https://github.com/nrjvarshney/ILDAE) to encourage research in important yet understudied areas such as efficient evaluations and difficulty analysis.
