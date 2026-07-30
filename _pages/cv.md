---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Computer Science and Engineering, The Chinese University of Hong Kong, 2019–2024
  * Supervisor: Prof. Zili Shao
  * Focus: Mobile and embedded systems, Android OS, display management, runtime optimization, energy efficiency
* B.S. in Computer Science (Outstanding Graduate), Xi'an Jiaotong University, 2015–2019
  * GPA: 3.95/4.3, Rank: 4/160
  * National Scholarship (Top 2/160), 2016

Work experience
======
* **Postdoctoral Researcher** (July 2024 – Present)
  * The Chinese University of Hong Kong
  * Duties: Proposed and implemented display-centric process model to address UI latency; designed generalized LLM-mobile interaction interface; architected privacy-preserving framework against WebView data exfiltration; developed transparent layout rearrangement for cross-screen adaptation.

* **Graduate Researcher (Ph.D.)** (June 2019 – July 2024)
  * The Chinese University of Hong Kong
  * Duties: Designed RCHDroid for runtime configuration handling (ASPLOS'23, TACO'25); introduced semantics-aware display management for foldable devices (LCTES'22); created MSA framework for transparent multi-screen support (TCAD'23); innovated Q-learning-based display energy optimization (TCAD'25).

* **Undergraduate Researcher** (July 2015 – June 2019)
  * Xi'an Jiaotong University
  * Duties: Built voice-controlled smartphone app (ML/NLP); developed web-based welfare platform; investigated blockchain consensus algorithms; designed traffic prediction platform (ARIMA/logistic regression) at Huawei Cloud Computing Elite Program.

Skills
======
* **Systems & OS**: Android framework (AOSP), Linux kernel, x86 assembly, operating system internals
* **Programming**: C, C++, Java, Python, Shell scripting
* **Performance Optimization**: Runtime configuration management, display energy optimization, UI latency reduction
* **Machine Learning**: Reinforcement learning (Q-learning), NLP, ARIMA
* **Tools & Platforms**: Git, Docker, QEMU/Bochs, Jekyll, LaTeX

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* **Reviewer** for IEEE TCAD, ACM TACO, and other conferences/journals (if applicable)
* **Professor Charles K. Kao Student Creativity Awards** (2021) – DSA: Dual-Screen Android System (2/4)
* **National College Student Innovation Project** (2019) – Voice-controlled smart assistant (1/6)
* **Organizer** of internal workshops on mobile systems (if any)