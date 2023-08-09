# python-tools
A comparison of useful Python tools

## To use on your laptop
Download [Anaconda 3.11](https://www.anaconda.com/download) for your operating system. Follow the installation instructions there.

Please use this distribution even if you have a different version pre-installed on your laptop. We want to ensure that each student has access to the same computing environment with the same Python libraries.

## Cloud environments

We are looking for a cloud environment that serves two purposes: students can use it a backup if their laptop is not powerful enough, and (in some classes) teachers can distribute and collect code for in-class and out-of-class assignments, minimizing the friction of downloading code and data.

The language is Python 3.10 (preferably 3.11 to match the recommended Anaconda distro). In-class instruction will use JupyterLab, so it would be great if that platform included this as an IDE that students are already familiar with. Some courses do machine learning where GPU access is a big plus.  

| Name | Link | Costs | Class management | Jupyter | Notes |
|---|---|---|---|---|---|
| GitHub Codespaces | https://docs.github.com/codespaces | [$0.09/core-hour](https://docs.github.com/en/billing/managing-billing-for-github-codespaces/about-billing-for-github-codespaces#pricing-for-paid-usage) | Can be combined with GitHub Classroom. | Jupyter is available by selecting "Open in JupyterLab" or adding `?editor=jupyter` to the end of the URL. See [blog post](https://github.blog/changelog/2022-11-09-using-codespaces-with-jupyterlab-public-beta/). | Costs can be [centralized by organization](https://docs.github.com/en/codespaces/managing-codespaces-for-your-organization/choosing-who-owns-and-pays-for-codespaces-in-your-organization). Hosted in Docker containers, does not seem to have GPUs. Directly linked to a repo. |
| Google Colab | https://colab.google/ | Starts free, [€0.12/compute-unit](https://colab.research.google.com/signup/pricing) Compute units are unclear. | Can be synced with GitHub, so possible to use GitHub Classroom.  | Starts immediately with Jupyter Notebook. | Has variable explorer. Has GPU. [Library versions](https://github.com/CEU-Economics-and-Business/python-tools/blob/755b8b549558851b7ed2e25d52e658d2cd9b0396/versions.ipynb). |  
| Replit | https://replit.com/ | [Free for edu institutions](https://replit.com/pricing) | There are teams to which it is easy to invite students and score their assignments. | No | |
| Hex | https://hex.tech/ | ? | ? | ? | ? |
| Deepnote | https://deepnote.com/home | ? | ? | ? | ? |
| Binder | https://mybinder.org/ | ? | ? | ? | ? |
| Nuvolos | https://nuvolos.cloud/ | [€10/month](https://nuvolos.cloud/pricing) | ? | ? | ? |
