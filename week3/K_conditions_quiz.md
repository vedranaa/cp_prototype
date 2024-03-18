1. LEVEL: BASIC. Combining conditions.
    Consider following block of code:
    ``` python
    if a > 0:
        if b > 0:
            print('both numbers are positive')
    ```
    Which of the following blocks below can be used interchangeably with the block above?

    ``` python
    if (a > 0) or (b > 0):
        print('both numbers are positive')
    ```

    ``` python
    if (a > 0) and not (b <= 0):
        print('both numbers are positive')
    ```

    ``` python
    if not (a <= 0) or (b > 0)
        print('both numbers are positive')
    ```

    ``` python
    if not (a <= 0) and not (b <= 0):
        print('both numbers are positive')
    ```


Example where confusion is because if something then else gets executed
    
    ``` python
    if something:
        bla
    if something else:
        bla
    else
    ```

