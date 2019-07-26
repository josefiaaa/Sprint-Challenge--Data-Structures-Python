Add your answers to the questions below.

1. What is the runtime complexity of your ring buffer's `append` method?
    The runtime complexity is O(1).

2. What is the space complexity of your ring buffer's `append` function?
    The space complexity O(1).

3. What is the runtime complexity of your ring buffer's `get` method?
    A loop going through a list one time is O(n).

4. What is the space complexity of your ring buffer's `get` method?
    O(1) - created a single variable.

5. What is the runtime complexity of the provided code in `names.py`?
    The provided code's runtime would be O(n^2). For every name in the `names_1.txt` file, it is looping though the `names_2.txt` file to match duplicates.

6. What is the space complexity of the provided code in `names.py`?
    Since there were only 3 variables, the space complexity should be O(1).

7. What is the runtime complexity of your optimized code in `names.py`?
    O(n) - I filled a dictionary with `name_2` values and ran a different loop to check if any values in `names_1` exist in `names_2`.

8. What is the space complexity of your optimized code in `names.py`?
    Since there are only 4 variables, the space complexity is O(1).
