---
"@covector/apply": minor
"@covector/files": minor
---

Bump version requirements for member crates declared in a cargo workspace root manifest's `[workspace.dependencies]` table. Requirements keep their form (partial pins stay partial, range prefixes are preserved), while path-only entries and `*` requirements float on the workspace and are left untouched.
