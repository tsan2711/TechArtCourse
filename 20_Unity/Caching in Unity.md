---
type: unity
status: stub
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

