---
type: concept
status: stub
---

# Dependency Injection

## One-liner
Provide dependencies from the outside (constructor / initializer) instead of creating or finding them inside.

## In Unity
- Prefer `Initialize(...)` wiring, serialized references, or a DI container (VContainer/Zenject).
- Avoid `FindObjectOfType` for gameplay dependencies.

## Related
- [[DIP (Dependency Inversion Principle)]]
- [[Event-Driven Architecture]]

