---
layout: default

questions:
- text: The task was to write a function which traverses a sequence of integers and returns the index of the first occurrence of element with value equal to the value of `a`. If such element is not found, the function should return -1. Consider the following attempts to solve this task. Which attempt will produce the desired output?
  choices: 
  - |
    ``` python
    def find_pattern(sequence):
        for s in sequence:
            if s == a:
                return s
            else:
                return -1
    ```
  - |
    ``` python
    def find_pattern(sequence):
        for s in sequence:
            if s == a:
                return s
            return -1
    ```
  - |
    ``` python
    def find_pattern(sequence):
        for s in sequence:
            if s == a:
                return s
        return -1
    ```
  - |
    ``` python
    def find_pattern(sequence):
        for i in range(len(sequence)):
            if sequence[i] == a:
                return i
            else
                return -1
    ```
  - |
    ``` python
    def find_pattern(sequence):
        for i in range(len(sequence)):
            if sequence[i] == a:
                return i
            return -1
    ```
  - |
    ``` python
    def find_pattern(sequence):
        for i in range(len(sequence)):
            if sequence[i] == a:
                return i
        return -1
    ```
  correct: "5"

---

# Loops Quiz

{% include quiz.html questions=page.questions %}

Bonus question: which build-in list method can be used instead? 

If you have doubts as if why something is wrong (or not), make a test case add a print statement for every iteration and every branch and execute the code. For example, to test the first attempt, you can use the following code:

``` python
def find_pattern(sequence):
    for s in sequence:
        print(f'Entered iteration with s = {s}')
        if s == a:
            print('Entered if branch')
            return s
        else:
            print('Entered else branch')
            return -1

sequence = [3, 6, 8, 2, 5, 7]
a = 5
print(find_pattern(sequence))
```

After executing the code with print statements, you will see that the the loop only enters the first iteration with value of `s` being 3, where it enters the else branch (because `s` is not equal to 5) and returns -1. Since both branches of if statement contain the return statement, the function will return something in the first iteration and the loop will never continue to the next iteration. This is not the desired behavior, because the function should return -1 only if the element with value equal to `a` is not found in the sequence.


You may also find it usefull to visualize the code execution in [Python Tutor](https://pythontutor.com/visualize.html#mode=edit). For example [like this](https://pythontutor.com/render.html#code=def%20find_pattern%28sequence%29%3A%0A%20%20%20%20for%20s%20in%20sequence%3A%0A%20%20%20%20%20%20%20%20if%20s%20%3D%3D%20a%3A%0A%20%20%20%20%20%20%20%20%20%20%20%20return%20s%0A%20%20%20%20%20%20%20%20else%3A%0A%20%20%20%20%20%20%20%20%20%20%20%20return%20-1%0A%20%20%20%20%20%20%20%20%20%20%20%20%0Asequence%20%3D%20%5B3,%206,%208,%202,%205,%207%5D%0Aa%20%3D%205%0Aprint%28find_pattern%28sequence%29%29&cumulative=false&curInstr=0&heapPrimitives=nevernest&mode=display&origin=opt-frontend.js&py=3&rawInputLstJSON=%5B%5D&textReferences=false).


