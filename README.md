# Distributed Constraint Optimization Problems and Applications: A Survey

This repository is associated with the paper 
- Ferdinando Fioretto, Enrico Pontelli, William Yeoh. "_Distributed Constraint Optimization Problems and Applications: A Survey_" J. Artif. Intell. Res. 61: 623-698 (2018) 

The above surveys the state-of-the-art on Distributed Multiagent optimization. 

The authors will release regular updates of the paper on its associated [ArXiv release](https://arxiv.org/abs/1602.06347). The updates will cover new distributed algorithms, model, and applications proposed by researchers in the community. 

All changes will be logged and can be seen in the [Log section](#log).

## Submit your work

A list of algorithms currently described in the survey is available in the [List of Algorithms section](#algorighms). 

If your work is not currently covered and you would like the authors to include it 
in the survey, you can send a request using the following link: 

[Submit your request](https://forms.gle/neSjptZocJT3VVzf9)

Therein, you will be asked to report:
- Why is the algorithm/model relevant to the survey.
- A summary of the algorithm, model, or application (no more than 2000 characters).
- For algorithmic work: 
  + Where does the new algorithm fall in the algorithm taxonomy described in Figure 5 of the survey paper
  + A summary of the results obtained by the new algorithm (benchmarks adopted, 
  algorithms compared, experimental results)
- For new applications: 
  + In which category does the new application falls with respect to the categorization 
  reported in Table 5 of the survey paper.

Failure to provide the required information may result in rejecting the proposal. 

<a name="algorithms">
  
## List of Current Algorithms

### Classical DCOP Algorithms 
#### Complete Algorithms 
- Synchronous Branch-and-Bound (SyncBB) - _Hirayama & Yokoo, 1997_
- Asynchronous Forward Bounding (AFB) - _Gershman et al., 2009_
- Asynchronous Distributed OPTimization (ADOPT) - _Modi et al., 2005_
- Concurrent Forward Bounding (ConcFB) - _Netzer, Grubshtein, & Meisels, 2012_
- Distributed Pseudo-tree Optimization Procedure (DPOP) - _Petcu & Faltings, 2005b_
- Optimal Asynchronous Partial Overlay (OptAPO) - _Mailler & Lesser, 2004_

#### Incomplete Algorithms
- Max-Sum - _Farinelli et al., 2008_
- Region Optimal - _Pearce & Tambe, 2007_
- Maximum Gain Message (MGM) - _Maheswaran, Pearce, & Tambe, 2004a_
- Distributed Stochastic Algorithm (DSA) - _Zhang, Wang, Xing, & Wittenberg, 2005_
- Distributed Upper Confidence Tree (DUCT) - _Ottens, Dimitrakakis, & Faltings, 2017_
- Distributed-Gibbs (D-Gibbs) - _Nguyen, Yeoh, & Lau, 2013_

### Asymmetric DCOP Algorithms
#### Complete Algorithms 
- Synchronous Asymmetric Branch and Bound 2-phase (SyncABB-2ph) - _Grinshpoun et al., 2013_
- Synchronous Asymmetric Branch and Bound 1-phase SyncABB-1ph - _Grinshpoun et al., 2013; Levit et al., 2013_
- Asymmetric Two-Way Bounding (ATWB) - _Grinshpoun et al., 2013_

#### Incomplete Algorithms
- Asymmetric Coordinated Local Search (ACLS) - _Grinshpoun et al., 2013_
- Minimal Constraint Sharing MGM (MCS-MGM) - _Grinshpoun et al., 2013_

### Multi-objective DCOP Algorithms
#### Complete Algorithms 
- Multi-Objective Synchronous Branch and Bound (MO-SBB) - _Medi, Okimoto, & Inoue, 2014_
- Pseudo-tree Based Algorithm - Matsui et al. 2012)


#### Incomplete Algorithms
- Bounded Multi-Objective Max-Sum (B-MOMS) - _Delle Fave et al., 2011_
- Dynamic Programming based on Aggregate Objective Functions (DP-AOF)  - _Okimoto, Clement, & Inoue, 2013_
- Multi-Objective Lp-norm based
- Distributed Pseudo-tree Optimization Procedure (MO-DPOPLp) - _Okimoto et al., 2014_
- Distributed Iterated Pareto Local Search (DIPLS) - _Wack et al., 2014_


### Dynamic DCOP Algorithms
#### Complete Algorithms 
- Self-stabilizing DPOP (S-DPOP) - _Petcu & Faltings, 2005c_
- Incremental Anyspace ADOPT (I-ADOPT) - _Yeoh, et al., 2011_ 
- Incremental Any-space BnB-ADOPT (I-BnB-ADOPT) - _Yeoh, et al., 2011_ 


#### Incomplete Algorithms
- Support Based Distributed Optimization (SBDO) - _Billiau, Chang, & Ghose, 2012a_
- Fast Max-Sum (FMS) - _Ramchurn, et al., 2010_

#### Dynamic DCOP Variants
- RS-DPOP _Petcu & Faltings, 2007b_
- Distributed Q-learning and R-learning _Nguyen, et al., 2014_

### Probabilistic DCOP Algorithms

#### Complete Algorithms 
- $\mathbb{E}$[DPOP] - _(Leaute' & Faltings, 2011)_
- Stochastic Dominance DPOP (SD-DPOP) - _Nguyen et al., 2012_


#### Incomplete Algorithms
- Distributed Neighbor Exchange Algorithm (DNEA) - _Atlas & Decker, 2010_
- Uncertain Generalized Distributive Law (U-GDL) - _Stranders et al., 2011_


#### Probabilistic DCOP Variants
- The Balanced Exploration Rebid (BE-Rebid) - _Taylor et al., 2010_
- Heist - _Stranders et al., 2012_
- Iterative Constraint Generation Max-Sum (ICGMax-Sum) _Wu & Jennings, 2014_


<a name="resources">

## Resources

### DCOP Solvers

### Datasets

### Tutorials



<a name="log">
  
## Log
- [Current version]()
