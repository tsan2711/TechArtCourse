---
type: concept
status: stub
priority: core
prerequisites:
  - SRP (Single Responsibility Principle)
next:
  - DIP (Dependency Inversion Principle)
---

# ISP (Interface Segregation Principle)

## One-liner
Clients should not be forced to depend on methods they do not use.

## In Unity
- Split “Interactable” capabilities: `IPickup`, `ITalk`, `IOpen`, etc.

## Related
- [[LSP (Liskov Substitution Principle)]]
- [[DIP (Dependency Inversion Principle)]]

