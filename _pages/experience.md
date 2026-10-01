---
title: "Experience"
permalink: /experience/
layout: single
author_profile: true
---

## Research Projects

### Measuring Learning Engagement in Multi-Person Virtual Reality
*Human Factors & Simulation Lab, University of Oklahoma · Aug 2024 – Present*  
*NSF CAREER project: "Non-text-based smart learning in fully immersive multi-person virtual reality using multimodal analysis of physiological measures." PI: Dr. Ziho Kang*

In this project, people in different places join one virtual classroom. We use eye movements, hand interactions, and brain activity to measure and predict how engaged they are in learning.

- Helped design the multi-person VR experiments and build the task scenes in Vizard and Godot. Ran the experiments with more than 60 participants and recorded fNIRS, eye-tracking, and behavior data.

<figure class="half" style="max-width:720px; margin:1em auto 1.5em;">
  <img src="/images/experience/vr-task-scene.jpg" alt="Single-person VR semantic network task" style="aspect-ratio:3/2; object-fit:cover; margin-bottom:0.3em;">
  <img src="/images/experience/vr-multi-person.jpg" alt="Multi-person VR semantic network task" style="aspect-ratio:3/2; object-fit:cover; margin-bottom:0.3em;">
  <figcaption style="text-align:center;">Left: the single-person VR semantic network task. Right: the multi-person version. Each colored laser shows where a participant is looking in real time.</figcaption>
</figure>

- Led the fNIRS data analysis, from preprocessing and filtering to motion artifact correction.
- Found that the eye-tracking cameras in VR headsets add periodic infrared noise to fNIRS signals. Developed a filtering method based on FFT and seasonal-trend decomposition (STL) to remove it. The method needs no hardware change and works on data that has already been collected.

<figure class="half" style="max-width:720px; margin:1em auto 1.5em;">
  <img src="/images/experience/fnirs-before-filtering.png" alt="fNIRS signal before filtering" style="margin-bottom:0.3em;">
  <img src="/images/experience/fnirs-after-filtering.png" alt="fNIRS signal after filtering" style="margin-bottom:0.3em;">
  <figcaption style="text-align:center;">fNIRS signal from one optode before (left) and after (right) filtering. The regular peaks on the left come from the eye-tracking cameras.</figcaption>
</figure>

- Built time-window measures from head, hand, and gaze data. These show how behavior changes during a task.
- Outcome: one first-author IEEE conference paper ([read the paper](https://doi.org/10.1109/BioSMART66413.2025.11046131){:target="_blank"}) and one accepted HFES paper. A journal paper on the filtering method is in preparation.

### Human Perception of Adaptive Cruise Control (ACC)
*Human Factors & Simulation Lab, University of Oklahoma · Mar 2024 – 2026 · Project Lead*

- Adapted a validated ACC simulation model in MATLAB. Compared an electric vehicle and a gas vehicle, each following a gas vehicle, in two scenarios: a highway merge with hard braking, and stop-and-go traffic.
- Introduced three measures of driver perception: perceived safety, consistency, and comfort. The electric vehicle scored higher on all three in both scenarios.
- Outcome: first-author paper in *Traffic Injury Prevention* (2026). [Read the paper](https://doi.org/10.1080/15389588.2026.2658780){:target="_blank"}

<figure style="display:block; max-width:500px; margin:1.5em auto;">
  <img src="/images/experience/acc-system.png" alt="ACC car-following system" style="width:100%; margin-bottom:0.3em;">
  <figcaption style="text-align:center;">Overview of the ACC system. The following car uses its front sensor to track the car ahead and adjust its speed.</figcaption>
</figure>

### Login Failures on the VA eBenefits Website
*University of Virginia · Mar 2023 – May 2023*

- Helped build a probabilistic model of login failures on the eBenefits / VA.gov website.
- Implemented and checked the model algorithms.
- Showed that the DS Logon path improves the login success rate.
- Outcome: co-authored paper at the AHFE 2023 International Conference.

<figure style="display:block; max-width:450px; margin:1.5em auto;">
  <img src="/images/experience/va-login-model.png" alt="Login model for the eBenefits website" style="width:100%; margin-bottom:0.3em;">
  <figcaption style="text-align:center;">Model of the login states on the eBenefits website.</figcaption>
</figure>

## Work Experience

### Research Assistant
*Human Factors & Simulation Lab, University of Oklahoma · Mar 2024 – Present*

- Work on VR experiments and driving simulation studies.
- Process and analyze fNIRS, eye-tracking, and behavior data in Python, R, and MATLAB.
- Write conference and journal papers with the research team.

### Teaching Assistant
*School of Industrial and Systems Engineering, University of Oklahoma · Aug 2024 – Present*

- Teach lab sessions, grade coursework, and hold office hours. See [Teaching](/teaching/).

### Technical Support Engineer Intern
*iFLYTEK Co., Ltd., Hefei, China · Jul 2021 – Sep 2021*

- Analyzed behavior and feedback data from over 1,000 users of online education platforms.
- Found common usability problems and shared them with the design team.
- Maintained user databases with Navicat and Fiddler.

## Skills

- **Programming:** Python, R, MATLAB
- **Simulation:** Arena, PTV Vistro
- **VR development:** Vizard, Godot
- **Design and analysis tools:** Figma, SAS, Origin
- **Data types:** fNIRS, eye tracking, VR motion data
