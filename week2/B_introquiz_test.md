---
layout: default

questions:
- text: |
    How many lines are printed out by the code below?
    ```python
    for i in range(5):
        print('Hej')
    print('med dig')
    ```
  choices: 
  - 5
  - 4
  - 10
  - 8
  - 6
  correct: "4"

- text: | 
    What is printed out by the code below?
    ```python
    for i in range(10):
        print(i, end=', ')
    print('and', i)
    ```
  choices: 
  - 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, and 10
  - 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, and 0
  - 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, and 9
  - 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, and -1
  correct: "2"


- text: I want to crate a string `greeting` with the value `'I am Vedrana from Croatia'` but with the values of the variables `name` and `country` inserted in the indicated place. Which of the following code snippets will do that?
  choices: 
  - |
    `greeting = print('I am ', name, ' from ', country`)
  - |
    `greeting = print('I am', name, 'from', country`)
  - |
    `greeting = 'I am ', name, ' from ', country`
  - |
    `greeting = 'I am', name, 'from', country`
  - |
    `greeting = 'I am ' + name + ' from ' + country`
  - |
    `greeting = f'I am {name} from {country} .'`
  - |
    `greeting = 'I am %s from %s' % (name, country)`

  correct: "0000111"

---

# This is to test the quiz functionality


{% include quiz.html questions=page.questions %}


