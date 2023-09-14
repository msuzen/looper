# LN 1: weighted Directed Acyclic Graph (wDAG)

Definition (wDAG): A weighted Directed Acyclic Graph (wDAG)  $\mathscr{G_{c}}$  is defined as set of ordered triplets of weights and connected random variables, such that, $k$th  triplet $(w_{k}, x_{i}, x_{j})$ where by $w_{k} \in \mathbb{R}$ is the weight, an effect size, between two variates that $x_{i}$ effects $x_{j}$. There are constraints : 

(i) No cyclic effects can be defined, necessarily $x_{i}$ can not be equal to $ x_{j}$.

(ii) If there is a definition,  $(w_{k}, x_{i}, x_{j})$ the reverse can't be defined, i.e.,  so that $(w_{k}, x_{j}, x_{i})$ does not exist.    

(iii) No two causal effects sizes can't be exactly equal, $w_{k}$ can not be equal to $w_{l}$, from the same causal variable,  meaning no simultaneous events caused by the same random variable. This prevents ambiguity of ordering and random tie-breaks are unnatural.

## Further reading and notes

* Pearl, Glymour and Jewell. 
  Causal Inference in Statistics: A Primer (2016).
  [amzn](https://www.amzn.com/dp/1119186846).  
  [Ch4-pdf](http://web.cs.ucla.edu/~kaoru/primer-ch4.pdf).
  [tweet-solution-manual](https://twitter.com/yudapearl/status/1484023795811696642).

* Constraint (iii) may not be applied, then ties should be break randomly, in the case of ordered events.
