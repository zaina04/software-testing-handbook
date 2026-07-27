# Chapter 3: Static Testing

## What is Static Testing?

Static testing is the process of evaluating software work products without executing the code. Instead of running the software, testers review documents, requirements, designs, or source code to identify defects early.

The main goal of static testing is to prevent defects before they become part of the software.

---

## Static Testing vs Dynamic Testing

| Static Testing | Dynamic Testing |
|---------------|-----------------|
| Does not execute the software | Executes the software |
| Finds defects early | Finds failures during execution |
| Reviews documents, designs and code | Tests the running application |
| Usually less expensive | Usually more expensive if defects are found late |

---

## Benefits of Static Testing

Static testing helps to:

- Detect defects early
- Reduce development costs
- Improve software quality
- Improve documentation
- Increase communication between team members
- Reduce the number of defects found during dynamic testing

---

## Review Process

A review is a structured examination of a work product to identify issues and suggest improvements.

A typical review consists of:

1. Planning
2. Review preparation
3. Review meeting
4. Rework (fixing identified issues)
5. Follow-up to ensure issues have been addressed

---

## Types of Reviews

### Informal Review
- No formal process
- Quick and flexible
- Often performed by peers

### Walkthrough
- Led by the author
- Used to explain the work product and gather feedback

### Technical Review
- Conducted by technical experts
- Focuses on technical correctness and quality

### Inspection
- The most formal type of review
- Follows a structured process with defined roles
- Aims to identify as many defects as possible

---

## Review Roles

Common roles include:

- **Author** – Creates the work product.
- **Reviewer** – Examines the work and identifies defects.
- **Moderator** – Organises and manages the review process.
- **Scribe** – Records defects and review outcomes.
- **Manager** – Supports the review process and acts on results.

---

## Success Factors for Reviews

Reviews are most effective when:

- Objectives are clearly defined.
- Participants are prepared.
- The right people are involved.
- Reviews focus on improving the product, not blaming individuals.
- Feedback is constructive.

---

## Static Analysis

Static analysis uses tools to examine source code without executing it.

These tools can identify issues such as:

- Coding standard violations
- Unused variables
- Dead or unreachable code
- Potential security vulnerabilities
- Memory leaks
- Complex or duplicated code

Static analysis complements reviews by automatically detecting problems that may be difficult to find manually.

---

# Chapter Summary

- Static testing evaluates documents and code without running the software.
- It helps identify defects early, reducing the cost of fixing them.
- Reviews improve quality through human examination of work products.
- The main review types are Informal Reviews, Walkthroughs, Technical Reviews, and Inspections.
- Static analysis tools automatically inspect source code for potential issues.
- Static testing and dynamic testing complement each other and should both be part of the software testing process.
