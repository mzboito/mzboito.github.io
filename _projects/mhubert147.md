---
layout: page
title: mHuBERT-147
description: The mHuBERT-147 SSL model family
importance: 1
category: model
related_publications: true
permalink: /projects/mhubert147/
---

<section class="project-category">
  <h2 class="category">About</h2>
  <p>
  The mHuBERT-147 models are multilingual compact and efficient self-supervised speech representation models. 
  They were trained and evaluated at NAVER LABS Europe with the funding of the UTTER EU project. 
  They are shared under the license <strong>CC-BY-NC-SA-4.0</strong>. 
  For more information, check our publication <a href="https://arxiv.org/pdf/2406.06371">here</a>.
  </p>
</section>

<section class="project-category">
  <h2 class="category">Link to resources</h2>
  <ul>
    <li>
      The mHuBERT-147 pre-trained models collection: 
      <a href="https://huggingface.co/collections/utter-project/mhubert-147-models-665f1c1dea9a5601a1bfc905" target="_blank">
        <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" width="20" style="vertical-align:middle;" alt="Hugging Face"/>
      </a>
    </li>

    <li>
      Intermediate checkpoints from the 3rd iteration:
      <a href="https://download.europe.naverlabs.com/mhubert147/" target="_blank">LINK</a>
      (<strong>user:</strong> user /<strong>password:</strong> copy the license mentioned above)
    </li>

    <li>
      The training code:
      <a href="https://github.com/utter-project/fairseq" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="20" style="vertical-align:middle;" alt="GitHub"/>
      </a>
    </li>

    <li>
      Pre-processing and clustering scripts:
      <a href="https://github.com/utter-project/mHuBERT-147-scripts" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="20" style="vertical-align:middle;" alt="GitHub"/>
      </a>
    </li>

    <li>
      HUTTER, a mHuBERT-147 CommonVoice Prototype:
      <a href="https://huggingface.co/utter-project/hutter-12-3rd-base" target="_blank">
        <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" width="20" style="vertical-align:middle;" alt="Hugging Face"/>
      </a>
    </li>

  </ul>
</section>
<section class="project-category">
  <h2 class="category">Citing us</h2>
  For citing us, please use the bibtex below:

  <div class="resources-page">
    {% highlight bibtex %}
    @inproceedings{zanonboito24_interspeech,
      title     = {m{H}u{BERT}-147: A Compact Multilingual {H}u{BERT} Model},
      author    = {Marcely Zanon Boito and Vivek Iyer and Nikolaos Lagos and Laurent Besacier and Ioan Calapodescu},
      year      = {2024},
      booktitle = {Interspeech 2024},
      pages     = {3939--3943},
      doi       = {10.21437/Interspeech.2024-938},
      issn      = {2958-1796},
    }
    {% endhighlight %}
  </div>

  <a rel="license" href="https://creativecommons.org/licenses/by-nc-sa/4.0/">
    <img alt="Creative Commons License" style="border-width:0" width="120"
        src="https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png" />
  </a>
</section>
