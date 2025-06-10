# [A resource list for causality in statistics, data science and physics](https://github.com/msuzen/looper)

##### Table of Contents  
[Editor's Selection](#editors-selection).  
[Books](#books)   
[Papers general](#papers-general)  
[Causal Discovery](#causal-discovery)       
[Simpson's Paradox](#simpsons-paradox)   
[Machine Learning](#machine-learning)  
[Fairness](#fairness)  
[Physics](#physics)  
[Thesis](#thesis)  
[Reviews](#review)  
[Software](#software)  
[Datasets](#datasets)     
[MOOCs](#moocs)  
[Blog Posts](#blog-posts)  
[Quotes](#quotes)  
[Video Lectures](#video-lectures).  
[Academics](#academics).   
[Communities](#communities-conferences)  

## Editors Selection 
Repeating from other sections, Highly important    
Order from beginner to advanced.    

* Judea Pearl and Mackenzie.  
  The Book of Why: The New Science of Cause and Effect (2018).  
  [amzn](https://www.amzn.com/dp/046509760X) | [Pearl's additional links](http://bayes.cs.ucla.edu/WHY/)

* The Seven Tools of Causal Inference, with Reflections on Machine Learning.      
  Judea Pearl.     
  Communications of the ACM, March 2019, Vol. 62 No. 3, Pages 54-60.      
  [url](https://cacm.acm.org/magazines/2019/3/234929-the-seven-tools-of-causal-inference-with-reflections-on-machine-learning/fulltext)    
  [pdf-reprint](https://ftp.cs.ucla.edu/pub/stat_ser/r481-reprint.pdf).  
  [interview](https://www.youtube.com/watch?v=CsMV5o3hotY).  
  
* Causal Inference: History, Perspectives, Adventures, and Unification (An Interview with Judea Pearl).      
  Observational Studies, 8, 2, (2022), p1-14.       
  [url](https://muse.jhu.edu/article/867087) | [pdf](https://muse.jhu.edu/pub/56/article/867087/pdf).         

* Pearl, Glymour and Jewell.  
  Causal Inference in Statistics: A Primer (2016).   
  [amzn](https://www.amzn.com/dp/1119186846).   
  [Ch4-pdf](http://web.cs.ucla.edu/~kaoru/primer-ch4.pdf).     
  [tweet-solution-manual](https://twitter.com/yudapearl/status/1484023795811696642).    
  Self-study by Bruno Goncalves [github](https://github.com/DataForScience/Causality) 

* Nobel Memorial Economics Prize 2021 on causal discovery, scientific summary.     
  Answering Causal Questions Using Observational Data.   (2021)   
  (David Card, Joshua Angrist, and Guido Imbens)  
  [pdf](https://www.nobelprize.org/uploads/2021/10/advanced-economicsciencesprize2021.pdf).

* Causality, determinism, and physics.   
  Julio Geo-Banacloche.    
  American Journal of Physics 90, 809 (2022); [doi](https://doi.org/10.1119/5.0087017).  

* Causal diagrams for empirical research.    
  Judea Pearl (1995).     
  [jstor](https://www.jstor.org/stable/2337329) | [pdf-UCLA](http://bayes.cs.ucla.edu/R218-B.pdf).     
  `Reasoning on Graphs: d-seperation, back/front-door`    

* Paul W. Holland.     
  Statistics and Causal Inference.     
  Journal of the American Statistical Association.     
  Dec., 1986, Vol. 81, No. 396 (Dec., 1986), pp. 945-960 [jstor](https://www.jstor.org/stable/2289064). | [pdf-from-David-Bleie](https://www.cs.columbia.edu/~blei/fogm/2020F/readings/Holland1986.pdf)    
  `Paper that coins the term: Fundamental Problem of Causal Inference`
  `It means there is no way to observe causality on the single entity simultaneously.`       

* Probabilistic and Causal Inference: The Works of Judea Pearl.  (2022)    
  Editors: Hector Geffner,Rina Dechter,Joseph Y. Halpern.    
  ACM Books [doi](https://dl.acm.org/doi/book/10.1145/3501714).   
  `An excellent technical reviews of Pearlian approach to causal inference`    
   
## Books   

Reverse chronological order, both technical and popular.   


* Causal Artificial Intelligence   
  A Roadmap for Building Causally Intelligent Systems   
  Elias Bareinboim   (2025)    
  [causalai-book website](https://causalai-book.net/)   

* Applied Causal Inference Powered by ML and AI   
  V. Chernozhukov, C. Hansen, N. Kallus, M. Spindler, V. Syrgkanis (2024)  
  [offfical-web](https://causalml-book.org) | [pdf](https://causalml-book.org/assets/chapters/CausalML_book.pdf)  

* A Mathematical Introduction to Causality   
  Lecture Notes (2023)
  Patrick Forré and Joris M. Mooij
  [UvA's-pdf](https://staff.fnwi.uva.nl/j.m.mooij/articles/causality_lecture_notes_2023.pdf)

* A First Course in Causal Inference.  
  Peng Ding.  
  [arXiv](https://arxiv.org/abs/2305.18793) (2023)

* Applied Causal Inference   
  Uday Kamath, Kenneth Graham, Mitchell Naylor  (2023)   
  [online-version](https://appliedcausalinference.github.io) | [lean-pub](https://leanpub.com/appliedcausalinference)   

* Causal Artificial Intelligence: The Next Step in Effective Business AI  
  Judith Hurwitz, John Thompson  (2023)
  [amz](https://amzn.com/dp/1394184131)  
  
* Causal Inference & Discovery in Python.  (2023)  
  From Machine Learning & Pearlian Perspective. 
  Aleksander Molak.   
  [causalpython](https://causalpython.io). | [amz](https://amzn.com/dp/1804612987)   
  
* Causal Inference for Data Science.     
  Aleix Ruiz de Villa (2023)
  [manning](https://www.manning.com/books/causal-inference-for-data-science).  
  
* Causal Analysis.  
  Impact Evaluation and Causal Machine Learning with Applications in R.  
  Martin Huber (2023).      
  MIT Press [url](https://mitpress.mit.edu/9780262545914/causal-analysis/)  | R package [causalweight](https://cran.r-project.org/web/packages/causalweight/index.html) | [R examples](https://www.unifr.ch/appecon/en/assets/public/uploads/causal%20analysis%20-%20R%20examples.txt) | [academic page](https://www.unifr.ch/appecon/en/research/text-book-causal-analysis.html)
  
* Causal Inference in Python.       
  Matheus Facure.    
  [Oreilly](https://www.oreilly.com/library/view/causal-inference-in/9781098140243/) (2023).      
  
* Causal Inference for The Brave and True. (2022).  
   Matheus Facure.      
  [e-book](https://matheusfacure.github.io/python-causality-handbook/landing-page.html) | [github](https://github.com/matheusfacure/python-causality-handbook)  
  
* Probabilistic and Causal Inference: The Works of Judea Pearl.  (2022)    
  Editors: Hector Geffner,Rina Dechter,Joseph Y. Halpern.   
  ACM Books [doi](https://dl.acm.org/doi/book/10.1145/3501714).   

* Microeconometrics using Stata: Volume 2: Nonlinear Models and Causal Inference Methods. (2022).      
  Cameron, A. C., and P. K. Trivedi.        
  Stata Press [url](https://www.routledge.com/Microeconometrics-Using-Stata-Second-Edition-Volume-II-Nonlinear-Models/Cameron-Trivedi/p/book/9781597183628)

* Nick Huntington-Klein.     
  The Effect: An Introduction to Research Design and Causality (2021).        
  [bookdown](https://theeffectbook.net/index.html) | [amzn](https://amzn.com/dp/1032125780).      
  [code-supplement](https://github.com/NickCH-K/causalbook) | [datasets-R](https://cran.r-project.org/web/packages/causaldata/index.html).    
  
* Causal Machine Learning.  
  Robert Ness (2022-).  
  [in-progress](https://www.manning.com/books/causal-machine-learning)  | [lecture notes](https://bookdown.org/robertness/causalml/docs/)
  
* Causal Inference, The Mixtape.     
  Scott Cunningham.      
  Yale University Press [url](https://yalebooks.yale.edu/book/9780300251685/causal-inference/) | [online-version](https://mixtape.scunning.com) (2021)
  
* Hernán & Robins.  
  Causal Inference: What If (2020).  
  CRC Press.   
  [online](http://bit.ly/2mSeeXI) | [pdf](https://cdn1.sph.harvard.edu/wp-content/uploads/sites/1268/2021/01/ciwhatif_hernanrobins_31dec20.pdf).    
  [python supplement](https://github.com/jrfiedler/causal_inference_python_code)

* Brady Neal.   
  Introduction to Causal Inference from a Machine Learning Perspective. (2020).  
  [pdf](https://www.bradyneal.com/Introduction_to_Causal_Inference-Dec17_2020-Neal.pdf) 
  
* Kohavi, Ron, Diane Tang, and Ya Xu.    
  Trustworthy Online Controlled Experiments: A Practical Guide to A/B Testing.            
  Cambridge University Press. [www](https://experimentguide.com/). (2020).      

* Experimental Design : Causal Inference   
  Stefan Wager.  
  Class notes [pdf](https://statweb.stanford.edu/~owen/courses/363/stats361.pdf). 
  [url](https://statweb.stanford.edu/~owen/courses/363/).  

* Pearl and Mackenzie.  
  The Book of Why: The New Science of Cause and Effect (2018).  
  [amzn](https://www.amzn.com/dp/046509760X) | [Pearl's additional links](http://bayes.cs.ucla.edu/WHY/)

* Rosenbaum.  
  Observation and Experiment: An Introduction to Causal Inference (2017).  
  [amzn](https://www.amzn.com/dp/067497557X/).   
  
* Jonas Peters, Dominik Janzing and Bernhard Schoelkopf.   
  Elements of Causal Inference: Foundations and Learning Algorithms (2017).  
  [mitpress](https://mitpress.mit.edu/books/elements-causal-inference) | [pdf](https://library.oapen.org/bitstream/handle/20.500.12657/26040/11283.pdf).  

* Pearl, Glymour and Jewell.  
  Causal Inference in Statistics: A Primer (2016).  
  [amzn](https://www.amzn.com/dp/1119186846).   
  [Ch4-pdf](http://web.cs.ucla.edu/~kaoru/primer-ch4.pdf).     
  [tweet-solution-manual](https://twitter.com/yudapearl/status/1484023795811696642).  
  Self-study by Bruno Goncalves [github](https://github.com/DataForScience/Causality)    

* Mastering 'Metrics: The Path from Cause to Effect. (2015).          
  Angrist, J.D. and J.-S.Pischke.   
  Princeton University Press [url](https://press.princeton.edu/books/paperback/9780691152844/mastering-metrics)

* Morgan & Winship.  
  Counterfactuals and Causal Inference (2nd edition) (2015).  
  [amzn](https://www.amzn.com/dp/1107694167)  

* Causal Inference for Statistics, Social, and Biomedical Sciences.      
  An Introduction, Imbens & Rubin, (2015).   
  [amzn](https://www.amzn.com/dp/0521885884).  
  
* Why ask Why? Forward Causal Inference and Reverse Causal Questions.   
  Andrew Gelman & Guido Imbens      
  [doi](http://doi.org/10.3386/w19614) (2013)
  
* Inference and Intervention: Causal Models for Business Analysis.  
  Michael D. Ryall and Aaron L. Bramson (2013).  
  [amzn](https://www.amzn.com/dp/0415657598)

* Angrist & Pischke.     
  Mostly Harmless Econometrics (2009).  
  [amzn](https://www.amzn.com/dp/0691120358/).  
  [princeton](https://press.princeton.edu/titles/8769.html)
  
* Probabilistic Graphical Models: Principles and Techniques.  
  Daphne Koller and Nir Friedman.  (2009). 
  MIT Press.  
  [amzn](https://www.amzn.com/dp/0262013193).  
  [mit](https://mitpress.mit.edu/books/probabilistic-graphical-models)

* Judea Perl.   
  Causality: Models, Reasoning and Inference (2009) 2nd Edition.   
  [amzn](https://www.amzn.com/dp/052189560X).  

* Fundamentals of statistical causality (2007).   
  C. A. P. Dawid.    
  [pre-print research gate](https://www.researchgate.net/publication/242495222_Fundamentals_of_statistical_causality).    
  
*  Microeconometrics: Methods and Applications (2005).      
   Cameron, A. C., and P. K. Trivedi.      
   Cambridge: Cambridge University Press. [amz](https://www.amzn.com/dp/0521848059).       
   Chapter-4: Instrumental Variables section [Author's-copy](http://cameron.econ.ucdavis.edu/e240a/ch04iv.pdf).     
  
* Rosenbaum.   
  Observational Studies (Springer Series in Statistics) 2nd Edition  (2002).  
  [amzn](https://www.amzn.com/dp/0387989676)
  
* Causation, Prediction, and Search.   
  Peter Spirtes, Clark Glymour and Richard Scheines.   
  2nd Edition (2001).   
  [mit press](https://mitpress.mit.edu/books/causation-prediction-and-search-second-edition) | [pdf-research-gate](https://www.researchgate.net/publication/242448131_Causation_Prediction_and_Search)
  
* Structural Equations with Latent Variables.  
  Kenneth A. Bollen (1989).  
  [wiley](https://onlinelibrary.wiley.com/doi/book/10.1002/9781118619179).  
  [amzn](https://www.amzn.com/dp/0471011711).   


## Papers general 

* Causal inference for time series     
  Jakob Runge et. al.  
  Nature Reviews Earth & Environment volume 4, pages 487–505 (2023)   
  [doi](https://doi.org/10.1038/s43017-023-00431-y)   

* A Measure-Theoretic Axiomatisation of Causality.  
  Junhyung Park, Simon Buchholz, Bernhard Schölkopf, Krikamol Muandet.   
  [arXiv](https://arxiv.org/abs/2305.17139) (2023).  

* Double Machine Learning and Automated Confounder Selection -- A Cautionary Tale.  
  Paul Hünermund et. al. (2023) 
  [arXiv](https://arxiv.org/abs/2108.11294) | [talk](https://faculti.net/double-machine-learning-and-automated-confounder-selection/) |
  [Journal of Causal Inference](https://doi.org/10.1515/jci-2022-0078)
  
* Causal Inference and Data-Fusion in Econometrics.  
  Paul Hünermund (Maastricht University), Elias Bareinboim (Columbia University).   
  [arXiv:1912.09104](https://arxiv.org/abs/1912.09104). | [The Econometrics Journal, 2023](https://doi.org/10.1093/ectj/utad008)

* Phenomenological Causality.    
  Dominik Janzing, Sergio Hernan Garrido Mejia (2022).     
  [arXiv](https://arxiv.org/abs/2211.09024)   

* Personalized Decision Making -- A Conceptual Introduction
  Scott Mueller, Judea Pearl.      
  [arXiv:2208.09558](https://arxiv.org/abs/2208.09558). (2022).       

* Backtracking Counterfactuals.  
  Julius von Kügelgen, Abdirisak Mohamed, Sander Beckers.  
  [arXiv](https://arxiv.org/abs/2211.00472) (2022)
  
* Causal Entropy Optimization.   
  Nicola Branchini, Virginia Aglietti, Neil Dhir, Theodoros Damoulas.    
  [arXiv](https://arxiv.org/abs/2208.10981).  (2022).   

* From Statistical to Causal Learning.   
  Bernhard Schölkopf, Julius von Kügelgen    
  [arXiv](https://arxiv.org/abs/2204.00607) (2022)
   
* Sensitivity Analysis of Individual Treatment Effects: A Robust Conformal Inference Approach.   
  Ying Jin, Zhimei Ren, Emmanuel J. Candès. (2021).     
  [arXiv](https://arxiv.org/abs/2111.12161). | [Rpackage](https://zhimeir.github.io/cfsensitivity/index.html)

* A Survey on Causal Inference.  
  Yao et. al.   
  [doi](https://dl.acm.org/doi/10.1145/3444944).   (2021).    

* Potential Outcome and Directed Acyclic Graph Approaches to Causality:    
  Relevance for Empirical Practice in Economics.    
  Guido W. Imbens.   
  Journal of Economic Literature (December 2020).   
  [journal](https://www.aeaweb.org/articles?id=10.1257/jel.20191597) | [arXiv](https://arxiv.org/abs/1907.07271) | [Pearl's response](http://causality.cs.ucla.edu/blog/index.php/category/imbens/)

* Synthetic Difference in Differences, 2019. 
  Dmitry Arkhangelsky, Susan Athey, David A. Hirshberg, Guido W. Imbens, and Stefan Wager. 
  [arxiv:1812.09970](https://arxiv.org/abs/1812.09970)

* Why Propensity Scores Should Not Be Used for Matching      
  King et. al.   
  Political Analysis, 27, 4, Pp. 435-454.  (2019)
  [url](https://tinyurl.com/y5b5yjxo)

* Detecting and quantifying causal associations in large nonlinear time series datasets.  
  Jakob Runge, Peer Nowack, Marlene Kretschmer, Seth Flaxman and Dino Sejdinovic. 
  Science Advances  27 Nov 2019 Vol. 5, no. 11, eaau4996.  
  [doi](http://dx.doi.org10.1126/sciadv.aau4996)
  
* The Seven Tools of Causal Inference, with Reflections on Machine Learning.  
  Judea Pearl.   
  Communications of the ACM, March 2019, Vol. 62 No. 3, Pages 54-60.  
  [url](https://cacm.acm.org/magazines/2019/3/234929-the-seven-tools-of-causal-inference-with-reflections-on-machine-learning/fulltext)    
  [pdf-reprint](https://ftp.cs.ucla.edu/pub/stat_ser/r481-reprint.pdf). 
  [interview](https://www.youtube.com/watch?v=CsMV5o3hotY).  

* A Meta-Transfer Objective for Learning to Disentangle Causal Mechanisms.    
  Yoshua Bengio, Tristan Deleu, Nasim Rahaman, Rosemary Ke, Sébastien Lachapelle, 
  Olexa Bilaniuk, Anirudh Goyal, Christopher Pal.  
  [arXiv:1901.10912](https://arxiv.org/abs/1901.10912)

* Theoretical Impediments to Machine Learning With Seven Sparks from the Causal Revolution.  
  Judea Pearl.  
  [arXiv:1801.04016](https://arxiv.org/abs/1801.04016)

* Automated versus do-it-yourself methods for causal inference:    
  Lessons learned from a data analysis competition.  
  Vincent Dorie†, Jennifer Hill, Uri Shalit, Marc Scott, and Dan Cervone.   
  [arXiv:1707.02641](https://arxiv.org/pdf/1707.02641.pdf)
  
* Double/Debiased Machine Learning for Treatment and Causal Parameters.   
  Victor Chernozhukov et. al.  (2017).  
  [arXiv](https://arxiv.org/abs/1608.00060). | [EC-journal](https://academic.oup.com/ectj/article/21/1/C1/5056401?login=true)      

* Quantum-Like Bayesian Networks for Modeling Decision Making.  
  Catarina Moreira and Andreas Wichert. 
  Front. Psychol., 26 January 2016. 
  [doi](https://doi.org/10.3389/fpsyg.2016.00011)

* Causal inference and the data-fusion problem    
  Elias Bareinboim and Judea Pearl    
  PNAS, 113 (27) 7345-7352 (2016)    
  [doi](https://doi.org/10.1073/pnas.1510507113)     

* The Sure-Thing Principle.  
  Judea Pearl (2016).  
  [pdf](https://ftp.cs.ucla.edu/pub/stat_ser/r466.pdf) 
  
* Brodersen KH, Gallusser F, Koehler J, Remy N, Scott SL.   
  Inferring causal impact using Bayesian structural time-series models.   
  Annals of Applied Statistics, (2015), Vol. 9, No. 1, 247-274.  
  [url](http://research.google.com/pubs/pub41854.html)
  
* Linear Models: A Useful “Microscope” for Causal Analysis.  
  Journal of Causal Inference 2013; 1(1): 155–170.  
  Judea Pearl.  
  [doi](https://doi.org/10.1515/jci-2013-0003) [pdf](http://ftp.cs.ucla.edu/pub/stat_ser/r409-corrected-reprint.pdf)

* Introduction to Judea Pearl's Do-Calculus.   
  Robert R. Tucci. (2013)
  [arXiv:1305.5506](https://arxiv.org/abs/1305.5506)

* The Do-Calculus Revisited.  
  Judea Pearl.   
  Keynote AI Uncertainy Conference (2012).  
  [pdf](https://ftp.cs.ucla.edu/pub/stat_ser/r402.pdf)
  
* Detecting causality in complex ecosystems.    
  George Sugihara, Robert May, Hao Ye, Chih-hao Hsieh, Ethan Deyle, Michael Fogarty, Stephan Munch.   
  Science Oct 26;338(6106):496-500 (2012).    
  [doi](https://doi.org/10.1126/science.1227079).    
  `convergent cross-mapping`

* Introduction to Causal Inference.    
  Peter Spirtes.    
  (2010)    
  [jmlr](http://www.jmlr.org/papers/v11/spirtes10a.html).   

*  Transfer entropy—a model-free measure of effective connectivity for the neurosciences.   
   Vicente et. al.   
   J Comput Neurosci (2011) 30:45–67.     
   [pdf](https://link.springer.com/content/pdf/10.1007/s10827-010-0262-3.pdf).   

* Causal inference in statistics: An overview.   
  Judea Pearl. (2009).  
  [doi](http://dx.doi.org/10.1214/09-SS057). 

* The Neyman— Rubin Model of Causal Inference and Estimation Via Matching Methods.        
  Jasjeet Sekhon.    
  The Oxford Handbook of Political Methodology.    
  [doi](10.1093/oxfordhb/9780199286546.003.0011) | [pdf-preprint](http://sekhon.berkeley.edu/papers/SekhonOxfordHandbook.pdf)

* Econometric Causality.   
  James J. Heckman.  
  International Statistical Review (2008), 76, 1, 1–27.    
  [doi](http://dx.doi.org/10.1111/j.1751-5823.2007.00024.x). 

* Causal Inference Using Potential Outcomes: Design, Modeling, Decisions.        
  Donald B. Rubin.      
  Journal of the American Statistical Association.          
  Vol. 100, No. 469 (Mar., 2005), pp. 322-331.          
  [jstor](https://www.jstor.org/stable/27590541).   
  [pdf-tandfonline](https://www.tandfonline.com/doi/pdf/10.1198/016214504000001880?casa_token=uQtd_czuZDEAAAAA:uh_ziMbrAJflEo1a5JbkhZauwazlpmdJKkbo0zRHRBlzBWx7CnS4GZAttMPyOVqow70mUycX0lmwgg)

* The Economic Costs of Conflict: A Case Study of the Basque Country  
  Alberto Abadie, Javier Gardeazabal   
  American Economic Review, Vol. 93, No.1, pp 113-132 (2003) |  
  [doi](https://dx.doi.org/10.1257/000282803321455188) | [baylor-pdf](https://business.baylor.edu/scott_cunningham/teaching/abadie-and-gardeazabal-2003.pdf)   
  
* Time Series Analysis, Cointegration, and applications.   
  Nobel Lecture of Clive Granger.  
  (2003)  
  [pdf](https://www.nobelprize.org/uploads/2018/06/granger-lecture.pdf)

* Causal Complexity and the Study of Politics.   
  Bear Braumoeller.   
  Political Analysis 198(11):209-233 (2003).   
  [doi](http://dx/doi.org/10.1093/pan/mpg012).   
  [researchgate-url](https://www.researchgate.net/publication/228774938_Causal_Complexity_and_the_Study_of_Politics).  

* Identification of Causal Effects Using Instrumental Variables    
  Joshua D. Angrist, Guido W. Imbens and Donald B. Rubin   
  Journal of the American Statistical Association (JASA)
  Vol. 91, No. 434 (Jun., 1996) [jstor](https://www.jstor.org/stable/2291629) | [pdf-McGill](https://www.math.mcgill.ca/dstephens/AngristIV1996-JASA-Combined.pdf)
  `potential outcomes`
  
* Causal diagrams for empirical research.    
  Judea Pearl (1995).      
  [jstor](https://www.jstor.org/stable/2337329) | [pdf-UCLA](http://bayes.cs.ucla.edu/R218-B.pdf).
  `Reasoning on Graphs: d-seperation, back/front-door`

* Identification and Estimation of Local Average Treatment Effects.   
  Joshua D. Angrist & Guido W. Imbens.    
  [nber](https://www.nber.org/papers/t0118) (1995).
  Econometrica, 6, 2,467-476.  (1994) [jstor](https://www.jstor.org/stable/2951620) | [pdf-Baylor](https://business.baylor.edu/scott_cunningham/teaching/imbens--angrist---late-1994.pdf)    
  
*  Paul W. Holland.  
   Statistics and Causal Inference.  
   Journal of the American Statistical Association.  
   Dec., 1986, Vol. 81, No. 396 (Dec., 1986), pp. 945-960 [jstor](https://www.jstor.org/stable/2289064). | [pdf-from-David-Bleie](https://www.cs.columbia.edu/~blei/fogm/2020F/readings/Holland1986.pdf)    

* Rubin, D. B. (1974)   
  Estimating causal effects of treatments in randomized and nonrandomized studies.    
  Journal of Educational Psychology, 66(5), 688-701.  
  [doi](http://dx.doi.org/10.1037/h0037350)

* Haavelmo, T. (1943).   
  The statistical implications of a system of simultaneous equations.  
  Econometrica, 11, 1–12.  
  [jstor](http://links.jstor.org/sici?sici=0012-9682%28194301%2911%3A1%3C1%3ATSIOAS%3E2.0.CO%3B2-N)
  
  Judea Pearls comment on Haavelmo.   
  Econometric Theory , Volume 31 , Issue 1: Haavelmo Memorial Issue: Part One , February 2015 , pp. 152 - 179
  [doi](https://doi.org/10.1017/S0266466614000231).    

* Wright, S. (1921)  
  Correlation and causation.  
  J. Agricultural Research. 20: 557–585.

* Wright, S. (1934).   
  The method of path coefficients.  
  Annals of Mathematical Statistics. 5 (3): 161–215.   
  [doi](http://www.doi.org/10.1214/aoms/1177732676)

## Causal Discovery

* Causation versus Prediction: Comparing Causal Discovery and  
  Inference with Artificial Neural Networks in Travel Mode Choice Modeling  
  Rishabh Singh Chauhan, Uttara Sutradhar, Anton Rozhkov, Sybil Derrible
  [arXiv](https://arxiv.org/abs/2307.15262) (2023)
  `Comparison of PC and Double ML on transportation preference`

* An Introduction to Causal Discovery   
  Martin Huber, A bonus chapter (2023)   
  [pdf-academic-page](https://www.unifr.ch/appecon/en/assets/public/uploads/introcausaldiscovery2.pdf)

* Causal Discovery and Prediction: Methods and Algorithms   
  Gilles Blondel (Thesis) (2023)  
  [arXiv](https://arxiv.org/abs/2309.09416)  
  
* On the Interventional Kullback-Leibler Divergence. 
  Jonas Wildberger, Siyuan Guo, Arnab Bhattacharyya, Bernhard Schölkopf.    
  [arXiv](https://arxiv.org/abs/2302.05380) (2023).    

* Causal Structure Learning: a Combinatorial Perspective.    
  Chandler Squires, Caroline Uhler.  (2022).   
  [arXiv](https://arxiv.org/abs/2206.01152).    

* Deep End-to-end Causal Inference.  
   Tomas Geffner, Javier Antoran, Adam Foster, Wenbo Gong,   
   Chao Ma, Emre Kiciman, Amit Sharma, Angus Lamb, Martin Kukla,   
   Nick Pawlowski, Miltiadis Allamanis, Cheng Zhang.      
   [arXiv](https://arxiv.org/abs/2202.02195) (2022).      
   [github-deci](https://github.com/microsoft/project-azua/tree/main/azua/models/deci)

* Learning to Induce Causal Structure.     
  Nan Rosemary Ke, Silvia Chiappa, Jane Wang, Jorg Bornschein, Theophane Weber,     
  Anirudh Goyal, Matthew Botvinic, Michael Mozer, Danilo Jimenez Rezende.    
  [arXiv](https://arxiv.org/abs/2204.04875) (2022).   

* Discovering Causal Structure with Reproducing-Kernel Hilbert Space ε-Machines.  
  Nicolas Brodu, James P. Crutchfield. 
  [arXiv](https://arxiv.org/abs/2011.14821) (2021).  

* Nobel Memorial Economics Prize 2021 on causal discovery, scientific summary.     
  Answering Causal Questions Using Observational Data.   (2021)   
  (David Card, Joshua Angrist, and Guido Imbens)     
  [pdf](https://www.nobelprize.org/uploads/2021/10/advanced-economicsciencesprize2021.pdf).   
  
 * Causal network reconstruction from time series: From theoretical assumptions to practical estimation.  
  J. Runge.  
  Chaos 28, 075310 (2018).   
  [DOI](https://doi.org/10.1063/1.5025050).  
  
* Learning Representations for Counterfactual Inference.  
  Fredrik D. Johansson, Uri Shalit, David Sontag.  
  ICML 2016, [arXiv](https://arxiv.org/abs/1605.03661).   
  
* Causal Discovery via Reproducing Kernel Hilbert Space Embeddings       
  Zhitang Chen, Kun Zhang, Laiwan Chan, Bernhard Schölkopf     
  Neural Computation 26, 1484–1517  (2014).     
  [doi](http://dx.doi.org/10.1162/NECO_a_00599)   
  
* Cosma Shalizi's notebook [causal discovery algorithms](http://bactra.org/notebooks/causal-discovery-algorithms.html).    

## Simpsons Paradox

* Learning to Discover Various Simpson's Paradoxes   
  Jingwei Wang, Jianshan He, Weidi Xu, Ruopeng Li, Wei Chu   
  KDD '23: Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery and Data Mining   
  August 2023, Pages 5092–5103 [doi](https://doi.org/10.1145/3580305.3599859) | [git-repository](https://github.com/ant-research/Learning-to-Discover-Various-Simpson-Paradoxes)

* A toolbox to demystify probabilistic and statistical paradoxes.   
  Kelter R, Schnurr A and Spies S (2023)   
  Front. Educ. 8:1212419. [doi](https://doi.org/10.3389/feduc.2023.1212419) | [author-pdf](https://dspace.ub.uni-siegen.de/bitstream/ubsi/2578/3/A_toolbox_to_demystify_probabilistic_and_statistical_paradoxes.pdf)

* Pearl, J. (2014). Comment: understanding Simpson’s paradox. Am. Stat. 68, 8–13. doi: 10.1080/00031305.2014.876829

* Simpson's Paradox: An Anatomy    
  Judea Pearl (1999). 
  [UCLA Technical-Report](http://bayes.cs.ucla.edu/R264.pdf)
  
* On Simpson's Paradox and the Sure-Thing Principle.   
  Colin R. Blyth.  
  Journal of the American Statistical Association.  
  Vol. 67, No. 338 (Jun., 1972), pp. 364-366.  [doi](https://doi.org/10.2307/2284382) 

*  The interpretation of interaction in contingency tables.       
   Simpson, E. H. (1951).    
   J. Royal Stat. Soc. 13, 238–241.  [doi](https://dx.doi.org/10.1111/J.2517-6161.1951.TB00088.X)   

## Machine Learning
Including games, reinforcement or deep learning.    

* Comprehensive Causal Machine Learning
  Michael Lechner, Jana Mareckova
  [arxiv](https://arxiv.org/abs/2405.10198)| (2024)

* Language Models as Causal Effect Generators    
  Lucius E.J. Bynum, Kyunghyun Cho    
  [arXiv](https://arxiv.org/abs/2411.08019) (2024)    

* Invariant Causal Knowledge Distillation in Neural Networks   
  Nikolaos Giakoumoglou, Tania Stathaki   
  [arXiv](https://arxiv.org/abs/2407.11802v2) (2024)   

* Peer-induced Fairness: A Causal Approach for Algorithmic Fairness Auditing
  Shiqi Fang, Zexun Chen, Jake Ansell
  [arXiv](https://arxiv.org/abs/2408.02558) (2024)

* Causally Abstracted Multi-armed Bandits   
  Fabio Massimo Zennaro et. al.     
  [arXiv](https://arxiv.org/abs/2404.17493) (2024)     

* Causal machine learning for predicting treatment outcomes       
  Stefan Feuerriegel et. al.      
  [url](https://www.nature.com/articles/s41591-024-02902-1) (2023)  

* Causal machine learning for single-cell genomics   
  Alejandro Tejada-Lapuerta, Paul Bertin, Stefan Bauer, Hananeh Aliee, Yoshua Bengio, Fabian J. Theis    
  [arXiv](https://arxiv.org/abs/2310.14935) (2023)   
  
* Estimating categorical counterfactuals via deep twin networks    
  Athanasios Vlontzos, Bernhard Kainz & Ciarán M. Gilligan-Lee    
  Nature Machine Intelligence volume 5, pages 159–168 (2023)
  [nature](https://www.nature.com/articles/s42256-023-00611-x) | [arXiv](https://arxiv.org/abs/2109.01904)

* Causal Reasoning and Large Language Models: Opening a New Frontier for Causality  
  Emre Kıcıman, Robert Ness, Amit Sharma, Chenhao Tan
  [arXiv](https://arxiv.org/abs/2305.00050) (2023)

* Causal Reinforcement Learning: A Survey   
  Zhihong Deng, Jing Jiang, Guodong Long, Chengqi Zhang
  [arXiv](https://arxiv.org/abs/2307.01452) (2023)

* Causal Component Analysis.   
  Wendong Liang et. al.  
  [arXiv](https://arxiv.org/abs/2305.17225) (2023).  

* Double Machine Learning and Automated Confounder Selection -- A Cautionary Tale.  
  Paul Hünermund et. al. (2023) 
  [arXiv](https://arxiv.org/abs/2108.11294) | [talk](https://faculti.net/double-machine-learning-and-automated-confounder-selection/) |
  [Journal of Causal Inference](https://doi.org/10.1515/jci-2022-0078)
  
* Causal Deep Learning.  
  Jeroen Berrevoets, Krzysztof Kacprzyk, Zhaozhi Qian, Mihaela van der Schaar.  (2023)
  [arXiv](https://arxiv.org/abs/2303.02186).   

* A Survey on Causal Reinforcement Learning
  Yan Zeng et. al. [arXiv](https://arxiv.org/abs/2302.05209) (2023)

* Reasoning about Causality in Games.    
  Lewis Hammond, James Fox, Tom Everitt, Ryan Carey, Alessandro Abate, Michael Wooldridge.  (2023).    
  [arXiv](https://arxiv.org/abs/2301.02324).    

* Evaluating Uses of Deep Learning Methods for Causal Inference.    
  Albert Whata; Charles Chimedza.   
  [ieee](https://ieeexplore.ieee.org/abstract/document/9667520). (2022)   

* Causal Machine Learning: A Survey and Open Problems   
  Jean Kaddour, Aengus Lynch, Qi Liu, Matt J. Kusner, Ricardo Silva 
  [arXiv](https://arxiv.org/abs/2206.15475) (2022)

* Causal Reinforcement Learning using Observational and Interventional Data.     
  Maxime Gasse, Damien Grasset, Guillaume Gaudron, Pierre-Yves Oudeyer.    
  [arXiv:2106.14421](https://arxiv.org/abs/2106.14421) (2021)

* Causal Reinforcement Learning, ICML 2020 [url](https://crl.causalai.net)

* Sample-Efficient Reinforcement Learning via Counterfactual-Based Data Augmentation.   
  Chaochao Lu, Biwei Huang, Ke Wang, José Miguel Hernández-Lobato, Kun Zhang, Bernhard Schölkopf.  (2020).      
  [arXiv:2012.09092](https://arxiv.org/abs/2012.09092)

* Machine Learning Methods That Economists Should Know About   
  Susan Athey and Guido W. Imbens
  [Annual Reviews](https://www.annualreviews.org/content/journals/10.1146/annurev-economics-080217-053433;jsessionid=ln_r7UHAEX_IEsVFDhG1ZgtVXrsPhWv5ReUKrihr.ip-10-241-10-70) (2019)
  
* Causality for Machine Learning.  
  Bernhard Schölkopf.  
  [arXiv:1911.10500](https://arxiv.org/abs/1911.10500)
  
* Causal Inference and Uplift Modelling: A Review of the Literature.   
  Pierre Gutierrez, Jean-Yves Gérardy ; Proceedings of The 3rd International    
  Conference on Predictive Applications and APIs, PMLR 67:1-13, 2017.   
  [url](http://proceedings.mlr.press/v67/gutierrez17a.html)

## Fairness 

* Survey on Causal-based Machine Learning Fairness Notions.    
  Karima Makhlouf, Sami Zhioua, Catuscia Palamidessi.    
  [arXiv](https://zhimeir.github.io/cfsensitivity/index.html) (2020). 
 
* Causal Modeling of Twitter Activity during COVID-19      
  Gencoglu, Oguzhan, and Mathias Gruber. (2020).      
  Computation 8, no. 4: 85. [doi](https://doi.org/10.3390/computation8040085).    
 
* Achieving Causal Fairness in Machine Learning.   
  Wu, Yongkai. University of Arkansas, ProQuest Dissertations Publishing, 2020. 27960037.   
  [url](https://search.proquest.com/openview/5b94283bd4da8edc1b14bff3db4c9e77/1?pq-origsite=gscholar&cbl=18750&diss=y)

* Causal Bayesian Networks (2019).    
  [blog-deepmind](https://deepmind.com/blog/article/Causal_Bayesian_Networks).   

* A Causal Bayesian Networks Viewpoint on Fairness.      
  Silvia Chiappa, William S. Isaac (2019).    
  [arXiv:1907.06430](https://arxiv.org/abs/1907.06430)    

* Zhang, J., & Bareinboim, E. (2018).       
  Fairness in Decision-Making — The Causal Explanation Formula.     
  Proceedings of the AAAI Conference on Artificial Intelligence, 32(1).   
  [doi](https://doi.org/10.1609/aaai.v32i1.11564).  

* Counterfactual Fairness.    
  Kusner et. al.   
  NeurIPs 2017 [pdf](https://proceedings.neurips.cc/paper/2017/file/a486cd07e4ac3d270571622f4f316ec5-Paper.pdf)

* Counterfactual Explanations without Opening the Black Box: Automated Decisions and the GDPR    
  Sandra Wachter, Brent Mittelstadt, Chris Russell          
  [arXiv](https://arxiv.org/abs/1711.00399) (2017).    

## Physics

*  H-Theorem do-conjecture  
   M. Suzen   
   [arXiv:2310.01458](https://arxiv.org/abs/2310.01458). | [code](https://github.com/msuzen/research/tree/main/h-do-conjecture)

* Causality, determinism, and physics.   
  Julio Geo-Banacloche.    
  American Journal of Physics 90, 809 (2022); [doi](https://doi.org/10.1119/5.0087017).  

* Arrow of Causality and Quantum Gravity.  
  John F. Donoghue and Gabriel Menezes.  
  Phys. Rev. Lett. 123, 171601    
  [url](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.123.171601)

* The causal set approach to quantum gravity.   
  Sumati Surya     
  Living Reviews in Relativity volume 22, Article number: 5 (2019).   
  [url](https://link.springer.com/article/10.1007/s41114-019-0023-1).  

* Algorithmic independence of initial condition and dynamical law in thermodynamics and causal inference.   
  Dominik Janzing et al 2016 New J. Phys. 18 093052.   
  [url-open-access](https://iopscience.iop.org/article/10.1088/1367-2630/18/9/093052/meta).   
  
* Quantum causality.   
  Brukner, Časlav.      
  Nature Physics, Volume 10, Issue 4, pp. 259-263 (2014).     
  [doi](https://ui.adsabs.harvard.edu/link_gateway/2014NatPh..10..259B/doi:10.1038/nphys2930) | [yale-pdf](https://inferenceproject.yale.edu/sites/default/files/brukner2014_q_causality.pdf)
  
* Causal Entropic Forces.    
  A. D. Wissner-Gross and C. E. Freer.   
  Phys. Rev. Lett. 110, 168702.  (2013).         
  [url](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.110.168702).  
  
* Resource Letter CD-1: Causality and determinism in physics.    
  R. Jones.     
  Am. J. Phys. 64, 208–215 (1996). [doi](https://doi.org/10.1119/1.18208).     
 
* Space-time as a causal set.  
  Luca Bombelli, Joohan Lee, David Meyer, and Rafael D. Sorkin.  
  Phys. Rev. Lett. 59, 521 (1987).  
  [url](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.59.521)

* The class of continuous timelike curves determines the topology of spacetime.   
  David B. Malament.   
  Journal of Mathematical Physics 18, 1399 (1977).   
  [doi](https://doi.org/10.1063/1.523436).  


## Thesis  

PhD thesis on causality.     

* Causality in Point Processes     
  McGovern, Ian      
  PhD Thesis, Los Angeles, [url](https://escholarship.org/content/qt5x56b2fk/qt5x56b2fk.pdf)  (2024)      

* Identifiable Causal Representation Learning    
  Unsupervised, Multi-View, and Multi-Environment    
  Julius von Kügelgen         
  PhD Thesis, Cambridge [doi](https://doi.org/10.17863/CAM.106852)    (2023)      

* Explainable Reinforcement Learning Through a Causal Lens.    
  Prashan Madumal.   
  PhD thesis, Melbourne [pdf](https://rest.neptune-prod.its.unimelb.edu.au/server/api/core/bitstreams/0730665b-be59-5e97-9eb8-33223bf6464c/content) | [aaai](https://ojs.aaai.org//index.php/AAAI/article/view/5631).  (2021).    

## Review   

* Causal Inference in the Social Sciences           
  Guido W. Imbens              
  [url](https://www.annualreviews.org/content/journals/10.1146/annurev-statistics-033121-114601) (2024)      

## Software.  

### Causal Discovery

  * Causal-learn: Causal Discovery in Python   
    Spirtes & CMU & Team  
    [arXiv](https://arxiv.org/abs/2307.16405) | [repo](https://github.com/py-why/causal-learn)  

  * Tigramite – Causal inference and causal discovery for time series datasets.    
    [github](https://github.com/jakobrunge/tigramite)

  * The Causal Discovery Toolbox (CDT)    
    A package for causal inference in graphs and in the pairwise settings.            
    [github](https://github.com/FenTechSolutions/CausalDiscoveryToolbox).   | [arXiv](https://arxiv.org/abs/1903.02278)

  * LinGAM Discovery of non-gaussian linear causal models [github](https://github.com/cdt15/lingam) | [software paper](https://jmlr.org/papers/v24/21-0321.html)  | [original paper](https://www.jmlr.org/papers/v7/shimizu06a.html)  

  * PyPhi: A toolbox for integrated information theory.   
  [pypi](https://pypi.org/project/pyphi/).  
  [arXiv1712.09644](https://arxiv.org/abs/1712.09644)

  * Causal-tune [github](https://github.com/py-why/causaltune).

  * Huawei's gCastle is a causal structure learning toolchain [github-repo](https://github.com/huawei-noah/trustworthyAI/tree/master/gcastle)

### Microsoft Research : PyWhy
  
  * PyWhy organisation [github](https://github.com/py-why/).      
    [DoWhy evolves to independent PyWhy model to help causal inference grow](https://www.microsoft.com/en-us/research/blog/dowhy-evolves-to-independent-pywhy-model-to-help-causal-inference-grow/?OCID=msr_blog_PyWhy_TW) | [aws-blog](https://www.amazon.science/blog/aws-contributes-novel-causal-machine-learning-algorithms-to-dowhy)     

  * DoWhy is a Python library for causal inference.    
    [github](https://github.com/microsoft/dowhy) | [Paper-arXiv](https://arxiv.org/abs/2011.04216). 
    
  * EconML.            
    EconML is a Python package for estimating heterogeneous treatment    
    effects from observational data via machine learning.  
    [github](https://github.com/microsoft/EconML)  
  
  * Azua/DECI.      
    [github](https://github.com/microsoft/project-azua)      
    [github-DECI-module](https://github.com/microsoft/project-azua/tree/main/azua/models/deci) `Deep End-to-end Causal Inference`   
    
  * ShowWhy.     
    UI on top of DoWhy, EconML [github](https://github.com/microsoft/showwhy)
    
  * Causica : DECI: End to End Causal Inference     
    [github](https://github.com/microsoft/causica)  

  * Causal-learn: Causal Discovery in Python   
    Spirtes & CMU & Team  
    [arXiv](https://arxiv.org/abs/2307.16405) | [repo](https://github.com/py-why/causal-learn)    

  * llm experimental [pywhy-llm](https://github.com/py-why/pywhy-llm)   

### Causal Impact and Observational

  * DoubleML in Python/R package [github](https://github.com/DoubleML/doubleml-for-py). | [JSS-article](https://www.jstatsoft.org/article/view/v108i03)   

  * CausalML: A Python Package for Uplift Modeling and Causal Inference with ML.  
    [github](https://github.com/uber/causalml) | [software X paper](https://doi.org/10.1016/j.softx.2022.101294)

  * An R package for causal inference using Bayesian structural time-series models   
  [CausalImpact](https://google.github.io/CausalImpact/CausalImpact.html). 
  [CRAN](https://cran.r-project.org/package=CausalImpact).    
  [github-python-port](https://github.com/jamalsenouci/causalimpact).   
  [paper](https://research.google/pubs/pub41854/).    
  [causalimpact-tf](https://github.com/WillianFuks/tfcausalimpact) Re-write with tensorflow probability

  * upliftml : Uplift modelling, Booking.com
  [github](https://github.com/bookingcom/upliftml)

  * [Identifying Causal Effects with the R Package causaleffect](https://cran.r-project.org/web/packages/causaleffect/vignettes/causaleffect.pdf)

  * IBM's causalib Python package [github](https://github.com/IBM/causallib)

  * (synthdid: Synthetic Difference in Differences Estimation)[https://synth-inference.github.io/synthdid/index.html].  
  R-package

### Causal Graphs and Bayesian Networks

  * DAGitty — draw and analyze causal diagrams [url](https://www.dagitty.net)  

  * CausalQueries: Make, Update, and Query Binary Causal Models   
    [CRAN](https://cran.rstudio.com/web/packages/CausalQueries/index.html) | [book: Causal Models: Guide to CausalQueries](https://macartan.github.io/causalmodels/)   

  * pgmpy is a pure python implementation for Bayesian Networks [www](https://pgmpy.org) | [Paper-ArXiv](https://arxiv.org/abs/2304.08639) | 

  * causaleffect: Deriving Expressions of Joint Interventional Distributions and Transport Formulas in Causal Models.   
    [CRAN](https://cran.r-project.org/web/packages/causaleffect/index.html).  
    * GRAPHL [repo](https://github.com/max-little/GRAPL) | [joss](https://joss.theoj.org/papers/10.21105/joss.04534.pdf)

  * dagR: Directed Acyclic Graph with R.  
  [CRAN](https://cran.r-project.org/web/packages/dagR/index.html)[doi](http://dx.doi.org/10.1097/EDE.0b013e3181e09112)
  
  * PyCID: Causal Influence Diagrams library [github](https://github.com/causalincentives/pycid)
  Relevant to PyCID : A python library for 2 player games [nashpy](https://github.com/drvinceknight/nashpy)  

  * [CausalPy](https://github.com/pymc-labs/CausalPy) : Bayesian -regression discontinuity |
  [pymc-lab](https://www.pymc-labs.io)
  
  * [CausalNex](https://github.com/quantumblacklabs/causalnex) A toolkit for causal reasoning with Bayesian Networks 
  from Quantumblack.

  * Tetrad Project: Graphical Causal Models  
  [url](http://www.phil.cmu.edu/tetrad/)

### Views

  * R Universe: [CRAN Task View Causal Inference](https://cran.r-project.org/web/views/CausalInference.html)

## Datasets

* R causaldata         
  Nick Huntington-Klein, Malcolm Barrett    
  Example dataset from some of the Causality textbooks       
  [github](https://github.com/NickCH-K/causaldata) |  [cran](https://cran.r-project.org/web/packages/causaldata/index.html)    

* Distinguishing Cause from Effect Using Observational Data: Methods and Benchmarks.     
  Joris M. Mooij, Jonas Peters, Dominik Janzing, Jakob Zscheischler, Bernhard Schölkopf;   
  17(32):1−102, (2016).  [jmlr-paper](https://jmlr.org/papers/v17/14-518.html).       
  Database with cause-effect pairs [url](https://webdav.tuebingen.mpg.de/cause-effect/).     
 
## MOOCs

* Mixtape sessions [url](https://www.mixtapesessions.io)  
  Free Course Material  

* A Crash Course in Causality: Inferring Causal Effects from Observational Data.    
  [url](https://www.coursera.org/learn/crash-course-in-causality)

* Measuring Causal Effects in the Social Sciences.   
  [url](https://www.coursera.org/learn/causal-effects)
  
* Probabilistic Graphical Models Specialization.  
  Daphne Koller.     
  [url](https://www.coursera.org/specializations/probabilistic-graphical-models) 

## Blog Posts

* Resolving disputes between J. Pearl and D. Rubin on causal inference.        
  Gelman (2009) [url](https://statmodeling.stat.columbia.edu/2009/07/05/disputes_about/).   
  Follow ups [1](https://statmodeling.stat.columbia.edu/2009/07/07/more_on_pearls/)
  [2](https://statmodeling.stat.columbia.edu/2009/07/09/more_on_pearlru/)
  [3](https://statmodeling.stat.columbia.edu/2009/07/07/philip_dawids_t/)
  
  * 05/2022 Statisticians vs. Causal Inference  [url](https://statmodeling.stat.columbia.edu/2022/05/14/causal-is-what-we-say-when-we-dont-know-what-were-doing/#comment-2053584) | Pearl's response [url](http://causality.cs.ucla.edu/blog/index.php/2022/05/17/what-statisticians-mean-by-causal-inference-is-gelmans-blog-representative/)      
  
* Judea Pearl on Potential Outcomes.  
  [url](http://causality.cs.ucla.edu/blog/index.php/2012/12/03/judea-pearl-on-potential-outcomes/)
  
* Judea Pearl, model vs. model-free :   
  "...no “causal interpretation” is needed for parameters that are intrinsically causal..."    
  [url](http://causality.cs.ucla.edu/blog/index.php/2017/02/22/winter-2017-greeting-from-ucla-causality-blog/).

* Eight basic rules for causal inference    
  By Peder M. Isager (2024)   
  Tutorial [url](https://pedermisager.org/blog/seven_basic_rules_for_causal_inference/)   

## Quotes

Including interviews.    

* Causal Inference: History, Perspectives, Adventures, and Unification (An Interview with Judea Pearl).  
  Observational Studies, 8, 2, 2022, p1-14.     
  [url](https://muse.jhu.edu/article/867087) | [pdf](https://muse.jhu.edu/pub/56/article/867087/pdf).       

* Interview with Don Rubin.    
  Observational Studies (2022).      
  [url](https://muse.jhu.edu/article/867089).      

* A Conversation with A. Philip Dawid   (2023)
  [arXiv](https://arxiv.org/abs/2312.00632)   


`Prediction and Causation`

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

`Rubin vs. Pearl`

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

`On the Pearl's Philosopy`

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

## Video Lectures 
including discussions

* 2022 Causal Data Science.      
  Elias Bareinboim (@ 1st Workshop on Interactive Causal Learning) [youtube](https://www.youtube.com/watch?v=6lWB_JmWY8g).    
* 2022 The Arrow of Time in Causal Networks
  Sean Carroll, Simons Intitute Talk [youtube](https://www.youtube.com/watch?v=6slug9rjaIQ)
* Judea Pearl: Causal Reasoning, Counterfactuals, and the Path to AGI | Lex Fridman Podcast #56.    
  Dec 11, 2019 [yt](https://www.youtube.com/watch?v=pEBI0vF45ic).    
* 2016 The Mathematics of Causal Inference: with Reflections on Machine Learning.    
  Judea Pearl, Microsoft Research. [youtube](https://www.youtube.com/watch?v=bcRl7sXR1hE).     
* 2015 Toward Causal Machine Learning.  
  Bernhard Schölkopf, [youtube](https://www.youtube.com/watch?v=ooeRlw3U2zU)
* 2012 Causal Inference Conference Featuring Judea Pearl [youtube](https://www.youtube.com/watch?v=j4JOR-PQuqQ&t=185s).         
  Judea Pearl's "The Mathematics of Causal Inference: Use it or Lose It"    
  
## Contemporary Academics

* [Judea Pearl](http://bayes.cs.ucla.edu/jp_home.html).  
* [Clark Glymour](https://www.cmu.edu/dietrich/philosophy/people/emeritus/glymour.html).
* [Peter Spirtes](https://www.cmu.edu/dietrich/philosophy/people/faculty/spirtes.html)
* [Richard Scheines](https://www.cmu.edu/dietrich/philosophy/people/faculty/scheines.html)
* [Elias Bareinboim](https://causalai.net).    
* [Donald B. Rubin](https://statistics.fas.harvard.edu/people/donald-b-rubin). 
* [Joshua Angrist](https://economics.mit.edu/faculty/angrist).  
* [Guido W. Imbens](https://www.gsb.stanford.edu/faculty-research/faculty/guido-w-imbens).  
* [Andrew Gelman](http://www.stat.columbia.edu/~gelman/).  
* [David Card](https://davidcard.berkeley.edu).  
* [Bernhard Schölkopf](https://is.mpg.de/~bs).
* [Joris M. Mooij](https://staff.fnwi.uva.nl/j.m.mooij/).
* [Dominik Janzing](https://janzing.github.io). 
* [Uri Shalit](https://dds.technion.ac.il/academicstaff/uri-shalit/).  
  
# Communities Conferences

* Causal RL [RLC Workshop 2025](https://sites.google.com/uci.edu/crlw2025/)
* [Causal Science](https://www.causalscience.org)
* Are Large Language Models Simply Causal Parrots?       
  Annual AAAI Conference on Artificial Intelligence 2024 [url](https://llmcp.cause-lab.net/schedule-llmcp)    
* Counterfactual reasoning: From minds to machines to practical applications.    
  ICML Workshop [url](https://sites.google.com/view/counterfactuals-icml/home) (2023)     
* Neurips 2023: Causal Representation Learning (CRL) [url](https://neurips.cc/virtual/2023/workshop/66497) 

