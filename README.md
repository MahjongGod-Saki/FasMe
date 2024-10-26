# FasMe: Fast and Sample-efficient Meta Estimator for Precision Matrix Learning in Small Sample Settings

This work has been accepted by NeurIPs 2024.

Abstract: Precision matrix estimation is a ubiquitous task featuring numerous applications such as rare disease diagnosis and neural connectivity exploration. However, this task becomes challenging in small sample settings, where the number of samples is significantly less than the number of dimensions, leading to unreliable estimates. Previous approaches either fail to perform well in small sample settings or suffer from inefficient estimation processes, even when incorporating meta-learning techniques.
To this end, we propose a novel approach FasMe for Fast and Sample-efficient Meta Precision Matrix Learning, which first extracts meta-knowledge through a multi-task learning diagram. Then, meta-knowledge constraints are applied using a maximum determinant matrix completion algorithm for the novel task. As a result, we reduce the sample size requirements to $O(\log p/K)$ per meta-training task and $O(\log\vert \mathcal{G}\vert)$ for the meta-testing task. Moreover, the hereby proposed model only needs $O(p \log\epsilon^{-1})$ time and $O(p)$ memory for converging to an $\epsilon$-accurate solution. On multiple synthetic and biomedical datasets, FasMe is at least ten times faster than the four baselines while promoting prediction accuracy in small sample settings.


P.S. As we are working on improving readability, the code will be released step by step.
