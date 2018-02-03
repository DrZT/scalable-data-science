# SDS-2.2

**Scalable Data Science from Atlantis**, *A Big Data Course in Apache Spark 2.2*

Welcome! This is [a 2017 Uppsala Big Data Meetup](https://www.meetup.com/Uppsala-Big-Data-Meetup) of a fast-paced PhD course sequel in data science.

Most lectures are live via HangoutsOnAir in Youtube at [this channel](https://www.youtube.com/channel/UCPJ5ALbDtuCA4DJmN3GvanA) and archived in [this playlist](https://www.youtube.com/playlist?list=PL_I1mOIPmfpawQcs9l1vYfh50RhK_UJfY). We are not set up for live interactions online.

There are two parts to the course sequel: 

1. Introduction to Data Science
2. Fundamentals of Data Science

## Uppsala University Students

[Introduction to Data Science](http://www.teknat.uu.se/digitalAssets/395/c_395062-l_3-k_introduction-to-data-science_red2.pdf) and [Fundamentals of Data Science](http://www.teknat.uu.se/digitalAssets/395/c_395062-l_3-k_fundamentals-of-data-science2.pdf) is a *"big data"* sequel that will introduce researchers from various scientific and engineering disciplines to the rapidly growing field of data science and equip them with the latest industry-recommended open sourced tools for extracting insights from large-scale datasets through the complete data science process of collecting, cleaning, extracting, transforming, loading, exploring, modelling, analysing, tuning, predicting, communicating and serving. 

## Support
The course is supported by databricks academic partners programme ([databricks](https://databricks.com) is the UC, Berkeley startup founded by the creators of [Apache Spark™](http://spark.apache.org), a fast and general engine for large-scale data processing) and [Amazon Web Services Educate](https://aws.amazon.com/education/awseducate), and aims to train data scientists towards being able to meet the current needs of Stockholm's data industry through feedback from the AI and Data Analytics Centre of Excellence at [Combient AB](https://combient.com), an industrial joint venture between 21 large companies in Sweden and Finland.


## Overview of Data Science Courses 
Data Science is the study of the generalizable extraction of knowledge from data in a practical and scalable manner.  A data scientist is characterized by an integrated skill set spanning mathematics, statistics, machine learning, artificial intelligence, databases and optimization along with a deep understanding of the craft of problem formulation to engineer effective solutions ([DOI:10.1145/2500499](http://dl.acm.org/citation.cfm?id=2500499), [DOI: 10.1126/science.aaa8415](http://science.sciencemag.org/content/349/6245/255.full-text.pdf+html)).  This course will introduce students to this rapidly growing field and equip them with some of its basic principles and tools.  

In particular, in *Introduction to Data Science*, they will be introduced to basic skills needed to collect, store, extract, transform, load, explore, model, evaluate, tune, test and predict using large structured and unstructured datasets from the real-world. 
The course will use the latest, open-sourced, fast and general engine for large scale data processing. 
Various common methods will be covered in-depth with a focus on the student’s ability to execute the data science process on their own through a course project (in *Fundamentals of Data Science*).

**Target group/s and recommended background**

Students are recommended to have basic knowledge of algorithms and some programming experience (equivalent to completing an introductory course in computer science), and some familiarity with linear algebra, calculus, probability and statistics. 
These basic concepts will be introduced quickly and one could take the course by putting extra effort on these basics as the course progresses. 
Successful completion of the course on *Introduction to Data Science* or equivalent and an interest in doing a course project in a small team is a prerequisite for *Fundamentals of Data Science*.


## Introduction to Data Science

**Contents, study format and form of examination** 

The course will cover the following contents:
- key concepts in distributed fault-tolerant storage and computing, and working
knowledge of a data scientist’s toolkit: Shell/Scala/SQL/Python/R, etc.
- practical understanding of the *data science process*:
  - ingest, extract, transform, load and explore structured and unstructured datasets
  - model, train/fit, validate/select, tune, test and predict (through an estimator) with a practical understanding of the underlying mathematics, numerics and statistics
  - communicate and serve the model’s predictions to the clients
- practical applications of predictive models for classification and regression, using case-studies of real datasets
 
There will be assignments involving computer programming and data analysis. The grade is based on attendance, course participation and successful completion of programming assignments.

## Fundamentals of Data Science

**Contents, study format and form of examination** 

The course will cover the following contents:
- key concepts in distributed fault-tolerant filestores and in-memory computing
- understanding the *data science process* (the underlying mathematics, numerics and statistics as well as concerns around privacy and ethics at a deeper level)
- applications of current predictive models and methods in data science to make/take common decisions/actions, including classification, regression, anomaly detection and recommendation, using case-studies of real datasets
- apply the data science process to one’s own case study and work collaboratively in a group (course project).

There will be assignments involving computer programming and data analysis, and written and oral presentation of the course project. The grade will be based on attendance, course participation, successful completion of programming assignments and the final course project.

The *course project* could take one of the following forms:
- analyzing an interesting dataset  using  existing  methods 
- obtaining your own dataset and analyzing it using existing methods 
- building  your  own  data  product  
- focussing on the theoretical properties of an algorithm, etc.
  
Students are encouraged to work in teams of two or three for a project.  
The project should be orally presented during the first week of January 2018 and made avaialable as a written report with all source codes and explanations.
Assignments, on the other hand, are to be completed individually.

## Outline of Topics 

**The exact set of topics may change slightly from the *tentative* outline below in order to cater better to the registered students at Uppsala University.**
{: .notice--danger}

1.  Introduction:  What is Data Science?
	-  Big Data and Data Science - beyond buzz-words
		- fault tolerance and distributed file-stores
		- distributed in-memory processing in Apache Spark
	-  History and latest landscape of research and practice
	-  Skill sets of a data scientist (maths, stats, computer science and software engineering)
	-  The Data Science Process
2. Basics of Probability, Statistics, Linear Algebra, Calculus and Programming
	-  Populations and samples - basic concepts (random variables, density and distribution functions)
	-  Simulate from basic discrete and continuous distributions (python/scala/R)
	-  Refresher in Linear Algebra (numpy, scala-breeze, R)
	-  concepts in model selection and tuning via cross-validation and testing
	-  Statistical modeling and fitting a model (linear regression, least squares/maximum likelihood, gradient descent)
	-  Shell command-line and crash-course/refresher in basic programming (python/scala/R)
3. Introduction to Map-Reduce and Distributed Computing
	-  Resilient Distributed datasets
	-  Transformations and Actions in Apache Spark (Introduction)
	-  Basics of Functional programming (python lambda functions and scala closures)
	-  Case Study 0: Word-count of US State of the Union Addresses
4. Ingest, Extract, Transform, Load and Explore with noSQL
	-  Case Study 0: US State of the Union Addresses
	-  Case Study 1: Power-plant data 
	-  Case Study 2: 1 Million Songs
	-  SQL basics - select, filter, join, group by, aggregate, etc. using SparkSQL
5. Two Basic Supervised Machine Learning Algorithms
	-  Linear Regression (power-plant data)
	-  Decision Trees for Classification (hand-written digit recognition)
6. Two Basic Unsupervised Machine Learning Algorithms 
	-  k-means (1 million songs dataset)
	-  Gaussian Mixture Models and EM Algorithm
7. Unstructured to Semi-structured text data
	-  Supervised: Sentiment analysis with Support vector Machine (twitter dataset)
	-  Unsupervised: Latent Dirichlet Allocation (news groups dataset)
	- Assignment: Build your own sentiment detector
8. Dimensionality Reduction
	- Distributed Linear Algebra -- basic concepts
	- Singular value Decomposition
	- Principal Component Analysis 
9. Collaborative Filtering for Recommendation Systems
	-  Matrix completion via Alternative Least Squares
	-  Assignment:  build your own recommendation system
10. Neural networks
	- Linear and logistic regression as neural networks
	- Back propagation for gradient descent
	- Use of pre-trained neural networks from google/Baidu/facebook in your machine learning pipeline
11. Mining Networks and Graphs
	-  Social networks as graphs (twitter data)
	-  Extract, transform and loading of network data
	-  Discovery of communities in graphs (wikipedia click streams)
	-  label and belief propagation
	-  querying sub-structures in graphs (US Airport network)
12. Data Science and Ethical Issues
	-  Discussions on ethics, privacy and security
	-  Case studies from the field
13. Project Presentations

# What was actually covered

*  [Introduction](gb/sds-2-2/000_scalableDataScience.md)
*  [Why Spark?](gb/sds-2-2/001_whySpark.md)
*  [Login to databricks](gb/sds-2-2/002_loginToDatabricks.md)
*  [Scala Crash Course](gb/sds-2-2/003_scalaCrashCourse.md)
*  [RDDs](gb/sds-2-2/004_RDDsTransformationsActions.md)
*  [RDDs HOMEWORK](gb/sds-2-2/005_RDDsTransformationsActionsHOMEWORK.md)
*  [Word Count - SOU](gb/sds-2-2/006_WordCount.md)
*  [Spark SQL Basics](gb/sds-2-2/007_SparkSQLIntroBasics.md)
*  [ETL Diamonds Data](gb/sds-2-2/008_DiamondsPipeline_01ETLEDA.md)
*  [ETL Power Plant](gb/sds-2-2/009_PowerPlantPipeline_01ETLEDA.md)
*  [Wiki Click streams](gb/sds-2-2/010_wikipediaClickStream_01ETLEDA.md)
*  [Simulation Intro](gb/sds-2-2/011_02_IntroToSimulation.md)
*  [Machine Learning Intro](gb/sds-2-2/011_03_IntroToML.md)
*  [K-Means 1MSongs Intro](gb/sds-2-2/012_UnsupervisedClustering_1MSongsKMeans_Intro.md)
*  [1MSongs - 1 ETL](gb/sds-2-2/013_UnsupervisedClustering_1MSongsKMeans_Stage1ETL.md)
*  [1MSongs - 2 Explore](gb/sds-2-2/014_UnsupervisedClustering_1MSongsKMeans_Stage2Explore.md)
*  [1MSongs - 3 Model](gb/sds-2-2/015_UnsupervisedClustering_1MSongsKMeans_Stage3Model.md)
*  [Decision Trees for Digits](gb/sds-2-2/016_SupervisedClustering_DecisionTrees_HandWrittenDigitRecognition.md)
*  [Linear Algebra Intro](gb/sds-2-2/017_LAlgIntro.md)
*  [Linear Regression Intro](gb/sds-2-2/018_LinRegIntro.md)
*  [Distrib. Linear Algebra](gb/sds-2-2/019_DistLAlgForLinRegIntro.md)
*  [Power Plant - Model Tune Evaluate](gb/sds-2-2/020_PowerPlantPipeline_02ModelTuneEvaluate.md)
*  [Activity Detection - Random Forest](gb/sds-2-2/021_recognizeActivityByRandomForest.md)
*  [Graph Frames Intro](gb/sds-2-2/022_GraphFramesUserGuide.md)
*  [Ontime Flight Performance](gb/sds-2-2/023_OnTimeFlightPerformance.md)
*  [Spark Streaming Intro](gb/sds-2-2/024_SparkStreamingIntro.md)
*  [Extended Twitter Utils](gb/sds-2-2/025_a_extendedTwitterUtils2run.md)
*  [Tweet Transmission Trees](gb/sds-2-2/025_b_TTTDFfunctions.md)
*  [REST Twitter API](gb/sds-2-2/025_c_RESTTwitter.md)
*  [Tweet Collector](gb/sds-2-2/026_TweetCollector.md)
*  [Tweet Track, Follow](gb/sds-2-2/027_TweetCollectorTrackAndFollow.md)
*  [Tweet Hashtag Counter](gb/sds-2-2/028_TweetHashtagCount.md)
*  [Tweet Classifier](gb/sds-2-2/029_TweetLanguageClassifier.md)
*  [Power Plant - Model Tune Evaluate Deploy](gb/sds-2-2/030_PowerPlantPipeline_03ModelTuneEvaluateDeploy.md) 
*  [Geospatial Analytics in Magellan](gb/sds-2-2/031_GeospatialAnalyticsInMagellan.md)
*  [NY Taxi trips in Magellan](gb/sds-2-2/032_NYtaxisInMagellan.md)
*  [Old Bailey Online - ETL of XML](gb/sds-2-2/033_OBO_LoadExtract.md)
*  [20 Newsgroups - Latent Dirichlet Allocation](gb/sds-2-2/034_LDA_20NewsGroupsSmall.md)
*  [Cornell Movie Dialogs - Latent Dirichlet Allocation](gb/sds-2-2/035_LDA_CornellMovieDialogs.md)
*  [Movie Recommendation - Alternating Least Squares](gb/sds-2-2/036_ALS_MovieRecommender.md)
*  [Animal Names Streaming Files](gb/sds-2-2/037a_AnimalNamesStructStreamingFiles.md)
*  [Normal Mixture Streaming Files](gb/sds-2-2/037b_Mix2NormalsStructStreamingFiles.md)
*  [Structured Streaming Prog Guide](gb/sds-2-2/038_StructuredStreamingProgGuide.md)
*  [Graph Mixture Streaming Files](gb/sds-2-2/037c_Mix2RandomGraphStructStreamingFiles.md)
*  [Structured Streaming of JSONs](gb/sds-2-2/039_StructuredStreamingFromJSONFileStream.md)
*  [T-Digest Normal Mixture Streaming Files](gb/sds-2-2/040a_TDigestInputStream.md)
*  [Sketching with T-Digest](gb/sds-2-2/041_SketchingWithTDigest.md)
*  [Intro to Deep Learning](gb/sds-2-2/049_DeepLearningIntro.md)
*  [Outline for DL](gb/sds-2-2/050_DLbyABr_01-Intro.md)
*  [Neural Networks](gb/sds-2-2/051_DLbyABr_02-Neural-Networks.md)
*  [Deep feed Forward NNs with Keras](gb/sds-2-2/052_DLbyABr_02a-Keras-DFFN.md)
*  [Hello Tensorflow](gb/sds-2-2/053_DLbyABr_03-HelloTensorFlow.md)
*  [Batch Tensorflow with Matrices](gb/sds-2-2/054_DLbyABr_03a-BatchTensorFlowWithMatrices.md)
*  [Convolutional Neural Nets](gb/sds-2-2/055_DLbyABr_04-ConvolutionalNetworks.md)
*  [MNIST: Multi-Layer-Perceptron](gb/sds-2-2/056_DLbyABr_04a-Hands-On-MNIST-MLP.md)
*  [MNIST: Convolutional Neural net](gb/sds-2-2/057_DLbyABr_04b-Hands-On-MNIST-CNN.md)
*  [CIFAR-10: CNNs](gb/sds-2-2/058_DLbyABr_04c-CIFAR-10.md)
*  [Recurrent Neural Nets and LSTMs](gb/sds-2-2/059_DLbyABr_05-RecurrentNetworks.md)
*  [LSTM solution](gb/sds-2-2/060_DLByABr_05a-LSTM-Solution.md)
*  [LSTM spoke Zarathustra](gb/sds-2-2/061_DLByABr_05b-LSTM-Language.md)
*  [2017 Advise from Data Industry](adviseFromIndustry/AndrewMorgan.md)
*  [Potential Projects](gb/sds-2-2/998_01_PotentialProjectIdeas.md)
*  [2017 dbc ARCHIVES](gb/sds-2-2/dbcArchive.md)

# Supplements

We will be supplementing the lecture notes with reading assignments from original sources.  

Here are some resources that may be of further help.

### Mathematical Statistical Foundations
- Avrim Blum, John Hopcroft and Ravindran Kannan.  Foundations of Data Science. Freely available from: [https://www.cs.cornell.edu/jeh/book2016June9.pdf](https://www.cs.cornell.edu/jeh/book2016June9.pdf). It is  intended as a modern theoretical course in computer science and statistical learning.
- Kevin P. Murphy.  Machine Learning:  A Probabilistic Perspective.  ISBN 0262018020.  2013.
- Trevor  Hastie,  Robert  Tibshirani  and  Jerome  Friedman.   Elements  of  Statistical  Learning, Second Edition.  ISBN 0387952845.  2009.  Freely available from: [https://statweb.stanford.edu/~tibs/ElemStatLearn/](https://statweb.stanford.edu/~tibs/ElemStatLearn).

### Data Science / Data Mining at Scale
- Jure Leskovek,  Anand Rajaraman and Jeffrey Ullman.  Mining of Massive Datasets.  v2.1, Cambridge University Press.  2014.  Freely available from: [http://www.mmds.org/#ver21](http://www.mmds.org/#ver21).
- Foster Provost and Tom Fawcett.  Data Science for Business:  What You Need to Know about Data Mining and Data-analytic Thinking.  ISBN 1449361323.  2013.
- Mohammed J. Zaki and Wagner Miera Jr.  Data Mining and Analysis: Fundamental Concepts and Algorithms.  Cambridge University Press.  2014.
- Cathy  O’Neil  and  Rachel  Schutt.   Doing  Data  Science,  Straight  Talk  From  The  Frontline. O’Reilly.  2014.

Here are some free online courses if you need quick refreshers or want to go indepth into specific subjects.

### Maths/Stats Refreshers
* [Linear Algebra Refresher Course (with Python)](https://www.udacity.com/course/linear-algebra-refresher-course--ud953)
* [Intro to Descriptive Statistics](https://www.udacity.com/course/intro-to-descriptive-statistics--ud827)
* [Intro to Inferential Statistics](https://www.udacity.com/course/intro-to-inferential-statistics--ud201)

### Apache Spark / shell / github / Scala / Python / R
- Learning Spark : lightning-fast data analytics by Holden Karau, Andy Konwinski, Patrick Wendell, and Matei Zaharia, O'Reilly, 2015.
- Advanced analytics with Spark : patterns for learning from data at scale, O'Reilly, 2015.
- Command-line Basics
	* [Linux Commnad-line Basics](https://www.udacity.com/course/linux-command-line-basics--ud595)
	* [Windows Command-line Bascis](https://www.lynda.com/-tutorials/Windows-command-line-basics/497312/513424-4.html)

- [How to use Git and GitHub: Version control for code](https://www.udacity.com/course/how-to-use-git-and-github--ud775)
- [Intro to Data Analysis: Using NumPy and Pandas](https://www.udacity.com/course/intro-to-data-analysis--ud170)
- [Data Analysis with R by facebook](https://www.udacity.com/course/data-analysis-with-r--ud651)
- [Data Visualization and D3.js](https://www.udacity.com/course/data-visualization-and-d3js--ud507)
- [Scala Programming](http://www.scala-lang.org/documentation)
- [Scala for Data Science, Pascal Bugnion, Packt Publishing, 416 pages, 2016](http://shop.oreilly.com/product/9781785281372.do). 

### Computer Science Refreshers
* [Intro to Computer Science (with Python)](https://www.udacity.com/course/intro-to-computer-science--cs101)
* [Intro to Python Programming](https://www.udacity.com/course/programming-foundations-with-python--ud036)
* [Intro to Relational Databases](https://www.udacity.com/course/intro-to-relational-databases--ud197)

