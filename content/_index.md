+++
title = "Workshop on Parallelizing \"Inherently Sequential\" Computation"
+++

The rise of massively parallel hardware has transformed AI and ML, yet many important models---including recurrent neural networks (RNNs), denoising diffusion models, and Markov chain Monte Carlo (MCMC)---were long believed to be "inherently sequential." Remarkably, researchers across different fields have independently converged on similar algorithmic breakthroughs to parallelize these processes, unlocking order-of-magnitude speedups on GPUs. Application domains of these parallel-in-time algorithms include:

- **Deep sequence modeling**, including linear attention, deep state space models (SSMs), and the parallelization of nonlinear recurrent neural networks (RNNs).
- **Deep generative modeling**, including parallelizing the sampling of diffusion models and structured variational autoencoders.
- **Classical probabilistic modeling**, including parallelizing Kalman filtering and smoothing, as well as Markov chain Monte Carlo (MCMC).

Yet because these communities rarely speak the same language, best practices remain siloed, and the full potential of these techniques is far from realized. This workshop breaks down these disciplinary walls, bringing together researchers for concrete discussions about shared techniques, open problems, and a path toward a unified algorithmic toolkit.

{{ new_block() }}

# Call for Papers

Details on paper submissions coming soon. Please check back for updates on submission guidelines, formatting requirements, and important dates.

{{ button(name = "Call for Papers", url = "papers")}}
