---
layout: default
title: Home
nav_order: 1
---

# Advanced Natural Language Processing
{: .mb-2 }
Spring 2027
{: .mb-2 .fs-6 .text-grey-dk-000 }


**Instructor**: 		[Sewon Min](https://www.sewonmin.com/)<br />
**Class hours**: 		TuThu 11:00-12:30 (11:10-12:30 considering Berkeley time) <br />
**Class location**: 	Gateway 1220 <br />
**Instructor OH**: 		TBA<br />
**GSI OH**: TBA<br />
**Contact**: <a href="#" class="contact-guidance-toggle" aria-controls="contactGuidance" aria-expanded="false" onclick="var panel=document.getElementById('contactGuidance'); panel.hidden=!panel.hidden; this.setAttribute('aria-expanded', String(!panel.hidden)); return false;">Please read before emailing</a><br />

<div id="contactGuidance" class="contact-guidance-panel" hidden markdown="1">
<button type="button" class="contact-guidance-close" aria-label="Close contact guidance" onclick="document.getElementById('contactGuidance').hidden=true; document.querySelector('.contact-guidance-toggle').setAttribute('aria-expanded', 'false');">&times; Close</button>

To help us respond quickly and make sure your question reaches the right people, please use the routes below. None of these situations requires emailing instructor Sewon Min at her Berkeley address. Course related emails sent directly to her will be automatically filtered and deleted, so please follow the guidance below.

<details class="contact-guidance-item" markdown="1">
<summary>I have questions about enrollment.</summary>

**Please submit the [Spring 2027 enrollment form](https://docs.google.com/forms/d/e/1FAIpQLSdpeEROA-xMt6LWIPoqBDXWPRmWWsiHE0E1muQWVHXscXaQew/viewform) by January 19 to be considered for enrollment.** All the information you need is included in the form. Enrollment decisions will be finalized no later than January 29, so please do not email before then to ask for an early decision. If you still have an enrollment question that the form does not answer, email [sewonm.admin+cs288@gmail.com](mailto:sewonm.admin+cs288@gmail.com).
</details>

<details class="contact-guidance-item" markdown="1">
<summary>I have questions about class materials.</summary>

Please ask during instructor office hours, which are held immediately after class, or post on Ed.
</details>

<details class="contact-guidance-item" markdown="1">
<summary>I have questions about assignments or projects.</summary>

Please use Ed for technical questions, requests for clarification, and other assignment- or project-related questions. You may post privately on Ed for confidential questions.
</details>

<details class="contact-guidance-item" markdown="1">
<summary>I have a DSP request.</summary>

You do not need to email the course staff. Please submit your request directly through DSP, and the course staff will follow up with you. If you have not heard from us within two weeks of submitting the request, email [sewonm.admin+cs288@gmail.com](mailto:sewonm.admin+cs288@gmail.com).

DSP requests related to assignments, projects, or the midterm should be submitted at least two weeks before the relevant deadline. For example, a midterm-related DSP request should be submitted by March 23.
</details>

<details class="contact-guidance-item" markdown="1">
<summary>I want to audit the class.</summary>

You are always welcome to audit—there is no need to ask the course staff for permission.
</details>

<details class="contact-guidance-item" markdown="1">
<summary>I have a course conflict.</summary>

Lectures will be recorded and livestreamed, so you are welcome to participate remotely by watching the class recording. The sessions you must attend in person are the midterm on April 6 and the poster sessions on April 20 and April 22. The midterm review on April 8 will not be recorded or livestreamed, so you will also need to attend that session if you would like to participate in it.
</details>

<details class="contact-guidance-item" markdown="1">
<summary>My question is not answered above.</summary>

Please use Ed whenever possible; private posts are welcome. If you cannot post on Ed, or if you have not received a response within four days of posting on Ed, email [sewonm.admin+cs288@gmail.com](mailto:sewonm.admin+cs288@gmail.com). If you have already posted on Ed, please include a link to the corresponding Ed post.
</details>
</div>

\[Ed link: TBA\] \[Gradescope link: TBA\] \[Lecture recordings: TBA\] \[Final project logistics and reference topics: TBA\]

<div id="enrollmentNote" class="alert alert-warning">
  <b>Enrollment for students who cannot enroll directly:</b> <b>Please submit the <a href="https://docs.google.com/forms/d/e/1FAIpQLSdpeEROA-xMt6LWIPoqBDXWPRmWWsiHE0E1muQWVHXscXaQew/viewform">Spring 2027 enrollment form</a> by January 19 to be considered for enrollment.</b> Enrollment depends on seat availability and is not guaranteed. Applicants should generally have A or A+ grades in at least three of CS 188, CS 189, CS 126, CS 127, CS 182, and CS 183, or have Berkeley research or project experience. All information needed is included in the form. Enrollment will be finalized no later than January 29; before then, please do not email to request an early decision.
</div>


<hr />

This course provides a graduate-level introduction to Natural Language Processing (NLP), covering techniques from foundational methods to modern approaches. We begin with core concepts such as word representations and neural network–based NLP models, including recurrent networks and attention mechanisms. We then study modern Transformer-based models, focusing on pre-training, fine-tuning, prompting, scaling laws, and post-training. The course concludes with recent advances in NLP, including retrieval-augmented models, reasoning models, and multimodal systems involving vision and speech.

**Prerequisites**: CS 288 assumes prior experience in machine learning and proficiency in PyTorch. Students should be familiar with neural networks, PyTorch, and NumPy; no introductory tutorials will be provided.

## Schedule (Tentative)
All deadlines are at 5:59 PM Pacific Time.

{% for module in site.modules %}
{{ module }}
{% endfor %}


## Acknowledgement

The class materials, including lectures and assignments, are largely based on the following courses, whose instructors have generously made their materials publicly available. We are deeply grateful to them for sharing their work with the broader community:
- [Princeton COS 484 Natural Language Processing](https://princeton-nlp.github.io/cos484/) by Danqi Chen, Tri Dao, Vikram Ramaswamy
- [CMU Advanced Natural Language Processing](https://cmu-l3.github.io/anlp-fall2025/) by Graham Neubig & Sean Welleck
- [Stanford CS336 Language Modeling from Scratch](https://stanford-cs336.github.io/spring2025/) by Tatsumori Hashimoto & Percy Liang
- [Cornell LM-class](https://lm-class.org/) by Yoav Artzi
- [An earlier offering of UC Berkeley EECS 288 Natural Language Processing](https://cal-cs288.github.io/fa24/) by Dan Klein and Alane Suhr
