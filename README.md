# nuntio-e2e-fixture

A scratch repository for Nuntio's end-to-end tests.

**Automated tests write to this repository.** They create branches, commit files,
open and merge pull requests, and revert commits. Do not put anything here you
care about, and do not use it as an example of a real site.

`main` is the baseline the tests expect. If a test run leaves debris behind,
reset with:

```bash
git checkout main && git reset --hard <baseline-sha>
```

## Layout

```text
content/blog/    MDX blog posts
content/docs/    MDX documentation pages
```
