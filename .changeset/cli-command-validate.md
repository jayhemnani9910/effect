---
"effect": patch
---

Add `Command.validate` for checks that span several flags or arguments, such as mutually exclusive flags. It receives the parsed input before the handler runs; a failure is reported with the command help, like a parse error.
