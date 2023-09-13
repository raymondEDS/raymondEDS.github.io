---
title: "Causal Matching with Text Embeddings: A Case Study in Estimating the Causal Effects of Peer Review Policies"
collection: publications
permalink: /publication/causal_matching
excerpt: 'To address this textual confounding, we extend variable ratio nearest neighbor matching to incorporate text embeddings.'
date: 2023-07-09
venue: 'Findings of the Association for Computational Linguistics: ACL 2023'
paperurl: 'https://aclanthology.org/2023.findings-acl.83/

---
A promising approach to estimate the causal effects of peer review policies is to analyze data from publication venues that shift policies from single-blind to double-blind from one year to the next. However, in these settings the content of the manuscript is a confounding variable—each year has a different distribution of scientific content which may naturally affect the distribution of reviewer scores. To address this textual confounding, we extend variable ratio nearest neighbor matching to incorporate text embeddings. We compare this matching method to a widely-used causal method of stratified propensity score matching and a baseline of randomly selected matches. For our case study of the ICLR conference shifting from single- to double-blind review from 2017 to 2018, we find human judges prefer manuscript matches from our method in 70% of cases. While the unadjusted estimate of the average causal effect of reviewers’ scores is -0.25, our method shifts the estimate to -0.17, a slightly smaller difference between the outcomes of single- and double-blind policies. We hope this case study enables exploration of additional text-based causal estimation methods and domains in the future.

[Download paper here](https://aclanthology.org/2023.findings-acl.83.pdf)
[Paper Github Repo](https://github.com/raymondEDS/VRM-E)
