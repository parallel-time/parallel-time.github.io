+++
title = "Workshop on Parallelizing \"Inherently Sequential\" Computation"
+++


# Abstract

Evaluating recurrent neural networks, generating from diffusion models, and sampling via Markov chain Monte Carlo were all believed to be "inherently sequential"---a fundamental bottleneck in the age of massively parallel hardware.
Remarkably, researchers in sequential, generative, and probabilistic modeling have independently converged on similar algorithmic breakthroughs to parallelize these processes, unlocking order-of-magnitude speedups.
Yet, because these communities rarely speak the same language, these best practices remain siloed, and the full potential of these techniques is far from realized.
This workshop breaks down these disciplinary walls.
We will bring together researchers from these disparate disciplines for concrete discussions about shared techniques, open problems, and a path toward a unified algorithmic toolkit.

{{ new_block() }}

{{ list(section_name = "speakers") }}

{{ button(name = "Programme", url = "programme")}}

{{ button(name = "Papers", url = "papers")}}



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
