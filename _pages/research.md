---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---

## Byzantine-Resilient Gradient Coding  
Undergraduate thesis with [Prof. Nikhil Karamchandani](https://sites.google.com/site/nikhilkaram/) and [Prof. Vinod Prabhakaran](https://www.tifr.res.in/~vinodmp/).  

Gradient coding is a coding-theoretic framework for distributing a large computation, say a gradient computation involved in gradient descent, to multiple workers (some of which may be faulty) and successfully recovering the final computation based on the results obtained by each worker. We study gradient coding in an adversarial scenario, i.e., some workers may be malicious. Our work builds upon the setting introduced in [this paper](https://doi.org/10.1109/ISIT54713.2023.10206794).  

I am currently working on developing low-replication gradient coding schemes while analyzing the communication and computation requirements of these schemes. So far, we have proposed a scheme and associated protocol capable of handling adversarial workers under full communication with an improvement in computation performance from previous results. I am also exploring the trade-off involved in computation requirements as we begin to introduce communication restrictions.  


## Information-Theoretic Persuasion  
Research project with [Prof. Michael Gastpar](https://people.epfl.ch/michael.gastpar/?lang=en).  

We are studying a project that models persuasion using information theory. Consider an agent that attempts to persuade a worker into taking an action favorable to the former's objective. The agent achieves this "persuasion" by revealing partial information about the worker's objective.  

We are currently working on quantifying this persuasion using the information contained in associated quantities and making remarks on the agent's optimal choice of selective information revelation. 

Our paper titled *"The Persuasion Bottleneck"* was presented at the International Symposium on Information Theory (ISIT) 2024. 



## Correlated Multi-Secret Sharing  
Research project with [Prof. Vinod Prabhakaran](https://www.tifr.res.in/~vinodmp/).  

Multi-Secret Sharing is a problem in information-theoretic cryptography, that is similar in setting to the [multi-party computation](https://en.wikipedia.org/wiki/Secure_multi-party_computation) problem. It involves distributing a set of *shares*, such that each party learns their *secret* using the shares accessible to them, without learning any extra information about the secrets of the other parties.  

I worked on the analysis of 3-party multi-secret sharing schemes under specific scenarios of the problem. I looked for optimal schemes and tested the optimality by bounding the randomness complexity required to facilitate secret sharing. We extended these information-theoretic bounds to all possible combinations of binary secrets and presented combinatorial bounds in cases where the lower bound was loose.  

Our paper titled *"[Randomness Requirements for Three-Secret Sharing](https://doi.org/10.1109/ISIT54713.2023.10206455)"* was presented at the International Symposium on Information Theory (ISIT) 2023. 

![Multi-Secret Sharing Problem](/images/SecretSharing.jpg)  
> *A general multi-secret sharing setting*
