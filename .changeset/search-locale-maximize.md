---
"blume": patch
---

Fix built-in search failing with "Something went wrong" in Chrome and other V8 browsers. `Intl.Locale#maximize()` throws in V8 for Orama's default tokenizer language `english`, and every query on a Latin-script index reached it.
