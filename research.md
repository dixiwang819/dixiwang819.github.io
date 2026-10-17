---
title: Research
layout: default
---
<style>
.project-card {
  display: flex;
  align-items: center;
  gap: 24px;
  border: 1px solid #ddd;
  border-radius: 12px;
  padding: 22px;
  margin: 24px 0;
}

.project-text {
  flex: 1;
  min-width: 0;
}

.project-image {
  flex: 0 0 35%;
}

.project-image img {
  width: 100%;
  height: auto;
  border-radius: 8px;
  display: block;
}

.project-text h3 {
  margin-top: 0;
}

/* Mobile screens */
@media (max-width: 600px) {
  .project-card {
    flex-direction: column;
    align-items: stretch;
  }

  .project-image {
    flex: auto;
    width: 100%;
  }
}
</style>

<h1>Research Projects</h1>

<p>
My current interest mainly focuses on deep learning for manifold-structured data, control-based algorithms and building connections between computational mean field games and machine learning theories.
</p>

<!-- Project 1 -->
<div class="project-card">

  <div class="project-text">
    <h3>Generative Modeling</h3>

  <p>
     We formulate optimal transport as an in-context operator-learning problem. We train a single solution operator that maps a pair of probability distributions to their optimal transport map. Given only a small number of samples from a previously unseen source--target pair as context, the model can infer the corresponding transport map without gradient updates.
  </p>

  <p>
      <a href="https://arxiv.org/abs/2601.09979">Paper</a>
  </p>
  </div>

  <div class="project-image">
    <img src="assets/From Gaussian to Dog Manifold.png"
         alt="Generative modeling illustration">
  </div>

</div>


<!-- Project 1 -->
<div class="project-card"
     style="background-image: url('assets/From Gaussian to Dog Manifold.png');">

  <div class="project-content">
    <h3>In-Context Learning on the Space of Probability Measures</h3>
    <p> We formulate optimal transport as an in-context operator-learning problem. We train a single solution operator that maps a pair of probability distributions to their optimal transport map. Given only a small number of samples from a previously unseen source--target pair as context, the model can infer the corresponding transport map without gradient updates.</p>
    <a href="https://arxiv.org/abs/2601.09979">Paper</a>
  </div>

</div>

<!-- PROJECT 1 -->
<div style="border:1px solid #ddd; border-radius:10px;
            padding:20px; margin:22px 0;">

  <h3 style="margin-top:0;">
    In-Context Learning on the Space of Probability Measures
  </h3>

  <p style="color:#666; font-size:14px;">
    Dixi Wang, Frank Cole, Yineng Chen, Yulong Lu, Rongjie Lai | 2026
  </p>

  <p>
    We formulate optimal transport as an in-context operator-learning problem. We train a single solution operator that maps a pair of probability distributions to their optimal transport map. Given only a small number of samples from a previously unseen source--target pair as context, the model can infer the corresponding transport map without gradient updates.
  </p>

  <p style="margin-bottom:0;">
    <a href="https://arxiv.org/abs/2601.09979" target="_blank">Paper</a>
    &nbsp;
  </p>

</div>

<!-- PROJECT 2 -->
<div style="border:1px solid #ddd; border-radius:10px;
            padding:20px; margin:22px 0;">

  <h3 style="margin-top:0;">
    Training Dynamics of Attention Networks
  </h3>

  <p style="color:#666; font-size:14px;">
    Dixi Wang, Yuan Gao, Rongjie Lai | 2026
  </p>

  <p>
    Write the description of your second project here.
  </p>

  <p style="margin-bottom:0;">
    <a href="https://arxiv.org/" target="_blank">Paper</a>
    &nbsp; | &nbsp;
    <a href="https://github.com/" target="_blank">Code</a>
  </p>

</div>
