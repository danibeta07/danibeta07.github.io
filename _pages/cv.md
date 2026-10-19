---
layout: single
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

[Download my full CV (PDF)](/files/Daniela_Betancurt_Anzola_CV.pdf)

## Education

**Ph.D. candidate, Biochemistry, Microbiology and Molecular Biology**  
The Pennsylvania State University | 2022–present  
Expected completion: Summer 2027  
Advisor: Dr. Estelle Couradeau

**M.Sc., Computational Biology**  
Universidad de los Andes, Bogotá, Colombia | 2022  
Thesis: Divergent response of the gut microbiome to a high-fiber diet  
Advisors: Dr. Alejandro Reyes and Dr. Federico Rey

**B.Sc., Biology, and B.Sc., Microbiology**  
Universidad de los Andes, Bogotá, Colombia | 2018  
Minor in Psychobiology

## Research appointments

**Graduate Researcher, Couradeau Lab**  
The Pennsylvania State University | 2024–present  
Soil microbial ecology, genome-resolved metagenomics, and multi-omics research in Colombian páramo wetlands.

**Graduate Researcher, Bisanz Lab**  
The Pennsylvania State University | 2022–2024  
Microbial engineering, automated strain screening, and mouse studies for a probiotic strategy targeting dietary mercury bioavailability.

**Laboratory Manager, Affect and Cognition Lab**  
Cornell University | 2021–2022  
Molecular biology workflows, human sample processing, gut microbiome analysis, and undergraduate mentoring.

**Research Assistant, Computational Biology and Microbial Ecology Lab**  
Universidad de los Andes | 2020–2022  
Integration of gut microbiome, metabolomics, and biomarker data from a dietary-fiber experiment.

**Research Assistant, Affect and Cognition Lab**  
Cornell University | 2018–2019  
Human gut microbiome profiling and experimental support for neuroscience research.

## Publications

<ul>
{% assign papers = site.publications | sort: "date" | reverse %}
{% for paper in papers %}
{% if paper.category == "manuscripts" %}
  <li><p>{{ paper.citation }} <a href="{{ paper.paperurl }}">Read article</a></p></li>
{% endif %}
{% endfor %}
</ul>

## Selected awards and fellowships

- **Interdisciplinary Innovation Fellowship**, One Health Microbiome Center, Penn State | 2025
- **Best Poster Award**, Páramos 2025 Symposium, Bogotá, Colombia | 2025
- **International Graduate Education Award**, Penn State | 2024
- **Future Leaders Mentoring Fellowship**, American Society for Microbiology | 2023–2025
- **Summer Undergraduate Research Fellowship**, Universidad de los Andes; research placement at Cornell University | 2018

## Teaching and mentoring

I have mentored undergraduate researchers at Penn State and Cornell University, taught undergraduate laboratory courses, and led microbiome research workshops.

[Teaching, mentoring, and workshop experience](/teaching/)

## Leadership and service

- Organizing Committee Member, One Health Microbiome Center Symposium, Penn State | 2025–2026
- Workshop Chair, Data Analysis Working Group, One Health Microbiome Center, Penn State | 2024–2026
- National Microbiome Data Collaborative Champion | 2025
- National Microbiome Data Collaborative Ambassador | 2024
- First-Year Representative, BMMB Graduate Student Association, Penn State | 2023

## Research skills

**Computational:** R, Python, Bash, Git/GitHub, HPC, SLURM, Conda, and reproducible analysis workflows.

**Microbiome and multi-omics:** Genome-resolved metagenomics, amplicon analysis, untargeted metabolomics, statistical modeling, and data visualization.

**Experimental:** Molecular biology, cloning, microbial culture, high-throughput strain screening, Opentrons automation, environmental sampling, and animal models (mice and rats).
