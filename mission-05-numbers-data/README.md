# Mission 5 — Numbers and data

> **Student:** Nikhil Aryan | **USN:** 2392608447 | **Campus:** Bengaluru

## 1. Task / objective
Convert decimal, binary, and hexadecimal values by hand, verify the calculations using Python, build an interactive number converter program (`number_converter.py`), and explain text encoding principles (ASCII and UTF-8).

## 2. Work completed
* Solved 7 number conversions by hand with complete mathematical steps (repeated division for decimal-to-binary, positional expansion for binary/hex-to-decimal, and 4-bit grouping).
* Verified each conversion interactively in Python using `bin()`, `int()`, and `hex()`.
* Built and tested `number_converter.py`, which prompts for a decimal number and outputs its binary and hexadecimal equivalents.
* Tested the program with three positive numbers (10, 42, 255) and documented function behavior.
* Answered questions on ASCII codes for 'A' and 'a', the purpose of text encoding standards, and non-ASCII character examples.

## 3. Commands / tools used
* `python3 number_converter.py`: Ran the interactive converter program.
* Python interactive shell (`python3`): Verified conversions using `bin()`, `hex()`, and `int()`.
* Python built-in functions:
  * `input()`: Accepts decimal number input from the user as a string.
  * `int()`: Parses string input into an integer.
  * `bin()`: Converts integer to binary string prefixed with `0b`.
  * `hex()`: Converts integer to hexadecimal string prefixed with `0x`.

## 4. My understanding
All digital data is ultimately stored and manipulated as bits (0 and 1). Number systems like binary (base 2) and hexadecimal (base 16) provide compact, mathematically aligned representations of underlying machine bytes. Character encodings like ASCII and UTF-8 map these numeric values into human-readable symbols, enabling cross-platform text storage and communication.

## 5. Difficulties faced
No major difficulties.

## 6. How I resolved them
Not applicable.

## 7. Evidence / files
* `mission-05-numbers-data/number_converter.py`
* `mission-05-numbers-data/notes.md` (Contains manual conversion steps, Python verifications, test results table, and text encoding analysis)
* `mission-05-numbers-data/README.md`

## 8. Commit details
* **Commit message:** `Build number converter and practise data representation`
* Pushed to remote: `https://github.com/nikhilaryan6115-design/digital-detective-8447`
