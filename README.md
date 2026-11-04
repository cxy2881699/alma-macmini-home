# Agent Memory

User-owned memory repository written by Agent Memory Hub.

- `events/<agent@device>/<session>/` raw conversation turns (never rewritten)
- `memories/` current memories; `revisions/` every version of every memory
- `entities/` people, projects, modules and tools that memories are about (graph nodes)
- `episodes/` processes over several turns: goal, ordered steps, outcome
- `relations/` subject —predicate→ object between entities, with validity dates
- `commits/` cognitive commits; `deprecations/` deprecated sources

Commit authors are `agent@device`, so `git log --author=claude-code@macmini` shows what that agent changed.
Do not store API keys or tokens here.
