# Factorial Program

A simple beginner Python program that calculates the factorial of the fixed value `5` using a loop.

## Program

The repository contains:

- `factorial.py` — calculates the factorial of 5.
- `Audit.md` — fact-check audit validating all README claims against the implementation.

## How It Works

The variable `fact` starts at `1`.

A `for` loop runs from 1 through 5 and repeatedly multiplies the current value of `fact`:

```python
n = 5
fact = 1
for i in range(1, n + 1):
    fact = fact * i
print("Factorial is: ", fact)
```

## Requirements

- Python 3.x

No external libraries are required.

## Usage

Run:

```bash
python factorial.py
```

## Output

```text
Factorial is:  120
```

## Example Calculation

5 × 4 × 3 × 2 × 1 = 120

## Fact-Check & Verification

This project includes a comprehensive [Audit.md](Audit.md) ensuring that all documentation claims accurately match the underlying code.

## Repository Information

- **Owner:** [khushigsd2924-design](https://github.com/khushigsd2924-design)
- **Repository:** [python-basics-factorial](https://github.com/khushigsd2924-design/python-basics-factorial)
