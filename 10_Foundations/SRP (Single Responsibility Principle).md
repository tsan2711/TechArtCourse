---
type: concept
status: stub
priority: core
prerequisites: []
next:
  - ISP (Interface Segregation Principle)
  - DIP (Dependency Inversion Principle)
---

# SRP (Single Responsibility Principle)

## One-liner
A module should have **one reason to change**.

## In Unity
- Prefer splitting a “god” `PlayerController` into focused components (Input, Movement, Audio, UI).

## Pitfalls
- Splitting too far can create coupling through shared state; group by cohesive change reasons.

## Related
- [[OCP (Open-Closed Principle)]]
- [[Dependency Injection]]

