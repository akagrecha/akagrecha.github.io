---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}
1. **Constrained regret minimization for multi-criterion stochastic bandits** [[Paper]](https://arxiv.org/abs/2006.09649)
(Mar'19 to June'19) <br>
*Advisors: Prof. Jayakrishnan Nair, EE, IITB & Prof. Krishna Jagannathan, EE, IITM* <br>
*Introduction*: We formulate a new approach to consider multiple criteria in a stochastic bandit framework. The aim is to maximize the pulls of an arm which optimizes a certain criterion while satisfying constraints on the other criteria. In particular, we look at the problem of risk-constrained loss minimization but the analysis can be easily extended to more general settings. 
 <br>
- Formulated the problem of CVaR-constrained expected loss minimization and defined the notion of a consistent algorithm for the proposed setting. 
- Proposed a consistent algorithm, RC-LCB, and proved that the expected number of pulls of a non-optimal arm is bounded by a term logarithmic in the horizon.  
- Proved an inherent tension between regret minimization and feasibility identification, i.e., identifying if any
arm satisfies the constraint on CVaR or not.  

2. **Distribution oblivious, risk-aware algorithms for multi-armed bandits** [[Paper]](https://papers.nips.cc/paper/9305-distribution-oblivious-risk-aware-algorithms-for-multi-armed-bandits-with-unbounded-rewards) (Jan'19 to Dec'19) <br>
*Advisors: Prof. Jayakrishnan Nair, EE, IITB & Prof. Krishna Jagannathan, EE, IITM* <br>
*Introduction*: We consider a fixed budget best-arm identification stochastic multi-armed bandit problem where the objective is to find the arm which minimizes a linear combination of the expected loss and a risk-sensitive metric Conditional Value at Risk (CVaR). The loss distributions could be unbounded or even heavy tailed. The algorithms should be distribution oblivious, i.e., unaware of any information about the distributions. <br>
- Proposed novel estimators for the CVaR of unbounded random variables (potentially heavy tailed) and proved concentration inequalities for the proposed estimators.
-  Provided a class of distribution oblivious algorithms with provable upper bounds on the probability of misindentification of the arm optimizing the linear mean-CVaR objective.
- Proved a lower bound on the probability of misidentification for any given linear mean-CVaR objective.

3. **Modelling and analysis of deferral based queues** [[Paper]](https://arxiv.org/abs/1910.12894) (July'18 to Dec'18) <br>
*Advisor: Prof. Jayakrishnan Nair, EE, IITB* <br>
*Introduction*: We consider the performance benefits arising from the possibility of deferring customers who cannot be served upon arrival. Specifically, we consider an Erlang B type loss system where the system operator can, subject to certain constraints, ask a customer arriving when all servers are busy, to come back at a specified time in the future. <br>
- We propose a simple state-dependent policy for determining the rearrival times of deferred customers and characterize its long run fraction of customers dropped.
- We also analyze a relaxation of the problem where the deferral times are bounded in expectation. 
- Via extensive numerical evaluations, we demonstrate the superiority of the proposed state-dependent policy over naive state-independent deferral policies.

4. **Semidefinite programming (SDP) based decoder for binary linear codes** [[Report]]({{ site.url }}/files/SDP_based_decoder_for_binary_linear_codes.pdf) (May'18 to July'18) <br>
*Advisor: Prof. James Saunderson, ECSE, Monash University* <br>
*Introduction*: Maximum likelihood decoding for several classes of codes is a provably hard problem. Practical decoding algorithms usually work well, but lack rigorous guarantees on performance. Formulating decoding as a convex optimization problem, we aim to provide efficient algorithms and provable guarantees on performance. <br>
- Formulated a SDP relaxation of maximum likelihood decoding of binary linear codes and found the explicit optimality conditions for the SDP based decoder.
- Proved that the SDP based decoder is at least as good as linear programming (LP) based decoder, i.e., whenever LP based decoder succeeds, so does the SDP based decoder.
- Simulations show that the SDP based decoder performs marginally better than the LP based decoder.

5. **A Model of Translation in Plasmodium falciparum** [[Report]]({{ site.url }}/files/Model_of_Translation_in_Plasmodium_Falciparum.pdf) (Aug'17 to Dec'17) <br>
*Advisor: Prof. Swati Patankar, BSBE, IITB* <br>
*Introduction*: *P. falciparum* is a malaria causing parasite & its genome is highly AT-rich, with AT content as high as 90% in the intergenic regions. Hence, a high number of upstream start codons & upstream open reading frames are found on the mRNAs, making the translation process of coding regions difficult to understand. <br>
- Reviewed literature on translation in P. falciparum & identified important features governing the mechanism.
- Developed a Markovian model to predict the translational efficiency based on the identified features and the data from in vitro experiments conducted in the lab.
