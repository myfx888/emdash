---
"emdash": patch
---

Fixes `emdash doctor` always reporting "could not query users table". The users check now queries the correct table and reports the actual user count.
