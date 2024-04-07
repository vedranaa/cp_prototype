---
layout: default
---

# Check assignments
**QUIZ. DURATION: 30min**


{% include question.html label="FIRST" text="First question?" choices="Yes;No;Maybe" correct=1 %}

{% include question.html label="SECOND" text="Second question?" choices="Yes;No;Maybe" correct="0;1;1" %}

{% capture q1text %}
This is a question. Say we want some code in it.
```python
def hello():
    print("Hello, world!")
hello()
```
And now the question is: What will this code do?
{% endcapture %}

{% capture q1A %}
```python
def hello():
    print("Hello, world!")
hello()
```
{% endcapture %}

{% capture q1B %}
It will print `Hello, world!`.
{% endcapture %}

{% capture q1AB %}
{{q1A}};{{q1B}}
{% endcapture %}

{% assign q1choices = q1AB %}
{% include question.html label="q1" text=q1text choices=q1choices correct=0 %}

{% assign q2text = "Here comes another question. Do you like this?"  %}
{% assign q2choices = "True; False" %}
{% include question.html label="q2" text=q2text choices=q2choices correct=0 %}