# Turborepo Monorepo Issue

Trying to reproduce an issue where turborepo fails to identify a monorepo, ie uses single package mode.

## Steps

```
git clone git@github.com:sambs/turbo-single-package-issue-repro.git
cd turbo-single-package-issue-repro
pnpm i
pnpm compile -vvv
```
