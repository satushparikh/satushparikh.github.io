---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---

## Multi-Secret Sharing  
Research project with [Prof. Vinod Prabhakaran](https://www.tifr.res.in/~vinodmp/).  

Multi-Secret Sharing is a problem in information-theoretic cryptography, that is similar in setting to the [multi-party computation](https://en.wikipedia.org/wiki/Secure_multi-party_computation) problem. It involves distributing a set of *shares*, such that each party learns their *secret* using the shares accessible to them, without learning any extra information about the secrets of the other parties.  

I worked on the analysis of 3-party multi-secret sharing schemes under specific scenarios of the problem. I looked for optimal schemes and tested the optimality by bounding the randomness complexity required to facilitate secret sharing. We extended these information-theoretic bounds to all possible combinations of binary secrets and presented combinatorial bounds in cases where the lower bound was loose.  

Our paper titled *"[Randomness Requirements for Three-Secret Sharing](https://doi.org/10.1109/ISIT54713.2023.10206455)"* was presented at [ISIT 2023](https://isit2023.org/). 

![Multi-Secret Sharing Problem](/images/SecretSharing.jpg)  
> *A general multi-secret sharing setting*
