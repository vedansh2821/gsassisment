# gsassisment

Assessment work (January 2025): question papers and solved programming exercises.

## Contents

Question papers (`.docx`):

- `API Assignment Questions.docx`
- `GIT Assignment Questions.docx`
- `Gen AI Assignment Questions.docx`
- `Oracle SQL Assignment Questions.docx`
- `QA Processes Assignment Questions.docx`
- `UFT Assignment Questions.docx`

Solved exercises:

- `JavaAssignment.java` — ten console exercises in one file, all using only `java.util.Scanner`: total marks/percentage, simple & compound interest, circle area/circumference, Celsius-to-Fahrenheit conversion, swapping two values, equality check, greatest of three numbers, even/odd check, leap-year check, and grade calculation. Only `calculateMarks()` is called from `main()`; the rest are present but commented out there.
- `pythonassignment.py` — standard-library-only Python exercises: file analysis (lines/words/characters), Fibonacci primes up to N, second-largest number in a list, and an anagram check. Note it prompts for a number at the top level when run.

## Running

```bash
javac JavaAssignment.java && java JavaAssignment
python3 pythonassignment.py
```

No third-party dependencies: the Java file uses only the standard library and the Python file uses only `re`, so there is no `requirements.txt`.
