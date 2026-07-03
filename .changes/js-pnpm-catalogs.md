---
"@covector/apply": minor
"@covector/files": minor
---

Handle pnpm catalog dependencies: `catalog:` references in package.json are left untouched (pnpm rewrites them at publish; previously they were corrupted to a bare major version), and the `catalog:`/`catalogs:` tables in pnpm-workspace.yaml are bumped to track member versions with the same form-preserving rules as the cargo workspace root table.
