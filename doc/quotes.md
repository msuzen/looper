
## Prediction and Causation

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

## Rubin vs. Pearl

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

## On the Pearl's Philosopy

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


