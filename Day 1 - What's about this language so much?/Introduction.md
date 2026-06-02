## 1. print()
Sends data to your screen.

* Hidden trick: It adds a invisible newline \n at the end by default.
* Custom fix: Change it using end="" or change spaces using sep="-".

## 2. Variables
They are not boxes holding data.

* Reality: They are string labels or arrows pointing to data in memory.
* Proof: If a = [1] and b = a, both arrows point to the exact same list.

## 3. input()
Freezes your code until the user hits Enter.

* The Catch: It converts everything into text (a string).
* Fix: You must wrap it in int() or float() to do math.

## 4. Data Types

* int: Whole numbers. No size limit.
* float: Decimals. Warning: 0.1 + 0.2 equals 0.30000000000000004 due to computer binary math.
* str: Text. Unchangeable (immutable) in memory once made.
* bool: True (equals 1) or False (equals 0).


