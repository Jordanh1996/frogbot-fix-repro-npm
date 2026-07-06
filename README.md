# frogbot-fix-repro-npm

Minimal npm repo to verify Frogbot **fix PR** on tokyoshiftleft.

Seeded direct dependency: `minimatch@3.0.2` (fix versions available via remediation).

**Secrets:** `JF_URL`, `JF_ACCESS_TOKEN`, `JF_GIT_TOKEN` (PAT with `repo` scope — `GITHUB_TOKEN` cannot open fix PRs in Actions).

**Tenant:** `https://tokyoshiftleft.jfrog.io/`
