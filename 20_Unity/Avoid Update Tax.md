---
type: unity
status: stub
---

# Avoid Update Tax

## One-liner
Avoid per-frame polling when you don’t need it; empty `Update()` still has overhead.

## Alternatives
- Events / callbacks
- Timers (`InvokeRepeating`)
- Coroutines / async (prefer UniTask when appropriate)

## Related
- [[Event-Driven Architecture]]
- [[UniTask Notes]]

