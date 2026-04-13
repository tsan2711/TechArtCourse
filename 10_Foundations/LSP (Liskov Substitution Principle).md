---
type: concept
status: stub
priority: recommended
prerequisites:
  - ISP (Interface Segregation Principle)
next: []
---

# LSP (Liskov Substitution Principle)

## One-liner
Subtypes must be substitutable for their base types without breaking expectations.

## In Unity
- If `IEnemy` promises “can move”, don’t implement a turret that throws or no-ops silently—split interfaces.

## Related
- [[ISP (Interface Segregation Principle)]]

