# GLOBAL RULES

## Enforcement
- These rules are mandatory and must not be violated
- Do not generate code that breaks any rule
- If a rule cannot be satisfied, request clarification instead of violating it

---

## Type Safety
- Always use TypeScript strict mode
- Avoid `any` unless absolutely necessary (must justify usage)
- Prefer explicit types over inference in public APIs
- Use type guards and proper validation for unknown data

---

## Code Style
- Use functional programming patterns where possible
- Avoid classes unless necessary
- Prefer pure functions with minimal side effects
- Keep functions small and focused

---

## Architecture
- Follow modular architecture
- Separate concerns (services, controllers, utils)
- Do not place business logic inside controllers
- Maintain clear boundaries between layers

---

## Naming
- Use clear, descriptive names
- Avoid abbreviations except standard ones (id, url)
- Names must reflect intent and usage

---

## Error Handling
- Always handle errors explicitly
- Do not swallow exceptions
- Provide meaningful error messages
- Fail safely and predictably
