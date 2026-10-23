---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download the current CV (PDF)](/files/Su_Li_CV_Oct_2026.pdf) · Updated October 23, 2026

## Academic appointments

- **Rice University**, Houston, TX — Postdoctoral Fellow, Department of Computational Applied Mathematics and Operations Research, August 2025–present
  - Advisor: Dr. Andrew J. Schaefer
- **The University of Texas MD Anderson Cancer Center**, Houston, TX — Visiting Research Scholar, August 2025–present
  - Advisor: Dr. Iakovos Toumazis
- **University of Toronto**, Toronto, Canada — Postdoctoral Fellow, Department of Mechanical and Industrial Engineering, July 2024–July 2025
  - Advisors: Dr. Vahid Sarhangian; Dr. André Augusto Ciré (Rotman School of Management, University of Toronto); Dr. Adam Diamant (Schulich School of Business, York University)

## Education

- **Ph.D. in Industrial Engineering**, Texas A&M University, 2024 — GPA: 4.00/4.00
  - Advisor: Dr. Hrayer Aprahamian
- **M.S. in Industrial Engineering**, Georgia Institute of Technology, 2018 — GPA: 3.60/4.00
- **B.Eng. in Industrial and Systems Engineering**, The Hong Kong Polytechnic University, 2017 — GPA: 3.76/4.00; First Class Honors; minor in Software Engineering

## Research interests

Operations research and industrial engineering, with a focus on data-driven optimization for healthcare operations and public health decision-making. Research areas include optimization under uncertainty; combinatorial and network optimization; Markov decision processes and approximate dynamic programming; and optimization for data analytics. Applications include healthcare scheduling and resource allocation, screening and diagnostic strategies, and infectious disease prevention and control.

## Research proposal development

- **National Institutes of Health (NIH), two proposals:** Formalize research methods, mathematical models, and solution approaches, and translate the mathematical framework into clinical terms.
- **National Science Foundation (NSF), one proposal:** Contribute to developing and refining the methodology section.

## Peer-reviewed journal articles

<ul>{% for post in site.publications reversed %}
  {% if post.section == "peer-reviewed" %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}</ul>

## Submitted manuscripts

<ul>{% for post in site.publications reversed %}
  {% if post.section == "submitted-working" and post.status == "submitted" %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}</ul>

## Working papers

<ul>{% for post in site.publications reversed %}
  {% if post.section == "submitted-working" and post.status == "working" %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}</ul>

## Invited conference presentations

- INFORMS Annual Meeting, San Francisco, CA, 2026
- INFORMS Annual Meeting, Atlanta, GA, 2025
- CORS Annual Conference, Edmonton, Canada, 2025
- INFORMS Computing Society Conference, Toronto, Canada, 2025
- INFORMS Annual Meeting, Seattle, WA, 2024
- International Symposium on Mathematical Programming (ISMP), Montréal, Canada, 2024
- INFORMS Annual Meeting, Phoenix, AZ, 2023
- INFORMS Annual Meeting, Indianapolis, IN, 2022

## Honors and awards

- Outstanding Doctor of Philosophy in Industrial Engineering Student, Texas A&M University, 2023
- Department Entry Scholarship, Texas A&M University, 2019
- Dean's Honors List, Faculty of Engineering, The Hong Kong Polytechnic University, 2013–2017
- Commercial Radio 50th Anniversary Scholarship, 2016
- Department Entry Scholarship, The Hong Kong Polytechnic University, 2013

## Academic service

**Conference session chair**

- *Modeling for Mitigation: Designing Disease Control Protocols*, INFORMS Annual Meeting, 2025
- *Strengthening Healthcare Systems for Preparedness*, INFORMS Annual Meeting, 2024
- *Breaking the Chain: Using OR to Control Infectious Outbreaks*, INFORMS Annual Meeting, 2023

**Journal peer reviewer**

*INFORMS Journal on Data Science*; *Health Care Management Science*; *INFOR: Information Systems and Operational Research*; *Scientific Reports*; *AI and Ethics*; *Journal of King Saud University—Computer and Information Sciences*; *Discover Global Society*.

## Teaching experience

- **Instructor**, Rice University, August 2025–December 2026
  - CMOR 462: Optimization in Finance (Fall 2025 and Fall 2026)
  - CMOR 463: Operations Research in Healthcare (Spring 2026)
- **Teaching Assistant**, Texas A&M University, May 2022–December 2023
  - ISEN 620/320: Survey of Optimization / Operations Research I
  - ISEN 340: Operations Research II
  - ISEN 302: Economic Analysis of Engineering Projects
  - ISEN 230: Informatics for Industrial Engineers
