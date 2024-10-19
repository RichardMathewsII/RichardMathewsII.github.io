---
title: WriteAssist - A GenAI Assitant for Writing-Heavy Classrooms
tags: [Python, GenAI]
date: 2024-08-15
image: /assets/projects/writeassist/logo.png
description: Reduce teacher burnout and improve student ​writing proficiency by equipping teachers with a ​classroom-aligned AI assistant that automates ​feedback generation and supports students with ​1:1 counseling.
---

<p class="text-center">
{% include elements/button.html link="https://github.com/RichardMathewsII/writeassist-llmops/" text="GitHub" %}
</p>

<p class="text-center">
{% include elements/button.html link="https://writeassist.my.canva.site/" text="Project Website (Demo)" %}
</p>

![frame1](/assets/projects/writeassist/PoC%20img.png)

## Summary
The problem in K-12 writing education is two-fold.

1. Teachers across the nation are facing an alarming level of stress and dissatisfaction due to overwhelming workloads, low pay, and a lack of appreciation. An all-time low 12% of teachers report being very satisfied with their jobs, and more than 50% of teachers would not recommend teaching to their younger selves, highlighting a growing crisis in the teaching profession that demands urgent attention. (Source)
2. Inadequate individualized feedback on student essays is hindering learning and growth in K-12 education. Teachers, burdened by heavy workloads, struggle to provide meaningful feedback, leaving students without the guidance and support needed to improve their writing skills. As a result, students often disregard feedback, leading to disengagement and a missed opportunity for academic advancement. (Anecdote from writing teacher)

I believe these two birds can be killed with one stone–GenAI. I pursued this problem for my data science capstone project at Berkeley and achieved great success. I led four other students through an agile implementation of a PoC deployed on AWS over a 12 week stretch and got selected as one of 6 teams (out of 33) to present at the showcase.

I also used this project as an opportunity to explore some ideas I had around end-to-end GenAI experimentation. I put together an implementation that worked very well using dagster, MLFlow, and Streamlit. Using this system, we were able to configure our deployed version to an optimal state for our tasks.

If you are interested in exploring more about the project or want to see a demo of the app or experimentation system, please visit the link below.

<p class="text-center">
{% include elements/button.html link="https://writeassist.my.canva.site/" text="Project Website (Demo)" %}
</p>

![frame1](/assets/projects/writeassist/PoC%20img.png)

## Contributions
Since my product idea was selected at the beginning of the semester, I took on the leadership role and really drove the project as the key contributor. Here are the highlights of my contributions:

👉 Formulated novel product idea and strategy, conducted market research and competitor analysis
👉 Led 4 developers in agile implementation of the PoC over 12 week period
👉 One of 6 teams (out of 33) to advance to the capstone showcase
👉 Combined machine learning theory, ​MLOps, and GenAI to construct a ​GenAIOps concept that allowed us to ​experiment over all components of our ​system in a scalable, transparent, and ​cost-efficient way
👉 Designed the GenAI inference architecture and implemented using dagster and OpenAI

## Credits
* Thank you to my capstone team–Emily McPherson, Daphne Lin, Patrick Xu, Sabreena Naser
* Thank you to my mentors–Joyce Shen and Kira Wetzel