+++
title = "Workshop on Parallelizing \"Inherently Sequential\" Computation"
+++

Evaluating recurrent neural networks, generating from diffusion models, and sampling via Markov chain Monte Carlo were all believed to be "inherently sequential"---a fundamental bottleneck in the age of massively parallel hardware.
Remarkably, researchers in sequential, generative, and probabilistic modeling have independently converged on similar algorithmic breakthroughs to parallelize these processes, unlocking order-of-magnitude speedups.
Yet, because these communities rarely speak the same language, these best practices remain siloed, and the full potential of these techniques is far from realized.
This workshop breaks down these disciplinary walls.
We will bring together researchers from these disparate disciplines for concrete discussions about shared techniques, open problems, and a path toward a unified algorithmic toolkit.

The rise of massively parallel hardware has transformed algorithmic and architectural development in AI and ML.
GPUs are designed for parallel computation, allowing for massive speedups. However, a wide variety of chain-like models---including recurrent neural networks (RNNs), denoising diffusion models, and Markov chain Monte Carlo (MCMC)---appear at first glance to be "inherently sequential."

The field has responded by finding ways to parallelize "inherently sequential" computation over the sequence length. **On GPUs, these parallel-in-time algorithms unlock order-of-magnitude speedups for models previously dismissed as "inherently sequential."** Application domains include:

- **Deep sequence modeling**, including attention, linear attention, deep state space models (SSMs), and the parallelization of nonlinear recurrent neural networks (RNNs).
- **Deep generative modeling**, including parallelizing the sampling of diffusion models and structured variational autoencoders.
- **Classical probabilistic modeling**, including parallelizing filtering, smoothing, and Markov chain Monte Carlo (MCMC).

Excitingly, almost identical techniques for parallelization-in-time are being used across these subfields---but siloing has led to the omission or reinvention of important techniques. This workshop will bring together researchers from all of these fields to share best practices and establish common vocabularies.

{{ new_block() }}

{{ list(section_name = "speakers") }}

{{ new_block() }}

# Schedule

| Time | Event |
|------|-------|
| 8:00 - 8:15 | Introduction by organizers |
| 8:15 - 8:45 | Invited talk (Sepp Hochreiter) |
| 8:45 - 9:15 | Invited talk (Will Merrill) |
| 9:15 - 10:30 | Coffee + Posters |
| 10:30 - 11:00 | Invited talk (Daniela Rus) |
| 11:00 - 12:00 | Contributed Spotlight Talks I, II, III |
| 12:00 - 13:00 | Lunch Break |
| 13:00 - 13:30 | Invited talk (Albert Gu) |
| 13:30 - 14:00 | Invited talk (Federico Danieli) |
| 14:00 - 15:00 | Coffee + Posters |
| 15:00 - 15:30 | Invited talk (Songlin Yang) |
| 15:30 - 16:00 | Invited talk (Stefano Ermon) |
| 16:00 - 16:45 | Panel discussion |
| 16:45 - 17:00 | Closing remarks |
| Afterward | Social event ("happy hour") |

{{ new_block() }}

# Call for Papers

Details on paper submissions coming soon. Please check back for updates on submission guidelines, formatting requirements, and important dates.

{{ button(name = "Call for Papers", url = "papers")}}

{{ new_block() }}

# Organizers

{{ grid(
    text = [
        ["Xavier Gonzalez","Stanford University"],
        ["Yutong Bai","UC Berkeley"],
        ["Adrien Corenflos", "University of Warwick"],
        ["Mónika Farsang","TU Wien"],
        ["Leo Kozachkov", "Brown University"],
        ["Korbinian Pöppel", "ELLIS Institute Tübingen"],
        ["David M. Zoltowski", "Stanford University"],
        ["Scott W. Linderman", "Stanford University"],
    ],
    urls = [
        "https://xaviergonzalez.github.io/",
        "https://yutongbai.com/",
        "https://adriencorenflos.github.io/",
        "https://monifarsang.github.io/",
        "https://kozleo.github.io/",
        "https://korbi.ai/",
        "https://www.davidzoltowski.com/",
        "https://web.stanford.edu/~swl1/",
    ],
    image_dir = "organizers") }}

{{ button(name = "About", url = "about") }}

{{ new_block() }}

# Contact

For any questions, ideas, or suggested speakers, please contact the organizers at [xavier18@stanford.edu](mailto:xavier18@stanford.edu) or [scott.linderman@stanford.edu](mailto:scott.linderman@stanford.edu).
