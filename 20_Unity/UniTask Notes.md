---
type: unity
status: stub
---

# UniTask Notes

## One-liner
UniTask is an async/await library optimized for Unity with low allocations and better ergonomics than coroutines for many cases.

## Use for
- IO / loading
- Timed sequences that need cancellation

## Pitfalls
- Always wire cancellation (scene unload / object destroy) to avoid ghost tasks.

## Related
- [[Avoid Update Tax]]

