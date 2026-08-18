## Archivist-First Codebase Navigation

Before broad repository exploration, architecture analysis, impact analysis, locating
implementations, or planning a multi-file change:

1. Delegate a focused question to the `archivist` subagent.
2. Use its response to identify the smallest relevant set of files.
3. Read source files directly only when necessary to complete the current task.
4. If the Archivist reports incomplete or stale records, allow it to inspect the
   relevant source and refresh its memory.
5. After substantial code changes are implemented and validated, give the Archivist
   the changed file list and ask it to refresh the affected records.
