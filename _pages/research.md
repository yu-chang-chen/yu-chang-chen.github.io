---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

## Publication

### "Global Representation of the Conditional LATE Model: A Separability Result", with *[Haitian Xie](https://www.haitianxie.org)*, **Oxford Bulletin of Economics and Statistics**. [\[Published Version\]](https://onlinelibrary.wiley.com/doi/10.1111/obes.12476) [\[WP Version\]](https://arxiv.org/abs/2007.08106)

This paper studies the latent index representation of the conditional LATE model, making explicit the role of covariates in treatment selection. We ﬁnd that if the directions of the monotonicity condition are the same across all values of the conditioning covariate, which is often assumed in the literature, then the treatment choice equation has to satisfy a separability condition between the instrument and the covariate. This global representation result establishes testable restrictions imposed on the way covariates enter the treatment choice equation. We later extend the representation theorem to incorporate multiple ordered levels of treatment.

## Papers in Submission
### "Personalized Subsidy Rules", with *[Haitian Xie](https://www.haitianxie.org)*, Submitted. [\[arXiv\]](https://arxiv.org/abs/2202.13545)

Subsidies are commonly used to encourage behaviors that can lead to short- or long-term benefits. Typical examples include subsidized job training programs and provisions of preventive health products, in which both behavioral responses and associated gains can exhibit heterogeneity. This study uses the marginal treatment effect (MTE) framework to study personalized assignments of subsidies based on individual characteristics. First, we derive the optimality condition for a welfare-maximizing subsidy rule by showing that the welfare can be represented as a function of the MTE. Next, we show that subsidies generally result in better welfare than directly mandating the encouraged behavior because subsidy rules implicitly target individuals through unobserved heterogeneity in the behavioral response. When there is positive selection, that is, when individuals with higher returns are more likely to select the encouraged behavior, the optimal subsidy rule achieves the first-best welfare, which is the optimal welfare if a policy-maker can observe individuals' private information. We then provide methods to (partially) identify the optimal subsidy rule when the MTE is identified and unidentified. Particularly, positive selection allows for the point identification of the optimal subsidy rule even when the MTE curve is not. As an empirical application, we study the optimal wage subsidy using the experimental data from the Jordan New Opportunities for Women pilot study.

## Work in Progress
### Estimation and Inference in Two-Step Empirical Bayes Methods, with *[Shuo-Chieh Huang](https://sites.google.com/view/nonstationary)*

Empirical Bayes (EB) methods are widely employed in the estimation of fixed effects. Prominent examples in economics include teacher value-added measures (VAM) and neighborhood effects. In these applications, the estimated effects are often further used as inputs to subsequent statistical analysis. This paper studies the validity of such two-step procedures, in which the case when EB estimates are used as explanatory variables in regression is emphasized and studied extensively. Our result shows that, although the ordinary least square (OLS) two-step estimator is consistent in linear models, the standard errors could be substantially downward biased if one does not correct for generated regressors. For example, the standard errors can be 40 percent larger after the correction in a typical teacher VAM application. For non-linear regressions, we find that the two-step procedure is harder to justify, as the resulting estimator is generally inconsistent without imposing ad-hoc distributional assumptions.


### Empirical Bayes with Optimal Shrinkage Trees

This paper studies the estimation of treatment effects in settings where there are many treatment arms while each treatment arm only has a moderate sample size. Examples in economics include neighborhood effects, hospital effects, and teacher value-added measures. We propose an Empirical Bayes (EB) method, which we refer to as "EB with Optimal Shrinkage Trees", that overcomes the high-dimensionality by leveraging the auxiliary information contained in treatment characteristics. Our method starts with using a decision tree to group treatment arms with similar treatment characteristics. Then, we apply the Empirical Bayes methodology and shrink the individual effect estimate from each arm toward the average among the group it belongs to.  We show that our procedure can reduce the total mean squared errors (MSE) of the treatment effect estimators compared to estimators with no shrinkage and conventional EB estimators that do not consider treatment characteristics. Also, we propose a consistent model selection procedure to approximate the optimal tree that minimizes the MSE. Simulations calibrated to real-world settings confirm that the method can greatly reduce the estimation errors, especially when the treatment characteristics are highly correlated to treatment effects. 
