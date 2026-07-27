# ISTQB Foundation Level Cheat Sheet

A quick revision guide covering the key concepts from the ISTQB CTFL syllabus.

---

# Testing Basics

### Software Testing
Evaluating software to verify it meets requirements and behaves as expected.

### Testing Objectives
- Find defects
- Prevent defects
- Verify requirements
- Validate user needs
- Build confidence
- Support release decisions

### Testing vs Debugging

| Testing | Debugging |
|---------|-----------|
| Finds defects | Finds and fixes defects |
| Usually done by testers | Usually done by developers |

### QA vs QC

| Quality Assurance (QA) | Quality Control (QC) |
|------------------------|----------------------|
| Prevents defects | Detects defects |
| Process-focused | Product-focused |

---

# Error → Defect → Failure

- **Error (Mistake):** Human mistake.
- **Defect (Bug):** Fault introduced into the software.
- **Failure:** Incorrect behaviour when the software runs.

Example:
Developer writes incorrect formula → Bug in code → Wrong total displayed to user.

---

# Seven Testing Principles

1. Testing shows the **presence** of defects, not their absence.
2. Exhaustive testing is impossible.
3. Test early.
4. Defects cluster together.
5. Tests wear out over time.
6. Testing depends on context.
7. Absence of errors does not mean the software is useful.

---

# SDLC Models

### Waterfall
- Sequential development
- Testing mainly after development

### Agile
- Iterative development
- Continuous testing

### DevOps
- Continuous development, testing, and deployment
- Heavy use of automation

---

# Shift-Left Testing

Start testing as early as possible to reduce defects and costs.

---

# Test Levels

| Level | Purpose |
|--------|----------|
| Unit | Test individual components |
| Integration | Test interactions between components |
| System | Test the complete system |
| Acceptance | Verify business/user requirements |

---

# Test Types

### Functional Testing
Checks **what** the software does.

### Non-Functional Testing
Checks **how well** it performs.

Examples:
- Performance
- Security
- Usability
- Reliability
- Compatibility

---

# Static vs Dynamic Testing

| Static Testing | Dynamic Testing |
|---------------|-----------------|
| No code execution | Executes software |
| Reviews documents/code | Runs the application |

---

# Review Types

- Informal Review
- Walkthrough
- Technical Review
- Inspection (most formal)

---

# Black-Box vs White-Box Testing

| Black-Box | White-Box |
|-----------|-----------|
| Tests functionality | Tests internal code |
| No code knowledge required | Requires code knowledge |

---

# Test Design Techniques

### Black-Box
- Equivalence Partitioning
- Boundary Value Analysis
- Decision Table Testing
- State Transition Testing

### White-Box
- Statement Testing
- Branch Testing

### Experience-Based
- Error Guessing
- Exploratory Testing
- Checklist-Based Testing

---

# Test Management

### Test Plan Includes
- Objectives
- Scope
- Resources
- Schedule
- Risks
- Entry criteria
- Exit criteria

### Risk-Based Testing
Focus testing on high-risk features first.

---

# Entry vs Exit Criteria

### Entry Criteria
Requirements before testing begins.

### Exit Criteria
Conditions that must be met before testing ends.

---

# Defect Lifecycle

1. Defect Found
2. Reported
3. Assigned
4. Fixed
5. Retested
6. Closed

---

# Test Metrics

- Test cases executed
- Pass/Fail rate
- Defects found
- Test coverage

---

# Test Tools

Used for:
- Test management
- Defect tracking
- Static analysis
- Test automation
- Performance testing

---

# Automation

### Benefits
- Faster execution
- Repeatable tests
- Better regression testing
- Saves time

### Limitations
- Initial setup cost
- Maintenance required
- Cannot replace human judgement

---

# Frequently Confused Terms

| Concept | Meaning |
|---------|---------|
| Verification | Are we building the product right? |
| Validation | Are we building the right product? |
| Confirmation Testing | Confirms a fixed defect is resolved |
| Regression Testing | Ensures changes haven't broken existing features |
| Static Testing | No execution of software |
| Dynamic Testing | Software is executed |

---

# Key Takeaways

- Testing finds defects but cannot prove software is bug-free.
- Test early to reduce costs.
- Exhaustive testing is impossible.
- Use different test levels and test types for complete coverage.
- Apply suitable test design techniques based on the situation.
- Prioritise testing based on risk.
- Automation supports testing but does not replace testers.
- Testing is a continuous activity throughout the SDLC.
