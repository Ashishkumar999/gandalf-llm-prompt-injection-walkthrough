# Testing Methodology

This document explains how Gandalf AI levels were solved step by step.

Each level introduced a stronger guardrail.

The strategy used:

Step 1: Observe defender message
Step 2: Identify filtering behavior
Step 3: Try direct extraction
Step 4: Try transformation techniques
Step 5: Try segmentation attacks
Step 6: Try context recall
Step 7: Try semantic chaining

This structured approach helps simulate real AI security testing workflows.

---

## Example Attack Flow

User Prompt
→ Guardrail Filter
→ Intent Detection
→ Output Validation
→ Secret Leakage (if bypass successful)

---

## Security Category

OWASP LLM01 – Prompt Injection
