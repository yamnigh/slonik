---
"slonik-sql-tag-raw": major
"@slonik/sql-tag": major
"slonik": major
---

Convert token types to symbols to ensures that SQL tokens cannot be injected from outside of the codebase, e.g. through JSON.

Thanks to @alxndrsn for reporting the issue.

Thanks to @danielrearden for suggesting a viable patch.