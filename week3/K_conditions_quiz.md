---
layout: default

questions:
- text: |
    Which of the suggested blocks of code can be used interchangeably with the block below?
    ``` python
    if a > 0:
        if b > 0:
            print('both numbers are positive')
    ```
  choices: 
  - |
    ``` python
    if (a > 0) or (b > 0):
        print('both numbers are positive')
    ```
  - |
    ``` python
    if (a > 0) and (b > 0):
        print('both numbers are positive')
    ```
  - |
    ``` python
    if (a > 0) and not (b <= 0):
        print('both numbers are positive')
    ```
  - |
    ``` python
    if not (a <= 0) or (b > 0):
        print('both numbers are positive')
    ```
  - |
    ``` python
    if not ((a <= 0) or (b <= 0)):
        print('both numbers are positive')
    ```  
  correct: "01101"

- text: |
    What gets printed when the following code is executed?
    ``` python
    a = 15
    if a > 10:
        print("too big")
    if a < 5:
        print("too small")
    else:
        print("just right")
    ```
  choices:
    - |
      ```
      too big
      ```
    - |
      ```
      too small
      ```
    - |
      ```
      just right
      ```
    - |
      ```
      too big
      too small
      ```
    - |
      ```
      too big
      just right
      ```
    - |
      ```
      too small
      just right
      ```
    - |
      ```
      too big
      too small
      just right
      ```
    - nothing gets printed
  correct: "4"

---

# Conditions Quiz

{% include quiz.html questions=page.questions %}



