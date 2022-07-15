# Git Precommit Hook

Actually a `commit-msg` hook... :D

Check if `[TICKET_CODE]` or `[INIT]` or `[TECH]` is at the start of a commit.

Check if multiple authors are present in commit if on master.

To use, need to set the hooks directory:

```sh
git config core.hooksPath gitHooks
```

Instead the following to do it for all repos? Risky...

```sh
git config --global core.hooksPath gitHooks
```

Or if NPM, then can use the preinstall script in package json (or other similar system).
