---
layout: default

question1:
    label: question1
    text:  What is my favorite color?
    choices: 
    - Pink
    - Blue
    - Red
    - Yellow
    correct: "1"

question2:
    label: question2
    text:  What do I like to do?
    choices: 
    - Code
    - Read
    - Go to dentist
    - Play football
    correct: "1100"

question3:
    label: question3
    text: |
      I have this code
      ```python
      def foo():
      return "bar"
      ```
      How should it be fixed?
    choices: 
    - |
      ```python
      def foo():
          output "bar"
      ```
    - |
      ```python
      def foo():
      output "bar"
      ```   
    - |
      ```python
      def foo():
          return "bar"
      ```
    correct: "001"

---

# Check assignments
**QUIZ. DURATION: 30min**


{% include question.html label="FIRST" text="First question. What do you think?" choices="Yes;No;Maybe" correct=1 %}
{% include question.html label="SECOND" text="Second question. And now?" choices="Yes;No;Maybe" correct="011" %}
{% include question.html question=page.question1 %}
{% include question.html question=page.question2 %}
{% include question.html question=page.question3 %}