---
layout: default
---

# Check assignments
**QUIZ. DURATION: 30min**


{% assign q1text = "Here is a question. Is this fun?" %}
{% assign q1choices = "True, False" | split: ', ' %}
{% assign q1feedbacks = "Correct!  This is awesome., How can you say that?!" | split: ', ' %}
{% include mc-question.html text=q1text choices=q1choices correct=0 feedbacks=q1feedbacks label="q1" %}

{% assign q2text = "Here comes another question. Do you like this?"  %}
{% assign q2choices = "True, False" | split: ', ' %}
{% assign q2feedbacks = "Correct!  This is awesome., How can you say that?!" | split: ', ' %}
{% include mc-question.html text=q2text choices=q2choices correct=0 feedbacks=q2feedbacks label="q2" %}


