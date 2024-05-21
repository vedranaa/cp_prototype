---
layout: default

questions:
- text: | 
    What if this is a long question that spans multiple lines?  Maybe even some code?
    ```python
    def foo():
        return "bar"
    ```
  choices: 
  - |
    Pink. And also this is a long answer that spans multiple lines. Maybe I would like to introduce some code in the answer?
    ```python
    def foo():
        return "bar"
    ```
  - Blue
  - Red
  - Yellow
  correct: "1"

- text: Where was I born?
  choices: 
  - Daruvar
  - Zagreb
  - New York
  - Boston
  correct: "1"

- text: Where would I like to live?
  choices: 
  - Daruvar
  - Zagreb
  - New York
  - Odense
  correct: "0110"

- text: Another nice city?
  choices: 
  - Daruvar
  - Zagreb
  - New York
  - Boston
  correct: "3"
---

# This is to test the quiz functionality


{% include quiz.html questions=page.questions %}


