# Profile development

This repository supplies the public GitHub profile for [bbrhm](https://github.com/bbrhm). `README.md` is the profile itself; [AGENTS.md](../AGENTS.md) records the owner's plain, modest style. Keep development documentation here so it does not appear in the profile.

## Codex cloud

Connect `bbrhm/bbrhm` and select the task branch. No setup script, maintenance script, package installation, runtime pin, environment variables or secrets are needed. Routine Markdown editing does not need agent internet access. The repository works without sibling checkouts or earlier chat history.

Edit `README.md`, run `git diff --check`, and inspect the diff and rendered Markdown if preview is available. Verify that project names, links and alpha access descriptions remain accurate. There is no automated test suite or deployment workflow for this Markdown-only repository. Do not report checks that were not run.

The current public projects are Arabic Reader Toolkit (invite-only alpha) and Open Map Driver (public alpha). Their public URLs are in the README. Their application source is private; do not add private source links or operational details to the profile.

The website and articles belong to the separate [bbrhm/bbrhm.github.io](https://github.com/bbrhm/bbrhm.github.io) repository. Its `src/_data/projects.json` records the website's project listing. If a change needs both repos, update each when available and in scope; otherwise report the remaining companion edit.

Return a branch/diff or pull request as requested. A change to `README.md` on `main` updates the public GitHub profile; there is no build or Firebase deployment step.

Example task: “Update the Open Map Driver description using these facts, keep the current low-key wording and layout, and prepare a PR. Flag any matching website edit.”
