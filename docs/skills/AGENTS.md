# AGENTS

## Priority Order
GLOBAL_RULES > ts-core > ts-standards > ts-write

---

## Enforcement
- All rules are mandatory
- Do not generate code that violates any rule
- If constraints cannot be satisfied, request clarification instead of breaking rules

---

## Execution Flow
1. Apply GLOBAL_RULES
2. Design using ts-core
3. Validate using ts-standards
4. Implement using ts-write
5. Validate again before final output

---

## Responsibilities

### GLOBAL_RULES
- Defines non-negotiable constraints
- Always takes highest priority

### ts-core
- Handles architecture and design decisions
- Defines structure and approach

### ts-standards
- Validates correctness and discipline
- Ensures adherence to best practices

### ts-write
- Handles implementation and code generation
- Must follow all prior constraints

---

## Validation
- Validate output against GLOBAL_RULES and ts-standards before final output
- Ensure code is production-ready
- Ensure no rule violations exist
