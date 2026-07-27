# Chapter 2: Testing Throughout the Software Development Lifecycle (SDLC)

## What is the SDLC?

The Software Development Life Cycle (SDLC) is the process used to plan, develop, test, deploy, and maintain software. Testing is not a separate activity at the end—it should be performed throughout the SDLC to identify defects early and reduce development costs.

---

## Testing in Different SDLC Models

### Waterfall

Waterfall follows a sequential approach where each phase is completed before moving to the next.

**Testing in Waterfall:**
- Mostly performed after development is complete.
- Defects are often found late.
- Best suited for projects with stable requirements.

### Agile

Agile develops software in small, frequent iterations (sprints).

**Testing in Agile:**
- Testing happens continuously.
- Testers work closely with developers and stakeholders.
- Frequent feedback helps identify defects early.

### DevOps

DevOps combines development and operations to deliver software faster and more reliably.

**Testing in DevOps:**
- Strong emphasis on automation.
- Continuous Integration (CI) and Continuous Delivery (CD) allow frequent testing and deployment.
- Testing becomes part of the development pipeline.

---

## Shift-Left Testing

Shift-left testing means starting testing activities as early as possible in the SDLC instead of waiting until development is complete.

**Benefits:**
- Finds defects earlier.
- Reduces the cost of fixing bugs.
- Improves software quality.
- Reduces project delays.

---

## Test Levels

Different test levels focus on different parts of the software.

### Unit Testing
- Tests individual components or functions.
- Usually performed by developers.

### Integration Testing
- Verifies that different modules work correctly together.

### System Testing
- Tests the complete application against specified requirements.

### Acceptance Testing
- Confirms the software meets business and user needs before release.
- Often performed by customers or end users.

---

## Test Types

Different test types evaluate different aspects of the software.

### Functional Testing
Checks whether the software performs the required functions.

### Non-Functional Testing
Evaluates attributes such as:
- Performance
- Security
- Usability
- Reliability
- Compatibility

### Black-Box Testing
Tests software based on inputs and expected outputs without looking at the code.

### White-Box Testing
Tests the internal logic and code structure.

---

## Confirmation vs Regression Testing

### Confirmation Testing
- Performed after a defect has been fixed.
- Confirms the original issue is resolved.

### Regression Testing
- Ensures recent changes have not introduced new defects.
- Existing functionality should continue to work as expected.

---

## Maintenance Testing

Maintenance testing is performed after software has been deployed.

It is required when:
- Bugs are fixed.
- New features are added.
- The software environment changes.
- Performance improvements are made.

Its main goal is to verify that updates have not negatively affected existing functionality.

---

# Chapter Summary

- Testing should occur throughout the SDLC, not only after development.
- Waterfall performs testing later, while Agile and DevOps encourage continuous testing.
- Shift-left testing helps detect defects earlier and reduces costs.
- The four main test levels are Unit, Integration, System, and Acceptance Testing.
- Functional testing checks what the software does, while non-functional testing checks how well it performs.
- Confirmation testing verifies bug fixes, whereas regression testing ensures new changes haven't broken existing functionality.
- Maintenance testing validates software after updates or environmental changes.
