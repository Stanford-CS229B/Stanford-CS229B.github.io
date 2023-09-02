---
layout: default
title: Projects
nav_order: 4
---

## Important Dates
* Mon., May 1 at 11:59pm: Project Proposals 
* Mon., May 22 at 11:59pm: Project Milestone 
* Thurs., June 8 from 10am-12pm @ [Sequoia coutyard](https://www.google.com/maps/place/37°25'43.9%22N+122°10'20.5%22W/@37.428851,-122.172354,17z/data=!3m1!4b1!4m4!3m3!8m2!3d37.428851!4d-122.172354): Poster Session
* Mon., June 12 at 11:59am (yes, am): Project Report

## Your Course Project 

Your class project is an opportunity for you to explore an interesting machine learning problem in the context of a real-world data set. **We are providing some seed project ideas below.** You can pick one of these ideas, and explore the data and algorithms within and beyond what we suggest. **You can also use your own data/ideas**, but, in this case, you have to make sure you have the data available now and a nice roadmap, since a quarter is too short to explore a brand new concept.

Projects can be done by you as an individual, or in teams of two students. You can discuss your ideas and approach with the instructors, but of course the final responsibility to define and execute an interesting piece of work is yours.

The final project is worth 40% of your grade, which will be split amongst four deliverables:
- A project proposal (feedback, but no grade), due on May 1 (Mon) by 11:59pm.
- A project milestone (10% of the final grade), due on May 22 (Mon) by 11:59pm.
- A project poster presentation (10% of the final grade), on June 8 (Thu) from 10am-12pm at [Sequoia coutyard](https://www.google.com/maps/place/37°25'43.9%22N+122°10'20.5%22W/@37.428851,-122.172354,17z/data=!3m1!4b1!4m4!3m3!8m2!3d37.428851!4d-122.172354).
- A final report (20% of the final grade), due on June 12 (Mon) by 11:59am (yes, am).

Your project will be evaluated by three criteria:
- Technical Depth: How technically challenging was what you did?
- Scope: How broad was your project? How many aspects, angles, variations did you explore? 
- Presentation: How well did you explain what you did, your results, and interpret the outcomes? Did you use the good graphs and visualizations? How clear was the writing?

The Technical Depth and Scope are complementary criteria, e.g., if you develop a single elaborate algorithm or model on a small dataset, you may score high on depth but low on scope, while if you try many very simple methods on different datasets, your scope would be higher but the depth lower. 
 
## Project Proposal  

You must turn in a project proposal on **May 1st by 11:59pm via Gradescope**.

**Read the list of available data sets and potential project ideas below.** If you prefer to use a different data set, we will consider your proposal, but you must have access to this data already, and present a clear proposal for what you would do with it.  

**Project proposal format**: Proposals should be **one page maximum**. Include the following information:
* Project title
* Data set
* Project idea. This should be approximately two paragraphs.
* Software you will need to write.
* Papers to read. Include 1-3 relevant papers. If you are doing something different then one of the suggested projects, you will probably want to read at least one of them before submitting your proposal.
* Teammate: will you have a teammate? If so, whom? Maximum team size is two students. One proposal per team.
* Milestone: What will you complete by the milestone? Experimental results of some kind are expected here.
 
## Project Milestone  

A project milestone should be submitted on **May 22nd by 11:59pm via Gradescope**. Your write up should be **3 pages maximum** in [NeurIPS format](https://nips.cc/Conferences/2023/PaperInformation/StyleFiles), not including references (the templates are for LaTex, if you want to use other editors/options please try to get close to the same format). You should describe the results of your first experiments here. Note that, as with any conference, the page limits are strict! Papers over the limit will not be considered.
 
## Poster Session  

We will hold a poster session on **Thursday, June 8th from 10am-12pm at [Sequoia coutyard](https://www.google.com/maps/place/37°25'43.9%22N+122°10'20.5%22W/@37.428851,-122.172354,17z/data=!3m1!4b1!4m4!3m3!8m2!3d37.428851!4d-122.172354)**. Each team will be given a stand to present a poster summarizing the project motivation, methodology, and results. The poster session will give you a chance to show off the hard work you put into your project, and to learn about the projects of your peers. 

Here are some details on the poster format:
- We will provide poster boards that are 30x40. 
- Suggested ways to make your poster:
    - Create a bunch of presentation slides (using powerpoint, beamer, etc), and print out each side on a piece of letter-sized paper. Then, put them all together on the provided poster board.
    - If you have access to a poster printer, you are welcome to create a single huge slide and print it out on a poster printer. However, you are not expected to have access to a poster printer, and you will not receive extra "presentation points" if you use this method.
 
## Project Report  

Your final submission will be a project report on **Monday, June 12th at 11:59am (yes, am not pm) via Gradescope**. 
Your write up should be **8 pages maximum** in [NeurIPS format](https://nips.cc/Conferences/2023/PaperInformation/StyleFiles), not including references (the templates are for LaTex, if you want to use other editors/options please try to get close to the same format). You should describe the task you solved, your approach, the algorithms, the results, and the conclusions of your analysis. Note that, as with any conference, the page limits are strict! Papers over the limit will not be considered.
 
## Project Ideas  

The course staff has outlined several potential project ideas below. This should give you a sense of the datasets available and an appropriate scope for your project. **You can either pick one of these or come up with something of your own to work on**.

### Netflix Challenge

From 2006-2009, Netflix sponsored a competition to improve its movie recommendation system. Their system is based off of predicting what rating a user will give to a particular movie (using a 1-5 star system). In effect, what we have is a matrix where each row represents a user and each column represents a movie. Some elements are filled with past ratings, but most of them are unknown. Students can use matrix factorization or clustering methods to predict the missing values in this matrix.
   * **Data**: [Ratings](https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data)
   * **Task**: Predict users' ratings of movies they haven't seen.
   * **Background**: [netflixprize.com Wikipedia article](http://en.wikipedia.org/wiki/Netflix_Prize)
   * **Methods**: matrix factorization/SVD, collaborative filtering, clustering, side-information

### Energy forecasting

This project is taken from a Kaggle contest run by the IEEE Power and Energy society. The goal is to predict the total energy load for a US utility across multiple zones, as well as the sum of the energy load across all these zones, based on temperature data.
   * **Data**: [datasets](https://www.kaggle.com/competitions/global-energy-forecasting-competition-2012-load-forecasting/data)
   * **Task**: Predict the hourly energy load across different zones of the US. (Note that the labels for the weeks meant to be predicted in the original contest are no longer available, so you should choose a random subset of other weeks to use as a test set.)
   * **Background**: https://www.kaggle.com/competitions/global-energy-forecasting-competition-2012-load-forecasting/overview/description
   * **Methods**: HMM, state space models, boosting (see https://robjhyndman.com/papers/kaggle-competition.pdf for another team's approach).

### Document Clustering

Documents taken from sources like Wikipedia or the online discussion board [Usenet](http://en.wikipedia.org/wiki/Usenet) often have word choice that reflects the topic being dicussed -- for example, the word "clustering" is much more likely to show up in a document on Computer Science than one about motorcycles. Given the collection of words in a document, it should be possible to predict what subject it is contained in. Alternatively, we might want to try to find documents similar to the one in question: if someone is reading a Wikipedia article on classification, perhaps they would also like to know that there is an article on regression.
* **Data**: Usenet: [Original Useful Subsets](http://mlg.ucd.ie/content/view/22/) , Wikipedia: [Wikipedia dataset](http://www.cs.washington.edu/education/courses/cse599c1/13wi/datasets/smallwiki.zip)
* **Task**: Search for articles similar to an example, or divide the dataset into clusters.
* **Background**: KM Chapter 25
* **Methods**: unsupervised learning, K-Means, LDA, spectral clustering

### Digit Recognition

Implement handwriting recognition by classifying pictures (stored as pixel data) as the appropriate digit. This project is based off a tutorial ML competition hosted on [kaggle.com](http://www.kaggle.com/)
* **Data**: [Kaggle Dataset](http://www.kaggle.com/c/digit-recognizer/data)
* **Task**: Classify an image of a digit
* **Background**: [Kaggle Description MNIST database](http://www.kaggle.com/c/digit-recognizer)
* **Methods**: multinomial logistic regression, k-nearest neighbor, svm, PCA, cross-validation.

### Federalist Papers

This task involves the famous disputed federalist papers. Some of the papers we know who wrote them and others we do not. The task involves converting the text into a "bag of words" (see attached for more info) feature vector and then attempting to classify the remaining essays as Hamilton or Madison. Students can use cross validation to test predictive power on known essays. This project involves mining text, which may be a challenging component, but it shows a very cool connection between machine learning and history.
* **Data**: [Project Gutenberg](http://www.gutenberg.org/cache/epub/1404/pg1404.txt)
* **Task**: Classify disputed papers as Hamilton or Madison
* **Background**: [Background](https://courses.cs.washington.edu/courses/cse446/17wi/federalist.pdf)
* **Methods**: logistic regression, decision trees, PCA, cross-validation

### Job Salary Prediction

This is another task taken from a Kaggle competition. Given an advertisement for a job opening, the goal is to predict the starting salary for the job being posted. Much of the data about the ads is unstructured text (like the ad content itself), but some structured data is given as well. A tree of the geographic relationships between the job locations is also provided. 
* **Data**: [Kaggle Dataset](https://www.kaggle.com/c/job-salary-prediction/data)
* **Task**: Predict a salary from a job posting
* **Background**: [Kaggle Description](https://www.kaggle.com/c/job-salary-prediction)
* **Methods**: regression, dimensionality reduction, neural networks

### Eigenfaces

The goal of this task is to learn how to recognize faces. We have a set of pictures of 20 people in various directions and expressions, some of which have sunglasses. One major problem with image data is that our input features are individual pixels, which are high-dimensional but not terribly meaningful in isolation. Using PCA, we can decompose our images into eigenvectors, which are linear combinations of pixels (nicknamed "eigenfaces"). Students can explore different classification tasks, from determining the presence of sunglasses to identifying individuals.
* **Data**: [Faces Directory](http://www.cs.cmu.edu/afs/cs.cmu.edu/project/theo-8/faceimages/faces/)
* **Task**: Classify images of faces
* **Background**: [.PGM format specification](http://netpbm.sourceforge.net/doc/pgm.html)
* **Methods**: dimensionality reduction, PCA, SVM, neural networks

### Human activity recognition

Human activity recognition is the problem of classifying sequences of accelerometer data recorded by smart phones into known well-defined movements. It has numerous applications in healthcare as an assistive technology when ensemble with other technologies like IoT. The dataset is collected from 30 subjects, performing different activities with a smartphone to their waists. The data is recorded with the help of sensors (accelerometer and Gyroscope) in that smartphone. The goal is to classify sequences of sensor data into the human activities such as walking, walking upstairs, walking downstairs, sitting, standing and laying.

* **Data**: [Human Activity Recognition Using Smartphones Data Set](https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)
* **Task**: Time series multi-class classification task
* **Background**: [Related paper](https://www.ijrte.org/wp-content/uploads/papers/v8i1/A1385058119.pdf)
* **Method**: decision trees, SVM, recurrent neural network with LSTM
