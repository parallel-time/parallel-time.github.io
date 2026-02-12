+++
title = "About"
+++

# About

The rise of massively parallel hardware has transformed algorithmic and architectural development in AI and ML.
GPUs are designed for parallel computation, allowing for massive speedups. However, a wide variety of chain-like models---including recurrent neural networks (RNNs), denoising diffusion models, and Markov chain Monte Carlo (MCMC)---appear at first glance to be "inherently sequential." This perceived mismatch between the capabilities of hardware and the requirements of algorithm often led to the deprecation of such "inherently sequential" approaches.

Remarkably, the field has responded by finding ways to parallelize "inherently sequential" computation over the sequence length. On GPUs, these parallel-in-time algorithms unlock order-of-magnitude speedups for models previously dismissed as "inherently sequential."

Application domains of such parallel-in-time algorithms to machine learning include:

1. **Deep sequence modeling**, including attention, linear attention, deep state space models (SSMs), and the parallelization of nonlinear recurrent neural networks (RNNs).

2. **Deep generative modeling**, including parallelizing the sampling of diffusion models and structured variational autoencoders.

3. **Classical probabilistic modeling**, including parallelizing filtering and smoothing, and Markov chain Monte Carlo (MCMC).

Excitingly, almost identical techniques for parallelization-in-time are being used across these different subfields. However, the diversity of fields and approaches has led to siloing, including the omission or reinvention of important techniques across different fields.

With the explosion of interest in all of these areas, the time is ripe for this workshop to bring together researchers from different fields to share best practices and establish common vocabularies.


{{ new_block() }}


# Organizers

**[Xavier Gonzalez](https://xaviergonzalez.github.io/)** ([Google Scholar](https://scholar.google.com/citations?user=5sj7cH8AAAAJ&hl=en)) is a final-year PhD student at Stanford. He has published work parallelizing nonlinear state space models like RNNs, MCMC, and more. Previously, he read for an MSc in Statistics at Oxford as a Rhodes Scholar. *Contact organizer.*

**[Yutong Bai](https://yutongbai.com/)** ([Google Scholar](https://scholar.google.com/citations?user=N1-l4GsAAAAJ&hl=en&oi=ao)) is a Postdoctoral Researcher at UC Berkeley (BAIR), advised by Alexei A. Efros, Jitendra Malik, and Trevor Darrell. She received her PhD in Computer Science from Johns Hopkins and is a 2023 Apple Scholar in AI/ML and MIT EECS Rising Star. Her research focuses on robust, self-supervised, and generative visual learning.

**[Adrien Corenflos](https://adriencorenflos.github.io/)** ([Google Scholar](https://scholar.google.com/citations?user=sJJ7FKgAAAAJ&hl=en&oi=ao)) is an Assistant Professor in the Department of Statistics at the University of Warwick. His research focuses on computational statistics and probabilistic machine learning, with a marked focus on computational and statistical parallelism, with application to Monte Carlo methodology and state-space models.

**[Mónika Farsang](https://monifarsang.github.io/)** ([Google Scholar](https://scholar.google.com/citations?user=Z8t3t7YAAAAJ&hl=en)) is a PhD student at TU Wien, focusing on interpretable and biologically inspired neural architectures, particularly liquid neural networks, exploring the trade-off between biological interpretability and scalable long-sequence modeling.

**[Leo Kozachkov](https://kozleo.github.io/)** ([Google Scholar](https://scholar.google.com/citations?user=V5dtdeUAAAAJ&hl=en&oi=ao)) is an Assistant Professor in the School of Engineering at Brown University and the Carney Institute for Brain Science. His research focuses on understanding dynamics, control, and computation in both natural and artificial systems.

**[Korbinian Pöppel](https://korbi.ai/)** ([Google Scholar](https://scholar.google.com/citations?user=sBrtrxwAAAAJ&hl=en&oi=ao)) is a post-doctoral researcher at the ELLIS Institute Tübingen. He works on hardware-efficient, scalable novel architectures for sequence modeling, combining gating mechanisms with associative memory for advanced recurrent models.

**[David M. Zoltowski](https://www.davidzoltowski.com/)** ([Google Scholar](https://scholar.google.com/citations?user=ZnxTn6IAAAAJ&hl=en&oi=ao)) is a Postdoctoral Scholar in the Department of Statistics at Stanford University. His research broadly focuses on probabilistic machine learning and computational neuroscience. He has developed algorithms to parallelize the evaluation of nonlinear dynamical systems.

**[Scott W. Linderman](https://web.stanford.edu/~swl1/)** ([Google Scholar](https://scholar.google.com/citations?user=6mD3I24AAAAJ&hl=en&oi=ao)) is an Assistant Professor at Stanford University in the Statistics Department and the Wu Tsai Neurosciences Institute, and the Co-Director of the Stanford Center for Neural Data Science. His research focuses on machine learning and neuroscience, and he has made important contributions in parallelizing sequential algorithms. *Contact organizer.*


{{ new_block() }}


# Program Committee

Akshat Agarwal,
Amber Hu,
Angikar Ghosal,
Axel Finke,
Christos Merkatas,
Etaash Katiyar,
Ezio Bartocci,
Fatemeh Yaghoobi,
Federico Danieli,
Federico Perlino,
Filip Tronarp,
Filippo Pagani,
Gabe Guo,
Hai-Dang Dau,
Hany Abdulsamad,
Hugo Queniat,
Hyung Dong Lee,
Ian Christopher Tanoh,
Jakub Smekal,
Jens Sjolund,
Julien Siems,
Kelly Buchanan,
Lanya Yang,
Lorenzo Rimella,
Margaret Trautner,
Martin Tappler,
Massimiliano Tamborrino,
Matei Stan,
Matt Sutton,
Maximilian Beck,
Mihaela-Larisa Clement,
Nicola Branchini,
Nicolas Zucchet,
Noah Cowan,
Radu Grosu,
Riccardo Grazzi,
Rocco Caprio,
Sahel Iqbal,
Sam Duffield,
Sara Perez-Vieites,
Shenggang Hu,
Skyler Wu,
Xiaoyu Lin,
Yvann Le Fay
