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

Sequence data and time series are becoming increasingly ubiquitous in fields as diverse as bioinformatics, neuroscience, health, environmental monitoring, finance, speech recognition/generation, video processing, and natural language processing.  Machine learning has become an indispensable tool for analyzing such data; in fact, sequence models lie at the heart of recent progress in AI like GPT3.  

This class integrates foundational concepts in time series analysis with modern machine learning methods for sequence modeling.  Connections and key differences will be highlighted.  You will learn theoretical fundamentals, but the focus will be on gaining practical, hands-on experience with modern methods through real-world case studies.  You will walk away with a broad and deep perspective of sequence modeling and key ways in which such data are not just 1D images. 

The course is divided into four modules: 
- Traditional time series methods
  - Stationarity, autocorrelation, and basic theoretical constructs
  - AR, MA, ARMA, and ARIMA/SARIMA models
  - Forecasting and maximum-likelihood-based estimation
  - State space models, including HMMs, filtering/smoothing, learning
- Deep learning-based sequence models
  - RNNs, gated RNNs, backpropagation through time
  - CNNs for sequence data
  - Transformers
- Advanced topics
  - Representation learning for time series
  - State-of-the-art sequence models
- Continuous-time modeling
  - Traditional models of event-based data (Poisson processes, Hawkes processes)
  - Neural temporal point processes
  - Neural ODEs and hybrid models

## Teaching team

{% assign instructors = site.staffers | sort: 'index' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Course Logistics

**When**: Class is Mondays and Wednesdays 1:30-2:50pm PST.

**Where**: Class will be in person in [Hewlett 201](https://campus-map.stanford.edu/?srch=Hewlett201).

**Links**:
- [Ed](https://edstem.org/us/courses/45827/discussion/):
  This is the main way that you and the teaching team should communicate: we will post all important announcements here, and you should ask all course-related questions here. For personal matters that you don’t wish to put in a private Ed post, you can email the teaching staff at `cs229b-aut2324-staff@lists.stanford.edu`.
- [Canvas](https://canvas.stanford.edu/courses/180581): The course Canvas page contains links and resources only accessible to students.
- [Gradescope](https://www.gradescope.com/courses/598920): We use Gradescope
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

- Homework Assignments (40%, 4 @ 10% each)
- Concept Quizzes (15%, 5 @ 3% each)
- Attendance at guest lectures (5%, 4 @ 1.25% each)
- Final Project (40%): Project midway (8%), Project presentation (8%), Project report (24%)

**Textbooks**:
- [Time Series Analysis and Its Application](https://link.springer.com/book/10.1007/978-3-319-52452-8); Schumway & Stoffer
- [Probabilistic Machine Learning](https://probml.github.io/pml-book/): [Advanced Topics](https://probml.github.io/pml-book/book2.html); Kevin Murphy
- [Deep Learning](https://www.deeplearningbook.org/contents/rnn.html); Goodfellow, Bengio, Courville
- Optional: [New Introduction to Multiple Time Series Analysis](https://link.springer.com/book/10.1007/978-3-540-27752-1); Lutkepohl
- Optional: [Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf); Bishop
