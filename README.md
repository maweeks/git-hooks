# Git Hooks

## commit-msg

- Check if `[TICKET_CODE]` or `[INIT]` or `[TECH]` is at the start of a commit.
- Check if multiple authors are present in commit if on master.

## Usage

To use, need to set the hooks directory:

```sh
git config core.hooksPath gitHooks
```

Instead the following to do it for all repos? Risky...

```sh
git config --global core.hooksPath gitHooks
```

Or if NPM, then can use the preinstall script in package json (or other similar system).

Or symlink / copy to .git/hooks dir
