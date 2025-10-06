---
layout: page
title: IWLST 22 Models and Code
description: Wav2vec 2.0 models and code for Tamasheq
importance: 5
category: model
related_publications: true
permalink: /projects/iwslt22/
---

### about

Avignon University co-organized the IWSLT 2022 low-resource track. We supplied participants with two wav2vec 2.0 models trained on Tamasheq speech: a Tamasheq-only model (243 hours) and a multilingual model (658 hours). Following the challenge, we released our speech translation code to the research community. This work was supported by the European SELMA project and the ANR ON-TRAC project.

### link to resources

- Tamasheq-only wav2vec 2.0: <a href="https://huggingface.co/LIA-AvignonUniversity/IWSLT2022-tamasheq-only">
  <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" width="20" style="vertical-align:middle;" alt="Hugging Face"/></a>

- Niger-Mali wav2vec 2.0: <a href="https://huggingface.co/LIA-AvignonUniversity/IWSLT2022-Niger-Mali">
  <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" width="20" style="vertical-align:middle;" alt="Hugging Face"/></a>

- Training recipe: <a href="https://github.com/speechbrain/speechbrain/tree/develop/recipes/IWSLT22_lowresource">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="20" style="vertical-align:middle;" alt="GitHub"/></a>

### citing us

For citing us, please use the bibtex below:

<div class="resources-page">
{% highlight bibtex %}
@inproceedings{zanon-boito-etal-2022-trac,
    title = "{ON}-{TRAC} Consortium Systems for the {IWSLT} 2022 Dialect and Low-resource Speech Translation Tasks",
    author = {Boito, Marcely Zanon and
      Ortega, John  and
      Riguidel, Hugo  and
      Laurent, Antoine  and
      Barrault, Lo{\"i}c  and
      Bougares, Fethi  and
      Chaabani, Firas  and
      Nguyen, Ha  and
      Barbier, Florentin  and
      Gahbiche, Souhir  and
      Est{\`e}ve, Yannick},
    editor = "Salesky, Elizabeth  and
      Federico, Marcello  and
      Costa-juss{\`a}, Marta",
    booktitle = "Proceedings of the 19th International Conference on Spoken Language Translation (IWSLT)",
    month = may,
    year = "2022",
    address = "Dublin, Ireland (in-person and online)",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.iwslt-1.28/",
    doi = "10.18653/v1/2022.iwslt-1.28",
    pages = "308--318",
}
{% endhighlight %}
</div>
