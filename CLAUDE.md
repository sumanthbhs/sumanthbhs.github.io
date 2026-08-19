# Working on this repository

## Git commit identity — required, no exceptions

Every commit pushed to this repository must be authored and committed as:

```
Sumanth Bharadwaj H S <sumanthbhs@gmail.com>
```

Before making any commit, explicitly set it for this repo (do not rely on whatever identity
the environment defaults to — verify it):

```bash
git config user.name "Sumanth Bharadwaj H S"
git config user.email "sumanthbhs@gmail.com"
```

Do not include `Co-Authored-By:` trailers, session links, or any other attribution to Claude,
Anthropic, or any AI tool in commit messages. The repository owner is the sole author and sole
publisher of record for everything in this repository.

This rule exists because an earlier session let the environment's preset git identity
(`Claude <noreply@anthropic.com>`) silently author every commit, which put "Claude" in the
repository's contributor history. That was corrected via a full history rewrite
(`git filter-branch`) and a force-push on 2026-08-19. Do not let it happen again — check
`git config user.name` / `git config user.email` before the first commit of any session.
