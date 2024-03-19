---
layout: default
---



# Loops Quiz

1. LEVEL: BASIC. The task was to write a function which traverses a sequence of integers and returns the index of the first occurrence of element with value equal to the value of ``a``. If such element is not found, the function should return -1. Consider the following attempts to solve this task. Which attempt will produce the desired output? Bonus question: which build-in list method can be used instead? 

    If you have doubts as if why something is wrong (or not), make a test case add a print statement in each iteration and execute the code. Or visualize the code execution in [Python Tutor](https://pythontutor.com/visualize.html#mode=edit). For example [like this](https://pythontutor.com/render.html#code=def%20find_pattern%28sequence%29%3A%0A%20%20%20%20for%20s%20in%20sequence%3A%0A%20%20%20%20%20%20%20%20if%20s%20%3D%3D%20a%3A%0A%20%20%20%20%20%20%20%20%20%20%20%20return%20s%0A%20%20%20%20%20%20%20%20else%3A%0A%20%20%20%20%20%20%20%20%20%20%20%20return%20-1%0A%20%20%20%20%20%20%20%20%20%20%20%20%0Asequence%20%3D%20%5B3,%206,%208,%202,%205,%207%5D%0Aa%20%3D%205%0Aprint%28find_pattern%28sequence%29%29&cumulative=false&curInstr=0&heapPrimitives=nevernest&mode=display&origin=opt-frontend.js&py=3&rawInputLstJSON=%5B%5D&textReferences=false).



    ``` python
    def find_pattern(sequence):
        for s in sequence:
            if s == a:
                return s
            else:
                return -1
    ```

    ``` python
    def find_pattern(sequence):
        for s in sequence:
            if s == a:
                return s
            return -1
    ```

    ``` python
    def find_pattern(sequence):
        for s in sequence:
            if s == a:
                return s
        return -1
    ```

    ``` python
    def find_pattern(sequence):
        for i in range(len(sequence)):
            if sequence[i] == a:
                return i
            else
                return -1
    ```

    ``` python
    def find_pattern(sequence):
        for i in range(len(sequence)):
            if sequence[i] == a:
                return i
            return -1
    ```

    ``` python
    def find_pattern(sequence):
        for i in range(len(sequence)):
            if sequence[i] == a:
                return i
        return -1
    ```

