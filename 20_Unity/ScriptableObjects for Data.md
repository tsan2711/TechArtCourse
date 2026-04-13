---
type: unity
status: stub
---

# ScriptableObjects for Data

## One-liner
Use ScriptableObjects to store **tweakable data** (stats, configs) outside of code.

## Benefits
- Designer-friendly tuning
- Less hardcoding / fewer merge conflicts

## Pitfalls
- Be careful with runtime mutation (asset vs instance). Prefer immutable “config” assets.

## Related
- [[Dependency Injection]]

