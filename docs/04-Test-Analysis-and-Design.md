# Chapter 4: Test Analysis and Design

## What is Test Analysis and Design?

Test analysis and design involve identifying what needs to be tested and creating effective test cases. The goal is to achieve good test coverage while using the minimum number of test cases.

Test cases should be clear, reusable, and capable of detecting defects.

---

## Black-Box Testing

Black-box testing focuses on the software's functionality without considering its internal code or structure. Test cases are created using requirements, specifications, or user expectations.

Common black-box techniques include:

- Equivalence Partitioning
- Boundary Value Analysis
- Decision Table Testing
- State Transition Testing

---

## White-Box Testing

White-box testing examines the internal structure and logic of the software. It focuses on code execution and ensures different parts of the program are tested.

Common white-box techniques include:

- Statement Testing
- Branch Testing

---

## Experience-Based Testing

Experience-based testing relies on the tester's knowledge, intuition, and previous experience to identify defects.

Common techniques include:

- Error Guessing
- Exploratory Testing
- Checklist-Based Testing

---

## Equivalence Partitioning (EP)

This technique divides input data into groups (partitions) where all values are expected to behave similarly. Instead of testing every possible value, one representative value from each partition is tested.

**Example**

Age must be between **18 and 60**.

Test values:
- 15 (invalid)
- 25 (valid)
- 70 (invalid)

---

## Boundary Value Analysis (BVA)

Defects often occur at the boundaries of input ranges. Boundary Value Analysis focuses on testing values at, just below, and just above these limits.

**Example**

Age range: **18–60**

Test values:
- 17
- 18
- 19
- 59
- 60
- 61

---

## Decision Table Testing

Decision tables are useful when software behaviour depends on multiple conditions.

Each combination of conditions is tested to ensure the correct action is performed.

**Example**

Login requires:
- Correct username
- Correct password

Different combinations produce different outcomes.

---

## State Transition Testing

State transition testing verifies how software behaves when moving between different states.

It is useful for systems such as:

- Login systems
- ATM machines
- Online shopping carts

**Example**

Too many incorrect login attempts may lock an account.

---

## Statement Testing

Statement testing measures whether every executable statement in the code has been executed at least once.

Higher statement coverage generally increases confidence but does not guarantee all defects are found.

---

## Branch Testing

Branch testing verifies that every possible decision outcome (such as True and False) has been executed.

It provides better coverage than statement testing because it tests different execution paths.

---

## Error Guessing

Error guessing relies on the tester's experience to predict where defects are likely to occur.

Examples include:

- Empty input fields
- Special characters
- Very large numbers
- Invalid dates
- Incorrect file formats

---

## Exploratory Testing

Exploratory testing combines learning, designing, and executing tests at the same time.

Rather than following predefined test cases, the tester explores the application to discover unexpected defects.

---

## Checklist-Based Testing

Checklist-based testing uses a predefined list of items that should be verified during testing.

This helps ensure consistency and reduces the chance of missing important checks.

---

# Chapter Summary

- Test analysis identifies what should be tested, while test design creates effective test cases.
- Black-box testing focuses on functionality, whereas white-box testing focuses on internal code.
- Experience-based testing relies on the tester's knowledge and intuition.
- Equivalence Partitioning reduces the number of test cases by grouping similar inputs.
- Boundary Value Analysis focuses on values where defects are most likely to occur.
- Decision Table Testing is useful when multiple conditions affect the outcome.
- State Transition Testing verifies behaviour as the software changes state.
- Statement and Branch Testing measure code coverage.
- Error Guessing, Exploratory Testing, and Checklist-Based Testing use practical experience to uncover defects.
