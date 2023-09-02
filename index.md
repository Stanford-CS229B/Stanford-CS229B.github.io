---
layout: default
title: Home
seo:
  type: Course
  name: {{ site.title }}
nav_order: 1
---

# {{ site.tagline }}

<!--{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}-->

This course provides a broad and deep treatment of modern statistical machine learning topics.  Students entering the course are assumed to have foundational working knowledge in statistics, probability, and basic machine learning concepts, though the course has been designed to provide a broadly accessible treatment of the topics covered.  

The course starts with a quick review of linear regression and classification, error metrics, and the bias-variance tradeoff.  We then delve into decision trees and deep learning techniques for non-linear regression and classification tasks.  The subsequent modules move beyond regression and classification tasks and turn to discovering patterns and low-dimensional structure via unsupervised learning.  Topics include clustering, dimensionality reduction and autoencoding methods, and matrix factorization.  The last module considers time series and sequential data sources via state space models and deep learning methods. 

## Teaching team

{% assign instructors = site.staffers | sort: 'index' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Course Logistics

**When**: Class is Mondays and Wednesdays 1:30-2:50pm PST.

**Where**: Class will be in person at
[Gates B3](https://campus-map.stanford.edu/?srch=Gates+B3).

**Links**:
- [Ed](https://edstem.org/us/dashboard):
  This is the main way that you and the teaching team should communicate:
  we will post all important announcements here, and you should ask
  all course-related questions here.
  For personal matters that you don't wish to put in a private Ed post, you can
  email the teaching staff at [stats315b-spr2223-staff@lists.stanford.edu](mailto:stats315b-spr2223-staff@lists.stanford.edu).
- [Canvas](https://canvas.stanford.edu/courses/169909): The course Canvas page
  contains links and resources only accessible to students.
- [Gradescope](https://www.gradescope.com/courses/524269): We use Gradescope
  for managing coursework (turning in, returning grades).  Please use your
  @stanford.edu email address to sign up for a Gradescope account.

**Prerequisites**: A well-prepared student will have knowledge of:
  * Math:
    * Linear algebra (matrix/vector operations, orthogonality, etc.)
    * Multivariate calculus (gradients, partial derivatives)
  * Probability:
    * Random variables, expectations, Gaussian distribution, conditional and marginal distributions
  * Statistics / machine learning basics:
    * Linear regression and classification and, ideally, overfitting and bias-variance tradeoff
    * Parameter estimation, including via maximum likelihood estimation
  * Programming proficiency in:
    * Python (preferred for this course), or
    * R, Julia, etc. with an ability to (i) pivot to Python with starter code or (ii) code independently in selected language

From experience, eager students with a strong quantitative background are able to catch up and fully participate.  

**Course Grade**: The course grade will be based on the following components.

- 5 Homework Assignments (45%): HW0 (5%), HW1 - HW4 (40%)
- Concept Quizzes (15%)
- Final Project (40%): Project midway (8%), Project presentation (8%), Project report (24%)

**Textbooks**:
- [Probabilistic Machine Learning](https://probml.github.io/pml-book/): [An Introduction](https://probml.github.io/pml-book/book1.html); Kevin Murphy
- [Probabilistic Machine Learning](https://probml.github.io/pml-book/): [Advanced Topics](https://probml.github.io/pml-book/book2.html); Kevin Murphy
- [The Elements of Statistical Learning: Data Mining, Inference, and Prediction, 2nd Edition (12th printing)](https://hastie.su.domains/ElemStatLearn/printings/ESLII_print12_toc.pdf);
 Trevor Hastie, Robert Tibshirani, Jerome Friedman

**Other references**:
- [A Course in Machine Learning](http://ciml.info); Hal Duame III
- Pattern Recognition and Machine Learning; Chris Bishop
- Machine Learning; Tom Mitchell
- Information Theory, Inference, and Learning Algorithms; David MacKay