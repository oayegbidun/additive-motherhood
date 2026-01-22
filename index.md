---
layout: default
title: Home
---

# Additive Motherhood: Nature, Nurture, and Quantitative Genetics

Welcome! I am a PhD Student in Crop Science [Quantitative Genetics Focus] at Washington State University and a new mom. 
This space serves as a professional portfolio for my research and a personal log of my journey through the $F_1$ generation of parenthood.

## Explore the Journey

🧬 Genetics
<ul> {% assign genetics_files = site.pages | where_exp: "p", "p.path contains 'genetics/'" | where_exp: "p", "p.name != 'index.md'" %} {% assign genetics_posts = genetics_files | where_exp: "p", "p.name != 'README.md'" %}

{% if genetics_posts.size > 0 %} {% for p in genetics_posts %} <li><a href="{{ site.baseurl }}/{{ p.path | replace: '.md', '.html' }}">{{ p.name | replace: ".md", "" | replace: "-", " " }}</a></li> {% endfor %} {% else %} {% for p in genetics_files %} <li><a href="{{ site.baseurl }}/{{ p.path | replace: '.md', '.html' }}">Coming Soon (View Overview)</a></li> {% endfor %} {% endif %}

</ul>

🍼 Motherhood
<ul> {% assign motherhood_files = site.pages | where_exp: "p", "p.path contains 'motherhood/'" | where_exp: "p", "p.name != 'index.md'" %} {% assign motherhood_posts = motherhood_files | where_exp: "p", "p.name != 'README.md'" %}

{% if motherhood_posts.size > 0 %} {% for p in motherhood_posts %} <li><a href="{{ site.baseurl }}/{{ p.path | replace: '.md', '.html' }}">{{ p.name | replace: ".md", "" | replace: "-", " " }}</a></li> {% endfor %} {% else %} {% for p in motherhood_files %} <li><a href="{{ site.baseurl }}/{{ p.path | replace: '.md', '.html' }}">Coming Soon (View Overview)</a></li> {% endfor %} {% endif %}

</ul>

✈️ Travel
<ul> {% assign travel_files = site.pages | where_exp: "p", "p.path contains 'travel/'" | where_exp: "p", "p.name != 'index.md'" %} {% assign travel_posts = travel_files | where_exp: "p", "p.name != 'README.md'" %}

{% if travel_posts.size > 0 %} {% for p in travel_posts %} <li><a href="{{ site.baseurl }}/{{ p.path | replace: '.md', '.html' }}">{{ p.name | replace: ".md", "" | replace: "-", " " }}</a></li> {% endfor %} {% else %} {% for p in travel_files %} <li><a href="{{ site.baseurl }}/{{ p.path | replace: '.md', '.html' }}">Coming Soon (View Overview)</a></li> {% endfor %} {% endif %}

</ul>
---

## Quantitative Genetics & Research
My academic focus lies in the statistical modeling of polygenic traits. I am particularly interested in how we partition variance to understand complex traits.

### Core Competencies:
* **Linear Mixed Models (LMM):** Estimating variance components ($V_A, V_E$) and predicting breeding values ($EBVs$).
* **Genomic Architecture:** Analyzing the polygenic nature of traits through GWAS and selection index theory.
* **Bioinformatics:** Proficient in **R** and beginner in **Python** for large-scale genomic data processing.

> **Mathematical Lens:** I view motherhood through the Breeder's Equation:
> $$R = h^2 S$$
> Where my daily Response ($R$) is a function of my academic Heritability ($h^2$) and the Selection ($S$) of the environments I choose to navigate.

## The Maternal Effect
In genetics, maternal effects describe the influence of a mother’s phenotype on her offspring's phenotype. 

## The Inverse Maternal Effect
Traditional quantitative genetics focuses on how I shape my child. Here, I document how my child shapes me—the **Inverse Maternal Effect**. 

Motherhood has been the most significant environmental shift of my life, impacting my:
* **Computational Efficiency:** Learning to code in the small windows of nap time.
* **Adaptive Capacity:** Preparing for new horizons (both personal and professional).
* **Statistical Perspective:** Seeing the beauty in the noise of a chaotic schedule.

---
*Follow my updates as I navigate the G × E interactions of a life in transition.*
