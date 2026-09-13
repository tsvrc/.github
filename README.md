# .github

Organization-wide default community health files for the `tsvrc` org. GitHub falls back to
whatever's here (`CODE_OF_CONDUCT.md`, `SUPPORT.md`, `.github/PULL_REQUEST_TEMPLATE.md`,
issue templates) for any repo in the org that doesn't define its own copy. `profile/README.md`
is the org's public profile page, shown at https://github.com/tsvrc.

Repo-specific files (`CONTRIBUTING.md`, `LICENSE`, `SECURITY.md`, repo-specific issue forms)
live in each repo instead, since those genuinely differ per project. See
[docs.github.com](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
for how the fallback works.

`GOVERNANCE.md` and `TRADEMARK.md` live here too, not because GitHub falls back to them
automatically (it doesn't, they're not part of the community-health mechanism above), but
because neither one differs per repo, so one copy here avoids two drifting out of sync.
Both `tsvrc-core` and `docs` link to them from their own READMEs.
