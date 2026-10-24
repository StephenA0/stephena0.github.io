---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I’m a 3rd-year Algorithms, Combinatorics, and Optimization (ACO) PhD Student at Carnegie Mellon University (CMU) in the Operations Research department. My research interests are broadly in approximation algorithms and combinatorial optimization, where I have primarily worked with Benjamin Moseley.

I obtained my M.S. in Algorithms, Combinatorics, and Optimization (ACO) from CMU in 2026. Before joining CMU, I obtained my B.S. in Computer Science and Mathematics from the University of Pittsburgh in 2024, where I was mentored by Kirk Pruhs.

**Contact Info:** sarndt@andrew.cmu.edu

## Publications

### Conference Publications

{% assign conferences = site.publications | where: "category", "conferences" | sort: "publication_order" %}
<div class="publication-list">
{% for post in conferences %}
  <article class="publication-entry">
    <h4 class="publication-title"><a href="{{ post.link }}">{{ post.title }}</a></h4>
    <p class="publication-details">{{ post.excerpt }}.</p>
    <p class="publication-venue"><i>{{ post.venue }}</i>.{% if post.award %} <strong class="publication-award">{{ post.award }}</strong>{% endif %}</p>
    {% if post.slidesurl %}<p class="publication-links"><a href="{{ post.slidesurl }}">Download Slides</a></p>{% endif %}
  </article>
{% endfor %}
</div>

### arXiv Preprints

{% assign preprints = site.publications | where: "category", "preprints" | sort: "publication_order" %}
<div class="publication-list">
{% for post in preprints %}
  <article class="publication-entry">
    <h4 class="publication-title"><a href="{{ post.link }}">{{ post.title }}</a></h4>
    <p class="publication-details">{{ post.excerpt }}.</p>
    <p class="publication-venue"><i>{{ post.venue }}</i>.{% if post.award %} <strong class="publication-award">{{ post.award }}</strong>{% endif %}</p>
    {% if post.slidesurl %}<p class="publication-links"><a href="{{ post.slidesurl }}">Download Slides</a></p>{% endif %}
  </article>
{% endfor %}
</div>

## Invited Talks

### Approximation Algorithms for Matroid-Intersection Coloring with Applications to Rota's Basis Conjecture

- Jul 2027: ISMP 2027 Approximation and Online Algorithms session talk
- Sep 2026: UIUC CS Theory Seminar
- Sep 2026: Michigan CS Theory Seminar
- May 2026: Waterloo Graphs and Matroids Seminar
- Apr 2026: CMU OR Seminar

## Workshops

- Sep 2026: [Cargèse Workshop](https://www.cargese.org/2026/) on Combinatorial Optimization
- Jul 2026: [Emléktábla Workshop](https://users.renyi.hu/~emlektab/) on Matroid Theory
- Jun 2026: [MAPSP Workshop](https://mapsp2026.webspace.durham.ac.uk/) on Scheduling

## Teaching

### TAing

- Fall (Mini) 2026: Network Optimization II (graduate)
- Summer (Mini) 2026: Optimization for Business (undergrad)
- Spring 2026: Optimization for Business (undergrad)
- Spring 2026: Integer Programming (graduate)

### Grading

- Spring 2026: Final Grader, Optimization for Business (MBA)

### Tutoring

- Spring 2017–26: High School Math Tutor, Algebra I - Calculus II and Physics / AP Physics (500+ hours)

## Professional Activities

### CMU INFORMS

#### Roles

- Aug 2026–27: President
- Mar–Aug 2026: YinzOR Logistics Co-Chair
- Aug 2025–26: Treasurer
- Mar–Aug 2025: YinzOR Flash Talk & Poster Session Co-Chair
- Aug 2024–25: Undergrad Outreach Chair

#### Talks

- Feb 2025: Pitt CSC Grad School Talk
- Nov 2024: CMU OR Grad School Talk
- Feb 2024: Pitt CSC Grad School Talk

### Meet-and-Think Seminar

Meet-and-Think Seminar is an informal, student-only weekly seminar for CMU OR, ACO, Math, etc. PhD Students whose primary purposes are to a) learn about other students’ research topics or interests, b) give a casual environment for students to meet and practice speaking skills, and c) to receive a free afternoon snack each week 😃.

**Organizer:** Mar 2025–Present

### Reviews

**Current review counter:** 7

- 2026: FOCS, APPROX, IEEE ToN, ORL
- 2027: SODA (x3)

## Awards and Scholarships

- Nov 2026: FOCS Best Paper Award
- Mar 2026: Litzenberger Family Fund Award
- Jan 2026: Egon Balas Award (Best CMU OR/ACO Summer Paper)
- Aug 2024: Dean’s PhD Scholarship Award
- Apr 2024: Pitt CS Outstanding Undergraduate Award

## ACO Qualifying Exam Notes

- [Algorithms Course Notes](/files/aco-qualifying-exam-notes/algorithms-course-notes.pdf)
- [Discrete Math Course Notes](/files/aco-qualifying-exam-notes/discrete-math-course-notes.pdf)
- [IP Course Notes](/files/aco-qualifying-exam-notes/ip-course-notes.pdf)
- [LP Course Notes](/files/aco-qualifying-exam-notes/lp-course-notes.pdf)
- [MCO Course Notes](/files/aco-qualifying-exam-notes/mco-course-notes.pdf)

### Calculus, Intuitively

A 60-page [introduction to Calculus](https://drive.google.com/file/d/1bn58Pj-KD6pm5TVbrXFFwIr4gsxCvw0q/view?usp=sharing) written during the 2020 COVID Lockdowns.

## Pictures

<figure class="personal-picture">
  <img src="/images/me-bella-tchalla.jpg" alt="Stephen Arndt with Bella and T'Challa">
  <figcaption>Me, Bella, and T'Challa</figcaption>
</figure>
