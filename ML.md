---
layout: page
permalink: /ML/
title: Machine Learning
description: Showcase your writing, short stories, or poems. Replace this text with your description.
---


Machine Learning (ML)
“Machine Learning” es parte del campo de estudio de Inteligencia Artificial enfocado al aprendizaje automatico de las computadoras, es decir que las computadoras tengan la habilidad de aprender sin tener que ser explicitamente progrmadas.
Como ejemplo de aplicaciones ML tenemos el poder catalogar si un email es spam o no, predecir el clima, predecir si un tumor es tipo maligno o no, etc.
Entre los modelos principales de ML se encuentran los de tipo supervisado (Supervised Learning) y los de tipo no-supervisado (Unsupervised Learning)
Supervised Learning vs Unsupervised Learning
Los modelos supervisados son aquellos modelos que nos permiten enseñar a la maquina, mediante el uso de datos ya conocidos.
# ML models

1 Supervised Learning
  1.1 Classification
            K-Nearest Neighbors
            Decision Trees 
            Support Vector Machines
            Logistic Regression
  1.2 Regression
2 Unsupervised Learning
  2.1 Clustering
  2.2 Association Rule Learning
  2.3 Visualization and Dimensionality Reduction
3 Semisupervised Learning
4 Reinforcement Learning



<ul class="post-list">
{% for poem in site.poetry reversed %}
    <li>
        <h2><a class="poem-title" href="{{ poem.url | prepend: site.baseurl }}">{{ poem.title }}</a></h2>
        <p class="post-meta">{{ poem.date | date: '%B %-d, %Y — %H:%M' }}</p>
      </li>
{% endfor %}
</ul>
