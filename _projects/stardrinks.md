---
layout: page
title: StarDrinks Test Set
description: An English and Korean test set for evaluating LLMs and speech assistants in a drink ordering scenario
importance: 1
category: data
related_publications: true
permalink: /projects/stardrinks/
---

<section class="project-category">
  <h2 class="category">About</h2>
  <p>
    <strong>StarDrinks</strong> is a test set in <strong>English and Korean</strong> for evaluating LLMs
    and speech assistants in a realistic <strong>drink ordering</strong> scenario. Task-oriented systems
    are often assessed under controlled conditions that fail to capture the variability of real user
    requests: diverse named entities, drink types, sizes, customizations, and brand-specific terminology,
    as well as spontaneous speech phenomena such as hesitations and self-corrections.
  </p>
  <p>
    The dataset contains speech utterance features, transcriptions, and annotated slots, and supports three
    evaluation settings: <strong>speech-to-slots</strong> (SLU), <strong>transcription-to-slots</strong> (NLU),
    and <strong>speech-to-transcription</strong> (ASR). Collected from authentic drink orders, it provides a
    linguistically rich benchmark for measuring model robustness and generalization to previously unseen
    named entities.
  </p>
</section>

<section class="project-category">
  <h2 class="category">Downloading the data</h2>
  <ul>
    <li>
      Dataset:
      <a href="https://europe.naverlabs.com/research/publications/stardrinks-an-english-and-korean-test-set-for-evaluating-llms-in-a-coffee-ordering-deployment-scenario/" target="_blank">
        NAVER LABS Europe
      </a>
    </li>
  </ul>
  <p>
    Access requires agreeing to a custom license: please sign the license agreement available on the
    dataset page above before downloading.
  </p>
</section>

<section class="project-category">
  <h2 class="category">Citing us</h2>
  <p>When using our dataset, please cite the following paper:</p>

<div class="resources-page">
{% highlight bibtex %}
@inproceedings{zanon-boito-etal-2026-stardrinks,
    title = "{S}tar{D}rinks: An {E}nglish and {K}orean Test Set for {SLU} Evaluation in a Drink Ordering Scenario",
    author = "Zanon Boito, Marcely  and
      Brun, Caroline  and
      Kim, Inyoung  and
      Proux, Denys  and
      Ait-Mokhtar, Salah  and
      Lagos, Nikolaos  and
      Meunier, Jean-Luc  and
      Calapodescu, Ioan",
    booktitle = "Proceedings of the 2026 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC)",
    month = may,
    year = "2026",
    address = "Palma de Mallorca, Spain",
    publisher = "European Language Resources Association",
    url = "https://arxiv.org/abs/2604.26500",
}
{% endhighlight %}
</div>
</section>
