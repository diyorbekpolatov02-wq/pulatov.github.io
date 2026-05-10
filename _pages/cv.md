---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* **Advanced Master in Medical Physics** (110/110 Cum Laude)  
  The Abdus Salam International Centre for Theoretical Physics (ICTP) & University of Trieste, Italy  
  *Jan 2024 – Dec 2025*  
  Thesis: *Intercomparison, validation, and implementation of tools for in-vivo dosimetry*

* **Training in Hospital — Clinical Medical Physics**  
  IRCCS Azienda Ospedaliero-Universitaria di Bologna (Policlinico di Sant'Orsola), Italy  
  *Jan 2025 – Dec 2025*  
  Thesis: *Implementation, validation, and intercomparison of tools for in-vivo dosimetry*

* **Scientific Visit — Dosimetry**  
  International Atomic Energy Agency (IAEA), Dosimetry Laboratory (SSDL), Seibersdorf, Austria  
  *Aug 2024*

* **Training and Research (Hungaricum Scholarship)**  
  Budapest University of Technology and Economics & HUN-REN Centre for Energy Research, Hungary  
  *Aug 2023 – Feb 2024*  
  Thesis: *Application of Monte Carlo Simulation for Internal Dose Assessment*

* **Master's Degree in Nuclear Physics and Astronomy** (GPA: 4.77/5)  
  Samarkand State University, Uzbekistan  
  *Sep 2020 – Jun 2022*  
  Thesis: *Application and effectiveness of proton therapy in onconeosurgery*

* **Bachelor's Degree in Physics** (GPA: 4.2/5)  
  Samarkand State University, Uzbekistan  
  *Sep 2016 – Jun 2020*

---

## Work Experience

* **Researcher** — Engineering Physics Institute, Samarkand State University  
  *Jan 2026 – Present* | Samarkand, Uzbekistan  
  - Preparing reports on radioactive analysis of water, soil, construction materials, and air
  - Installation and calibration of radiation detectors
  - Responsible for the establishment of the new Master's program in Medical Physics

* **Junior Researcher** — Nuclear Physics Laboratory, Samarkand State University  
  *Sep 2022 – Sep 2023* | Samarkand, Uzbekistan  
  - Calibration of NaI(Tl) and HPGe detectors and their verification
  - Passive measurements of Rn-222 in air using activated charcoal sorption columns
  - Monte Carlo simulation with Geant4 and Python data analysis

* **Physics Teacher** — Public School № 31  
  *Sep 2019 – Feb 2022* | Samarkand, Uzbekistan

---

## Skills

**Programming:** Python, C++, Linux  
**Simulation:** Monte Carlo with Geant4 and GATE  
**Python Libraries:** NumPy, Pandas, Seaborn, Matplotlib  
**Medical Physics Software:** ImageJ, Pinnacle TPS, Mosaiq R&V  
**Dosimetry:** MOSFET, GafChromic film, HPGe, ionization chambers, TLD, OSLD, RPLD  
**QA Systems:** LINAC (ELEKTA), Brachytherapy, SPECT, PET, CT, MRI  
**Dosimetry Software:** Sun Nuclear PerFRACTION, Dosisoft EPIgray Edition 2.0

---

## Languages

| Language | Level |
|----------|-------|
| Uzbek | Native |
| English | Advanced (IELTS Band Score 7) |
| Russian | Pre-Intermediate |
| Italian | Beginner |

---

## Publications

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

---

## Teaching

{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
