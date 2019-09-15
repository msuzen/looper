# `A resource list for causality in statistics, data science and physics.`

## Books

Reverse chronological order, both technical and popular.

* Pearl and Mackenzie
  The Book of Why: The New Science of Cause and Effect (2018)
  [amzn](https://www.amzn.com/dp/046509760X)

* Hernán & Robins
  Causal Inference (2018)
  [online](http://bit.ly/2mSeeXI)

* Rosenbaum
  Observation and Experiment: An Introduction to Causal Inference (2017)
  [amzn](https://www.amzn.com/dp/067497557X/)

* Jonas Peters, Dominik Janzing and Bernhard Schoelkopf
  Elements of Causal Ingerence: Foundations and Learning Algorithms (2017)
  [mitpress](https://mitpress.mit.edu/books/elements-causal-inference)

* Pearl, Glymour and Jewell,
  Causal Inference in Statistics: A Primer (2016)
  [amzn](https://www.amzn.com/dp/1119186846)

* Morgan & Winship,
  Counterfactuals and Causal Inference (2nd edition) (2015)
  [amzn](https://www.amzn.com/dp/1107694167)

* Causal Inference for Statistics, Social, and Biomedical Sciences: 
  An Introduction, Imbens & Rubin, (2015)
  [amzn](https://www.amzn.com/dp/0521885884)
  
* Inference and Intervention: Causal Models for Business Analysis
  Michael D. Ryall and Aaron L. Bramson (2013)
  [amzn](https://www.amzn.com/dp/0415657598)

* Angrist & Pischke 
  Mostly Harmless Econometrics (2009)
  [amzn](https://www.amzn.com/dp/0691120358/)
  [princeton](https://press.princeton.edu/titles/8769.html)

* Judea Perl 
  Causality: Models, Reasoning and Inference (2009) 2nd Edition
  [amzn](https://www.amz.com/dp/052189560X)
  
* Econometric Causality, 
  James J. Heckman
  International Statistical Review (2008), 76, 1, 1–27 
  [doi](http://dx.doi.org/10.1111/j.1751-5823.2007.00024.x)
  
* Rosenbaum  
  Observational Studies (Springer Series in Statistics) 2nd Edition  (2002)
  [amzn](https://www.amzn.com/dp/0387989676)

  

## Papers

* Theoretical Impediments to Machine Learning With Seven Sparks 
  from the Causal Revolution, Judea Pearl
  [arXiv:1801.04016](https://arxiv.org/abs/1801.04016)

* Automated versus do-it-yourself methods for causal inference: 
  Lessons learned from a data analysis competition
  Vincent Dorie†, Jennifer Hill, Uri Shalit, Marc Scott, and Dan Cervone
  [https://arxiv.org/pdf/1707.02641.pdf](https://arxiv.org/pdf/1707.02641.pdf)
  
* Brodersen KH, Gallusser F, Koehler J, Remy N, Scott SL. 
  Inferring causal impact using Bayesian structural time-series models. 
  Annals of Applied Statistics, (2015), Vol. 9, No. 1, 247-274. 
  [link](http://research.google.com/pubs/pub41854.html)

* Introduction to Causal Inference
  Peter Spirtes
  (2010) [jmlr](http://www.jmlr.org/papers/v11/spirtes10a.html)

* Causal inference in statistics:An overview 
  Judea Pearl. (2009) [doi](http://dx.doi.org/10.1214/09-SS057)

* Rubin, D. B. (1974). Estimating causal effects of treatments 
  in randomized and nonrandomized studies. 
  Journal of Educational Psychology, 66(5), 688-701.
  [doi](http://dx.doi.org/10.1037/h0037350)
  
* Haavelmo, T. (1943). 
  The statistical implications of a system of simultaneous equations. 
  Econometrica, 11, 1–12.
  [jstor](http://links.jstor.org/sici?sici=0012-9682%28194301%2911%3A1%3C1%3ATSIOAS%3E2.0.CO%3B2-N)

## Software

* dagR: Directed Acyclic Graph with R
  [CRAN](https://cran.r-project.org/web/packages/dagR/index.html)[doi](http://dx.doi.org/10.1097/EDE.0b013e3181e09112)

* An R package for causal inference using Bayesian structural 
  time-series models 
  [CausalImpact](https://google.github.io/CausalImpact/CausalImpact.html)
  [CRAN](https://cran.r-project.org/package=CausalImpact)

* Python package [causalinference](https://github.com/laurencium/causalinference) [Vignette](https://github.com/laurencium/causalinference/blob/master/docs/tex/vignette.pdf)

* Tetrad Project: Graphical Causal Models [homepage](http://www.phil.cmu.edu/tetrad/)

* PyPhi: A toolbox for integrated information theory [arXiv](https://arxiv.org/abs/1712.09644)

## MOOCs

* A Crash Course in Causality: Inferring Causal Effects from Observational Data [link](https://www.coursera.org/learn/crash-course-in-causality)

* Measuring Causal Effects in the Social Sciences [link](https://www.coursera.org/learn/causal-effects)
 
## Quotes: Prediction and Causation

* " Actually correlation lets you make predictions 
   in many cases, assuming you're making prediction 
   about the world as reflected in your data. 
   For example, correlations between photos and 
   their labels allows you usually to make predictions 
   about new photos. 

   The problem gets difficult if you want to predict the 
   effects of actions taken in a different manner from 
   that which exists in your data. For example, if you 
   want to consider different treatment strategies for 
   cancer using data from past cancer patients, only 
   correlations will usually not suffice as you're 
   trying to predict counterfactual that might not exist in your data."
   Uri Shalit, Technion (Forum Communication 01/2018)

*  Reply to Uri: 

    "You don't have to have correlation to make a prediction in any case.  
    Chicken entrails used to suffice, and still do some places.  
    I would argue that chicken entrails might actually be better 
    than relying purely upon correlation if you know nothing 
    about any causality involved.

     Only if the correlation is the result of causality will 
     you be able to trust a prediction using correlation.  
     This is where the "science" in "data science" usually disappears, 
     as exemplified in your post."

     Recall, Fisher himself (while employed by the tobacco industry) 
     claimed that any link between lung cancer and smoking was mistaking 
     correlation for causality.  Of course, Fisher, a life long smoker, 
     died from lung cancer also.  Talk about causality bites, 
     predicting Fisher's means of death via the correlation would 
     have been trustable."
     Mark Powell, Austin (Forum Communication 01/2018)

## Quotes: Rubin vs. Pearl

* " Rubin and Pearl are kind of "academic enemies". 
  Though neither completely dismisses the other, 
  they both make snide remarks about the other's work. 
  Pearl shows in his book exactly how Neyman-Rubin 
  potential outcomes can be derived from causal graphs. 
  As far as I know Rubin never really makes an 
  attempt to address Pearl's ideas directly. 
  However, Rubin, being a statistician, made 
  significant contributions to the practice of real-world 
  causal inference, which go beyond Pearl's interests. 
  Jamie Robins also made seminal contributions to this subject.
  You can read some of the debate on Andrew Gelman's blog 
  [here](http://andrewgelman.com/2009/07/05/disputes_about/)
  Pearl writes in the comment section and in that blog  
  post there are links to follow up posts. "
  Uri Shalit, Technion (Forum Communication 01/2018)

## Quotes: On the Pearl's Philosopy

* "..while Pearl's work is foundational, and its importance  
  cannot be overstated, his published work is often 
  insufficient in addressing the real-world problems of 
  many data scientists. The reason is that Pearl is mostly 
  concerned with the problem of identification, i.e. which data 
  generating processes allow us to infer causation from observed data. 
  He is less concerned with the statistical problem of actually 
  inferring these purported causal relationships from data. 
  This is especially true if the data is high-dimensional 
   or noisy (Pearl usually considers a few binary or Gaussian variables)."
  Uri Shalit, Technion (Forum Communication 01/2018)
