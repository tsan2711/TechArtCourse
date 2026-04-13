---
type: unity
status: stub
priority: core
prerequisites: []
next:
  - Caching in Unity
---

# Unity Lifecycle (Awake vs Start)

## One-liner
- Use `Awake` for **self-initialization**
- Use `Start` for **connecting to other objects**

## Rules of thumb
- Don’t assume other scene objects are ready in `Awake`.
- Cache references once (avoid `GetComponent` in `Update`).

## Related
- [[Caching in Unity]]

