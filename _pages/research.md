---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---
## Multi-agent Multi-arm Bandits with Linear Rewards

**Abstract:**  
 Sequential learning in a multi-agent resource constrained matching market has received significant
interest in the past few years. We study decentralized learning in two-sided matching markets where
the demand side (aka players or agents) competes for a ‘large’ supply side (aka arms) with potentially
time-varying preferences, to obtain a stable match. Despite a long line of work in the recent past,
existing learning algorithms such as Explore-Then-Commit or Upper-Confidence-Bound remain
inefficient for this problem. In particular, the per-agent regret achieved by these algorithms scales
linearly with the number of arms, $K$. Motivated by the linear contextual bandit framework, we
assume that for each agent an arm-mean can be represented by a linear function of a known feature
vector and an unknown (agent-specific) parameter. Moreover, our setup captures the essence of a
dynamic (non-stationary) matching market where the preferences over arms change over time. Our
proposed algorithms achieve instance-dependent logarithmic regret, scaling independently of the
number of arms, $K$.

**TL;DR:**  
We solved a multi-agent multi-armed bandit problem with *time-varying* mean rewards modeled as linear functions. Our decentralized algorithm achieves instance-dependent logarithmic regret matching lower bound orderwise, with regret scaling independent of the number of arms.

Our work, **[Competing Bandits in Decentralized Large Contextual Matching Markets](https://arxiv.org/abs/2411.11794)**, is available on [arXiv](https://arxiv.org/abs/2411.11794).
 