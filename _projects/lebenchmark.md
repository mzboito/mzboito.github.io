---
layout: page
title: <i>LeBenchmark</i> Project
description: Models and benchmarking for the French language
importance: 2
category: model
related_publications: true
permalink: /projects/lebenchmark/
---

<section class="project-category">
  <h2 class="category">About</h2>
  <p>
    <em>LeBenchmark</em> was a project focused on training wav2vec 2.0 models for the French language. 
    It was a group effort between many public and private institutions in France. 
    Throughout the project, we produced several models that were made available to the scientific community under <strong>Apache-2.0 license</strong>. 
    We also produced a benchmark covering seven tasks and different tuning settings, in order to evaluate the performance of such SSL models in different downstream tasks. 
    For more information, check these publications: 
    <a href="https://www.isca-archive.org/interspeech_2021/evain21_interspeech.pdf" target="_blank">LeBenchmark</a> and 
    <a href="https://arxiv.org/pdf/2309.05472" target="_blank">LeBenchmark 2.0</a>.
  </p>
</section>

<section class="project-category">
  <h2 class="category">Link to resources</h2>
  <ul>
    <li>
      Our collection of models: 
      <a href="https://huggingface.co/LeBenchmark" target="_blank">
        <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" width="25" style="vertical-align:middle;" alt="Hugging Face"/>
      </a>
    </li>
    <li>
      Other resources: 
      <a href="https://github.com/LeBenchmark" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="25" style="vertical-align:middle;" alt="GitHub"/>
      </a>
    </li>
  </ul>
</section>

<section class="project-category">
  <h2 class="category">Citing us</h2>
  <p>
    We have several publications related to this project. If you simply want to mention the existence of the project, please cite both LeBenchmark (Interspeech) and LeBenchmark 2.0 (Journal) publications. They are listed below:
  </p>

  <div class="resources-page">
{% highlight bibtex %}
@article{parcollet24_lebenchmark,
  title = {LeBenchmark 2.0: A standardized, replicable and enhanced framework for self-supervised representations of French speech},
  journal = {Computer Speech & Language},
  volume = {86},
  pages = {101622},
  year = {2024},
  issn = {0885-2308},
  doi = {https://doi.org/10.1016/j.csl.2024.101622},
  url = {https://www.sciencedirect.com/science/article/pii/S0885230824000056},
  author = {Titouan Parcollet and Ha Nguyen and Solène Evain and Marcely Zanon Boito and Adrien Pupier and Salima Mdhaffar and Hang Le and Sina Alisamir and Natalia Tomashenko and Marco Dinarelli and Shucong Zhang and Alexandre Allauzen and Maximin Coavoux and Yannick Estève and Mickael Rouvier and Jerôme Goulian and Benjamin Lecouteux and François Portet and Solange Rossato and Fabien Ringeval and Didier Schwab and Laurent Besacier},
}
@inproceedings{evain21_interspeech,
  title = {Le{B}enchmark: A Reproducible Framework for Assessing Self-Supervised Representation Learning from Speech},
  author = {Solène Evain and Ha Nguyen and Hang Le and Marcely Zanon Boito and Salima Mdhaffar and Sina Alisamir and Ziyi Tong and Natalia Tomashenko and Marco Dinarelli and Titouan Parcollet and Alexandre Allauzen and Yannick Estève and Benjamin Lecouteux and François Portet and Solange Rossato and Fabien Ringeval and Didier Schwab and Laurent Besacier},
  year = {2021},
  booktitle = {Interspeech 2021},
  pages = {1439--1443},
  doi = {10.21437/Interspeech.2021-556},
  issn = {2958-1796},
}
{% endhighlight %}
</div>

In case you want to explicitly cite our work on frozen or unfrozen speech encoders, please refer to the following publication:

<div class="resources-page">
{% highlight bibtex %}
@inproceedings{evain21_task,
 author = {Evain, Sol\`{e}ne and Nguyen, Ha and Le, Hang and Zanon Boito, Marcely and Mdhaffar, Salima and Alisamir, Sina and Tong, Ziyi and Tomashenko, Natalia and Dinarelli, Marco and Parcollet, Titouan and Allauzen, Alexandre and Est\`{e}ve, Yannick and Lecouteux, Benjamin and Portet, Fran\c{c}ois and Rossato, Solange and Ringeval, Fabien and Schwab, Didier and besacier, laurent},
 booktitle = {Proceedings of the Neural Information Processing Systems Track on Datasets and Benchmarks},
 editor = {J. Vanschoren and S. Yeung},
 title = {Task Agnostic and Task Specific Self-Supervised Learning from Speech with {L}e{B}enchmark},
 url = {https://datasets-benchmarks-proceedings.neurips.cc/paper_files/paper/2021/file/b3e3e393c77e35a4a3f3cbd1e429b5dc-Paper-round2.pdf},
 volume = {1},
 year = {2021},
}
{% endhighlight %}
</div>
</section>
