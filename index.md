---
layout: default
title: Home
---
# Additive Motherhood: Nature, Nurture, and Quantitative Genetics

Welcome! I am a PhD Student in Crop Science at Washington State University and a new mom. This space is a professional portfolio of my research and a personal log of my journey through the $F_1$ generation of parenthood.

🧬 Research Focus: The D-Genome Explorer
My doctoral research is dedicated to Germplasm Enhancement in bread wheat (_Triticum aestivum_). I explore the allelic diversity of its ancestral relative, _Aegilops tauschii_, to identify novel alleles for:

Agronomic Resilience: Improving yield stability.
Nutritional Density: Enhancing the micronutrient profile of modern cultivars.

By partitioning the genetic variance ($V_G$) contributed by the D-genome progenitor, I work to overcome the evolutionary bottleneck that limits modern wheat's potential.

📂 Explore the Journey
Below is a dynamic list of my latest logs and technical updates:

🧬 Genetics
<ul> {% assign genetics_files = site.pages | where_exp: "p", "p.path contains 'genetics/'" | where_exp: "p", "p.name != 'index.md'" %} {% assign genetics_posts = genetics_files | where_exp: "p", "p.name != 'README.md'" %}

{% if genetics_posts.size > 0 %} {% for p in genetics_posts %} <li><a href="{{ p.url | relative_url }}">{{ p.name | replace: ".md", "" | replace: "-", " " }}</a></li> {% endfor %} {% else %} {% assign genetics_readme = genetics_files | where: "name", "README.md" | first %} <li><a href="{{ genetics_readme.url | relative_url }}">Research Overview: Aegilops tauschii & Allele Discovery</a></li> {% endif %}

</ul>

🍼 Motherhood & The Inverse Maternal Effect: Documenting how my child shapes me—the environmental shift of a lifetime.
<ul> {% assign motherhood_files = site.pages | where_exp: "p", "p.path contains 'motherhood/'" | where_exp: "p", "p.name != 'index.md'" %} {% assign motherhood_posts = motherhood_files | where_exp: "p", "p.name != 'README.md'" %}

{% if motherhood_posts.size > 0 %} {% for p in motherhood_posts %} <li><a href="{{ p.url | relative_url }}">{{ p.name | replace: ".md", "" | replace: "-", " " }}</a></li> {% endfor %} {% else %} {% assign motherhood_readme = motherhood_files | where: "name", "README.md" | first %} <li><a href="{{ motherhood_readme.url | relative_url }}">The Inverse Maternal Effect (Overview)</a></li> {% endif %}

</ul>

✈️ Travel & Global Variance: Exploring the world's cultures and cuisines through my lens.
<ul> {% assign travel_files = site.pages | where_exp: "p", "p.path contains 'travel/'" | where_exp: "p", "p.name != 'index.md'" %} {% assign travel_posts = travel_files | where_exp: "p", "p.name != 'README.md'" %}

{% if travel_posts.size > 0 %} {% for p in travel_posts %} <li><a href="{{ p.url | relative_url }}">{{ p.name | replace: ".md", "" | replace: "-", " " }}</a></li> {% endfor %} {% else %} {% assign travel_readme = travel_files | where: "name", "README.md" | first %} <li><a href="{{ travel_readme.url | relative_url }}">Travel & Global Variance (Overview)</a></li> {% endif %}

</ul>

📊 Core Competencies
Statistical Modeling: Linear Mixed Models (LMM) for $V_A$ and $V_E$ estimation.
Bioinformatics: Proficient in R and growing in Python for genomic data processing.
Genomic Selection: Applying GWAS and selection index theory to predict breeding values ($EBVs$).

The Breeder's Equation of Motherhood: 
$$R = h^2 S$$

My daily Response ($R$) is a function of my academic Heritability ($h^2$) and the Selection ($S$) of the environments I choose to navigate.
---

*Follow my updates as I navigate the G × E interactions of a life in transition.*
