---
layout: default
title: Projects
nav_order: 4
---

## Important Dates

- Mon., Oct. 23 at 11:59pm: Project Proposals
- Mon., Nov. 13 at 11:59pm: Project Milestone
- Weds., Dec. 6 from 1:30-3:00pm: Poster Session (location TBD)
- Mon., Dec. 11 at 11:59pm: Project Report

## Your Course Project

Your class project is an opportunity for you to explore an interesting sequence modeling problem in the context of a
real-world data set. We are providing some seed project ideas below. You can pick one of these ideas and explore the
data and algorithms within and beyond what we suggest. You can also use your own data/ideas, but, in this case, you have
to make sure you have the data available now and a nice roadmap, since a quarter is too short for a very open-ended and
uncertain research project.

Projects can be done by you as an individual, or in teams of two students. You can discuss your ideas and approach with
the instructors, but of course the final responsibility to define and execute an interesting piece of work is yours.

The final project is worth 40% of your grade, which will be split amongst four deliverables:

- A project proposal (feedback, but no grade), due on **October 23rd by 11:59pm**.
- A project milestone (10% of the final grade), due on **November 13th by 11:59pm**.
- A project poster presentation (10% of the final grade), on **December 6th from 1:30-3:00pm (class time)**.
- A final report (20% of the final grade), due on **December 11th by 11:59pm**.

Your project will be evaluated by three criteria:

- Technical Depth: How technically challenging was what you did?
- Scope: How broad was your project? How many aspects, angles, variations did you explore?
- Presentation: How well did you explain what you did, your results, and interpret the outcomes? Did you use the good
  graphs and visualizations? How clear was the writing?

The Technical Depth and Scope are complementary criteria, e.g., if you develop a single elaborate algorithm or model on
a single dataset, you may score high on depth but low on scope, while if you try many very simple methods on different
datasets, your scope would be higher but the depth lower.

To give you a sense of what we're expecting:

- A great project would involve constructing a model---one that synthesizes and goes beyond the various ideas from
  lecture and homework---tailored to your particular dataset with careful thought about how the model is trained and
  evaluated. It would involve a variety of analyses to stress test your model and justify your interpretation of the
  results. The presentation would clearly and concisely convey your results. An alternative great project would consider
  a range of modern sequence models and/or datasets and do a thoughtful and thorough analysis of the tradeoffs between
  the methods, with insights as to why and when certain methods perform better than others (rather than just leaderboard
  competition-style numbers comparing the methods without intuition/guidance added).
- An okay project would tweak a model, algorithm, and analysis from class and apply it to a new dataset. It would
  involve a few different checks to show that the model is appropriate and a nice report of your findings. (A better
  project would consider a range of modeling or algorithmic approaches covered in class and thoroughly study which
  performed best, and explain why.) The presentation would get the message across.
- A subpar project would simply apply existing techniques from existing packages to a dataset and do the bare minimum to
  get a result. The models and algorithms would have been covered in lectures or homeworks with the dataset considered
  not requiring any new insights. It might omit key steps of model checking and model criticism or have clear conceptual
  errors in the model and/or algorithm formulation. The presentation might be perfunctory.

## Project Proposal

You must turn in a project proposal on **October 23rd by 11:59pm via Gradescope**.

Read the list of available data sets and potential project ideas below. If you prefer to use a different data set, we
will consider your proposal, but you must have access to this data already, and present a clear proposal for what you
would do with it.

**Project proposal format**: Proposals should be **one page maximum**. Include the following information:

- Project title
- Data set
- Project idea. This should be approximately two paragraphs.
- Software you will need to write.
- Papers to read. Include 1-3 relevant papers. If you are doing something different then one of the suggested projects,
  you will probably want to read at least one of them before submitting your proposal.
- Teammate: will you have a teammate? If so, whom? Maximum team size is two students. One proposal per team.
- Milestone: What will you complete by the milestone? Experimental results of some kind are expected here.

## Project Milestone

A project milestone should be submitted on **November 13th by 11:59pm via Gradescope**. Your writeup should be 3 pages
maximum in [NeurIPS format](https://nips.cc/Conferences/2023/PaperInformation/StyleFiles), not including references (the
templates are for LaTex, if you want to use other editors/options please try to get close to the same format). You
should describe the results of your first experiments here. Note that, as with any conference, the page limits are
strict! Papers over the limit will not be considered.

## Poster Session

We will hold a poster session on **December 6th from 1:30-3:00pm (location TBD)**. Each team will be given a stand to
present a poster summarizing the project motivation, methodology, and results. The poster session will give you a chance
to show off the hard work you put into your project, and to learn about the projects of your peers.

Here are some details on the poster format:

- We will provide poster boards that are 40” (height) x 30” (wide).
- Suggested ways to make your poster:
    - Create a bunch of presentation slides (using powerpoint, beamer, etc), and print out each side on a piece of
      letter-sized paper. Then, put them all together on the provided poster board.
    - If you have access to a poster printer, you are welcome to create a single huge slide and print it out on a poster
      printer. However, you are not expected to have access to a poster printer, and you will not receive extra "
      presentation points" if you use this method.

## Project Report

Your final submission will be a project report on **Monday, December 11th at 11:59pm via Gradescope**.
Your writeup should be 8 pages maximum
in [NeurIPS format](https://nips.cc/Conferences/2023/PaperInformation/StyleFiles), not including references (the
templates are for LaTex, if you want to use other editors/options please try to get close to the same format). You
should describe the task you solved, your approach, the algorithms, the results, and the conclusions of your analysis.
Note that, as with any conference, the page limits are strict! Papers over the limit will not be considered.

## Project Ideas

The course staff has outlined several potential project ideas below. This should give you a sense of the datasets
available and an appropriate scope for your project. You can either pick one of these or come up with something of your
own to work on.

### Hierarchical/multiresolution representation learning

Real-world data usually have hierarchical structure which can be learned from data. However, many popular contrastive
and self-supervised representation learning methods do not take advantage of this hierarchical structure, especially for
sequence data. Propose a method to use hierarchical information for representation learning. Alternatively, take an
existing method that takes advantage of hierarchical information and design a series of targeted experiments to show how
it is learning hierarchical information.

- Background:
    - TS2Vec: Towards Universal Representation of Time Series by Yue et al., 2022
    - Sequence Modeling with Multiresolution Convolutional Memory by Shi et al., 2023
    - Contrastive Representation Learning: https://lilianweng.github.io/posts/2021-05-31-contrastive/
    - Self-supervised Representation Learning: https://lilianweng.github.io/posts/2019-11-10-self-supervised/
- Methods:
    - Representation learning
    - Contrastive learning
    - Deep learning

### Blind-deconvolution with State-Space Models and RNNs

Many time-series can be described as sequences of impulse response, where the system is subjected to a series of
external perturbations, resulting in a smoothed out signal that we observe. For example, in calcium imaging, we observe
calcium fluorescence that is the result of neuronal spikes. In continuous-glucose monitoring, we observe glucose rises
from food that the person consumes. The inverse problem, where we seek to infer the impulse from the observed signal is
known as blind deconvolution. Using what you learned from this course, propose a new method (or implement an existing
method) to do blind deconvolution on a synthetic or real-world dataset.

- Background:
    - Blind deconvolution of sparse but filtered pulses with linear state space models, by Zalmai et al., 2016.
    - Discrete flow posteriors for variational inference in discrete dynamical systems, by Aitchison et al., 2018 (See
      Figure 2C)
- Methods:
    - State-space systems
    - Recurrent neural networks
    - Probabilistic inference

### Explainability in Sequence Models
- The rising complexity and adoption of deep learning models, particularly sequence models, in critical domains like healthcare and finance, have intensified the need for model explainability to ensure transparent, fair, and accountable AI systems. The goal of this project is to explore existing explainability methods with sequence models. Fit a sequence model on a couple of datasets (simulated or real-world), and compare and contrast FIT, an explainability method specifically designed for temporal data, with at least two other baseline methods (e.g. Deep-Lift, Integrated gradient, LIME, Feature Occlusion). Examine the results by visualizing which parts of the input sequences are most influential for predictions.
- Background
  - FIT (https://arxiv.org/pdf/2003.02821.pdf; https://github.com/sanatonek/time_series_explainability/tree/master)
  - Deep-Lift (https://arxiv.org/pdf/1704.02685.pdf)
  - Integrated gradient (https://arxiv.org/pdf/1703.01365.pdf)
  - LIME (https://arxiv.org/pdf/1602.04938.pdf)
  - Feature Occlusion (https://arxiv.org/pdf/1705.08498.pdf)
  - See https://captum.ai/api/ for implementation of baseline methods
- Methods
  - Recurrent neural networks, Transformers
  - Explainability methods
- Example Dataset
  - https://ai.stanford.edu/~amaas/data/sentiment/
  - Other datasets used in selected papers above

### Multimodal Sequence Modeling
- Multimodal sequence modeling, which involves integrating information from diverse data sources like text, audio, and images, is pivotal in harnessing the full spectrum of insights embedded in complex, real-world data. It poses several challenges, including the alignment of different modalities, the fusion of heterogeneous data sources, the management of disparate data dimensions and temporal resolutions. The goal of this project is to explore methods for integrating and analyzing diverse data types, such as text, audio, and images, in a unified model. Choose a multimodal sequence model (or propose your own architecture) and apply it to a multimodal dataset. Design experiments to examine how using multiple modalities, in contrast to using each of the modalities alone, affects the performance of your model. An ideal comparison should consider the model size, dataset size, and computational costs.
- Background
  - m-RNN (https://arxiv.org/pdf/1412.6632.pdf; https://github.com/mjhucla/TF-mRNN)
  - MulT (https://arxiv.org/pdf/1906.00295.pdf; https://github.com/yaohungt/Multimodal-Transformer)
  - MultiModal-InfoMax (https://arxiv.org/pdf/2109.00412.pdf; https://github.com/declare-lab/MSA-Robustness/tree/2466d33c767411f6490c8c022666e8d9167696b9/Multimodal-Infomax)
- Methods
  - Recurrent neural networks, Transformers 
- Example Dataset
  - https://github.com/drmuskangarg/Multimodal-datasets
  - http://multicomp.cs.cmu.edu/resources/cmu-mosi-dataset/
  - Other datasets used in selected papers above

### Comparing Discrete and Continuous-Time Models for Sequential Data

The literature on building models for sequential data has studied two types of models – discrete-time models (e.g.,
RNNs, LSTMs, transformers) and continuous-time models (e.g., neural ODE). Discrete-time models typically can be viewed
as discretizing some continuous-time process, such as an ODE, and the two types of modelling approaches can sometimes be
combined to produce hybrid methods that are more suitable to bespoke applications.
In this project, you are tasked to compare methods for discrete-time and continuous-time modelling on your chosen
benchmark datasets. You should choose at least one discrete-time method and one continuous-time method and compare the
two approaches on chosen benchmark datasets. You will need to compare their task performances and computational
complexity (both speed and memory).

- Background
    - https://arxiv.org/abs/1806.07366
    - https://arxiv.org/abs/2111.00396
    - https://proceedings.mlr.press/v202/shi23f.html
    - https://epubs.siam.org/doi/pdf/10.1137/S1064827501380630
    - https://arxiv.org/abs/2005.08926
    - https://arxiv.org/abs/1907.03907
- Methods
    - RNN, LSTM
    - Transformers
    - Neural ODE, CDE, SDE
    - S4, HiPPO
    - Backprop, adjoint sensitivity method
- Datasets
    - Long Range Arena: https://arxiv.org/abs/2011.04006
    - UEA time series classification archive https://arxiv.org/abs/1811.00075
    - PhysioNet 2019 challenge https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6964870/
    - Other datasets in selected papers above

### Is Attention Necessary for Time-Series Modeling?

The literature has seen mixed results for modelling time-series data with the attention-based transformer architecture.
Some works claim that simple non-attention-based architectures can be more effective than vanilla transformers on
benchmark tasks, while others try to justify the effectiveness of transformers over non-transformer models.
In this project, you are tasked to compare transformer-based and non-transformer-based models on your chosen benchmark
datasets. You should choose at least one transformer-based model and one non-transformer-based model and compare the two
approaches on chosen benchmark datasets. The scale of the model size, dataset size, and computational resources all
matter, and your comparison should control for these factors. You should also control for hyper-parameter tuning. An
ideal empirical evaluation should compare approaches across different scales (to derive scaling laws). Theoretical
results are not required, but you are encouraged to also study the theoretical limitations of each paradigm (e.g.,
modelling capacity).

- Background
    - https://arxiv.org/abs/2205.13504
    - https://arxiv.org/pdf/2106.13008.pdf
    - https://huggingface.co/blog/informer
    - https://huggingface.co/blog/autoformer
    - https://proceedings.mlr.press/v202/shi23f/shi23f.pdf
- Methods
    - Transformers; variants of transformers for modeling time-series
    - S4, HiPPO
- Datasets
    - See datasets in selected papers above

### Energy forecasting
This project is taken from a Kaggle contest run by the IEEE Power and Energy society. The goal is to predict the total energy load for a US utility across multiple zones, as well as the sum of the energy load across all these zones, based on temperature data.

- Data: datasets

- Task: Predict the hourly energy load across different zones of the US. (Note that the labels for the weeks meant to be predicted in the original contest are no longer available, so you should choose a random subset of other weeks to use as a test set.)

- Background: https://www.kaggle.com/competitions/global-energy-forecasting-competition-2012-load-forecasting/overview/description

- Methods: HMM, state space models (see https://robjhyndman.com/papers/kaggle-competition.pdf for another team’s approach).

### Neuroscience
(Neural Dynamics and Functional Connectivity) In addition to studying neural dynamics, a large research area in neuroscience is understanding how neural systems interact with each other. This is useful in understanding the pathways involved when the brain executes a complex task. Given time series data about the activity in each region of the brain, for example, EEG data or functional MRI data, how can you determine which signals in a certain system affect other signals in a different region of the brain? Granger causality is a way of inferring lagged, directed connections between regions. Graphical models can uncover instantaneous, undirected connectivity. A project here would be to learn about these types of methods and apply them to a neuroscience (or other proxy) dataset.

- Datasets: https://www.ieeg.org

- Background references: 
  - https://www.sciencedirect.com/science/article/pii/S0959438818301570?via%3Dihub
  - https://arxiv.org/abs/2105.02675

- Papers that are examples of the project ideas above:

  - https://arxiv.org/abs/1402.6951
  - https://arxiv.org/pdf/1802.05842.pdf
  - https://www.tandfonline.com/doi/full/10.1080/01621459.2018.1476238

### Environmental Data

(Air Quality Index data) The Air Quality Index is a measure that is important not only in California but in other large metropolitan areas with high smog rates. It’s important to forecast the air quality index in a specific location, say Santa Clara county, so that at-risk populations can prepare. Can you use the time series models we studied in class to forecast AQI? How would you incorporate the spatio temporal aspect of the data? Using AQI data in adjacent locations might help in time series forecasting; how would you incorporate this in your model? Can you use other information such as wildfire data or weather data to help forecast AQI?

(Global Temperature Forecasting) The IPCC released an unequivocal 2021 report on the human impacts on global warming: there is little doubt that the past century of unprecedented warming has been a result of human activity. Using historical temperature data, can basic time series methods quantify how unusual the past century of warming has been? Another aspect of the project is to forecast temperatures beyond the current year; can these be improved using auxiliary data such as human industrial activity, carbon emissions, or certain weather patterns like El Nino? How do your methods compare to the estimates given in the IPCC report; do they improve those predictions in any way?

- Data sources:
  - https://www.epa.gov/outdoor-air-quality-data
  - https://climatedataguide.ucar.edu/climate-data/global-temperature-data-sets-overview-comparison-table

- References:

  - Intelligent modeling strategies for forecasting air quality time series: A review, Liu et al. 2021
  - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6164777/

### Financial Time Series

(Stochastic Volatility) Practitioners also care a lot about forecasting volatility, which is the variance of stock prices. Higher volatility is useful for financial institutions as trading during those periods can mean increased opportunities; it also provides increased liquidity to exit out of large positions. Volatility is also intimately related with option pricing. A common time series model for volatility is the GARCH family of models. A project here would learn about and present GARCH modeling (which is a topic we have not covered in class), apply it to forecasting the variance of a certain asset, or other financial time series (stock price volatility, interest rates, etc). For example, fit an ARCH and GARCH model to your selected data. How does this compare to using methods we have seen in class, including ARMA models, state space models, etc?

(Pairs Trading) A certain strategy called pairs trading tries to capitalize on short term price dispersions between assets that should behave similarly. For example, stocks in the same industry selling similar products are expected to behave similarly, statistically speaking. When the prices diverge, you place a bet that they will eventually converge again and behave similarly. There are multiple ways of quantifying similarity between time series. For example, price difference / price ratio can be modeled by a stationary, mean reverting process, such as an OU process (a type of Gaussian process). A project here could be to identify such a pairs trade, fit an OU process model to it, and test whether the difference reverts to the mean frequently. Can you forecast the next reversion time? Another related project is to identify good pairs trades by statistical tests, such as Cross correlation, Cointegration, or Granger causality. You would learn about and apply these concepts to finding such trades. How do each of these methods compare for generating good pairs trades?

- Data sources: Google Finance, Yahoo Finance.

- References:

  - For GARCH modeling: See ch. 5 of textbook “Statistics and Data Analysis for Financial Engineering: With R Examples, Ruppert and Matteson”.
  - For a survey of GARCH usage in finance and econometrics, see “Garch 101: The use of ARCH/GARCH Models in Applied Econometrics, Engle 2001".
  - For pairs trading, the below articles provide an implementation overview of the strategy. There are also academic papers linked within these sources.
    - https://quantpedia.com/strategies/pairs-trading-with-stocks/
    - https://hudsonthames.org/an-introduction-to-cointegration/
    - https://hudsonthames.org/optimal-stopping-in-pairs-trading-ornstein-uhlenbeck-model/
