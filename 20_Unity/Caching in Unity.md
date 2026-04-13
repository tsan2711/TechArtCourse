---
type: unity
status: stub
priority: core
prerequisites:
  - Unity Lifecycle (Awake vs Start)
next:
  - Avoid Update Tax
---

# Caching in Unity

## One-liner
Cache expensive lookups (components, transforms, camera refs) instead of repeating them every frame.

## Common targets
- `GetComponent<T>()`
- `Camera.main`
- Object searches (`Find`, `FindObjectOfType`)

## Related
- [[Avoid Update Tax]]
- [[Unity Lifecycle (Awake vs Start)]]

