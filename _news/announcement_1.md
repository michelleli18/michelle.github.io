layout: post
title: Presented our work <b>Predictive Uncertainty with Uncertainty-awareness and Lower Dimensional Representations</b> at Mellon Mays Undergraduate Fellowship Western Regional Conference.
date: 2023-11-3 15:59:00-0400
inline: false
related_posts: false
---

Keywords: Gaussian Processes, Uncertainty Quantification, Stochastic Variational Deep Kernel Learning

Although deep learning has improved medical image analysis via image segmentation, it can only provide point estimates. This lacks the reliability needed to make important decisions in the medical field, reliability that can be soothed with uncertainty quantification. In the following, we aim to use Gaussian Processes (GPs) to address this by providing predictive distributions, allowing physicians to interpret results with uncertainty estimates. Recently, Wu et al. [1] proposed a principled method using Deep Kernel Learning and a sparse GP layer to produce accurate uncertainty estimates in medical image analysis. DKL provided a lower dimensional representation that would help the GP layers.

<ul>
    <li>Distinguish the importance of having a lower dimensional input to GPs by comparing the results of SVDKL with GP vs DKL with GP. Less complex variables and a GP can be utilised to improve predictive uncertainty quantification in (medical) image analysis.</li>
    <li>Fuse variational inference and deep kernel learning (similar to NF) to produce SVDKL for improved analysis estimates with multiple classifications (novel).</li>
    <li>Prove our own method of using PCA with a GP layer to quantify the uncertainty within the Bone Age Dataset as proposed by Wu et al [1]. To do so, we will:</li>
    <ul>
        <li>Capture variation in the pre-processed dataset with Principal Component Analysis (PCA). % Transform the input data into a simpler distribution to capture complex dependencies.</li>
        <li>Feed variables into the GP to compute the mean and covariance of the predictive distribution to produce predictions associated with uncertainties.</li>
    </ul>
</ul>

[1] Wu, Z., Yang, Y., Gu, J., &  Tresp, V. (2021). Quantifying predictive uncertainty in medical image analysis with deep kernel learning. arXiv preprint arXiv:2106.00638.