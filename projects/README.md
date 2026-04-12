# Projects

Each initiative gets its own subfolder here. Use lowercase-hyphenated slugs for folder and file names.

```
projects/
  [initiative-slug]/
    [initiative-slug]-1pager.md
    [initiative-slug]-prd.md          (added when ready)
    [initiative-slug]-test-plan-01.md (added when a test plan is created)
    competitive-analysis.md           (added when competitive analyst runs)
    source-docs/                      (the PM moves source files here)
    prototype/
      index.html                      (added when a prototype is built)
```

Project subdirectories are gitignored by default. If you want to track your initiatives in version control, remove the `projects/*/` line from `.gitignore`.
