---
layout: page
title: About Me
permalink: /about/
---
<div style="overflow: auto;">
  <img src="/assets/images/ntnu_hoeyde_eng.png" style="float: right; max-width: 40%; margin-right: 1em;">
    <div style="overflow: hidden;">
      <p>I am a norwegian PhD student at the Department of Mathematical Sciences at the Norwegian University of Science and Technology (NTNU). I have a Masters degree in [Applied Physics and Mathematics](https://www.ntnu.edu/studies/mtfyma) awarded by NTNU in 2020.</p>
  </div>
</div>

My main research interest is understanding how to utilize learning-based methods in practical applications. I believe generative models in weak supervision data settings is one of the most widely applicable and efficient methods for solving many problems. With weak supervision I mean what is traditionally called unsupervised and semi-supervised learning, as opposed to strong supervision which is traditionally called supervised learning. There are a few reasons for this:

- Generative models learn the *structure* of the data, which can then be applied to different tasks. This is in contrast to learning how to solve specific problems *discriminatively*. In the discriminate paradigm, trained models can only be used for the specific problem (and data) they were trained for.
- Discriminate fitting also requires (large amounts) of strong supervision data. While discriminate models have paved the way for more general learning-based methods for many decades (even centuries), I believe in what I call the *strong supervision bottleneck*. In the coming years, the performance of discriminative models will plateau because there simply is not enough available strong supervision data, and training (generative) models with weak supervision will be more efficient.
- Generative models (with discriminative fine-tuning, as opposed to discriminative fitting) have recently proven to be absurdly effective at many tasks. The prime example is of course ChatGPT, where some already claim that we have reached something close to AGI.

One facet of learning-based methods that has always interested me is exactly where the line between *knowledge-based* modelling and *data-driven* model fitting should be drawn. This usually comes down to what *parameterization* we choose, as described by Vladimir Vapnik before I was even born:

>The matter is that in solving the function estimation problems in both
computational statistics (say pattern recognition, regression, density estimation) and in computational mathematics (say, obtaining approximations
to the solution to multidimensional (operator) equations of different types)
the first step is describing (parametrizing) a set of functions in which one
is looking for a solution. <br> - *The Nature of Statistical Learning Theory*, Vladimir N. Vapnik, 1995.}

My fascination with this topic started when I was doing a summer internship at a research institute when I was about 22 years old. During this summer, I worked on thermodynamics, specifically modelling of electrolytes. I spent over a month implementing a heavily theoretical method for minimizing Gibbs free energy to calculate some quantity of interest. The model was a sort of [Van der Waals](https://en.wikipedia.org/wiki/Van_der_Waals_equation) model on steroids. One thing that bothered me about this model was that even though it was based on a lot of physical modelling, it still required parameters that had to be tuned experimentally. To compare against the method, I implemented something called the [Pitzer equations](https://en.wikipedia.org/wiki/Pitzer_equations), which was a much simpler physical model that relied more on experimentally tuned parameters. This model took an afternoon to implement, and gave better results in basically every metric when tested on experimental data. It was at this point I asked myself: 

>When do we stop modelling and just rely on fitting to experimental data? To what degree can we rely on data?. 

It is a bit absurd to me that I had to clarity to ask this question when I was still so young, but I am still hunting for an answer to this question.
