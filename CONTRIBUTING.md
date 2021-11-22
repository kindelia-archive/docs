# Kindelia Contributing Guide

Thank you for considering contributing to Kindelia. This document will outline
how to submit changes to the project and which conventions to follow. If you are
ever in doubt about anything we encourage you to reach out through any of the
following channels:

- Discord (TODO)
- [t.me/quleuber](https://t.me/quleuber)

The next section lists the main repositories that compose the project, and their
respective specific contributing guides.

## Repos

* [Ubilog](https://github.com/Kindelia/ubilog)
  * The consensus layer that Kindelia build upon.
  * [CONTRIBUTING.md on github.com/Kindelia/ubilog](https://github.com/Kindelia/ubilog/blob/master/CONTRIBUTING.md)

* [Kindelia](https://github.com/Kindelia/kindelia) itself
  * [CONTRIBUTING.md on github.com/Kindelia/kindelia](https://github.com/Kindelia/kindelia/blob/master/CONTRIBUTING.md)

<!--
## Prerequisites

* You're familiar with GitHub Issues and Pull Requests.
-->

## Issues before PRs

Before you start working on a change please make sure that there is an issue for
what you will be working on. You can either find and existing issue or open a
new issue if none exists. Doing this makes sure that others can contribute with
thoughts or suggest alternatives, ultimately making sure that we only add
changes that make.

## Commits

Strive towards keeping your commits small and isolated - this helps the reviewer
understand what is going on and makes it easier to process your requests. It is
recommended to keep your changes grouped logically within individual commits.

## Rebase

Once you have committed your changes, it is a good idea to use `git rebase` (not
`git merge`) to synchronize your work with the main repository.

```
$ git fetch upstream
$ git rebase upstream/master
```

## Pull requests

Once your changes are ready you must submit your branch as a pull request.

Please include in your PR the following information:

## Merge Style

All pull requests are squashed and merged.

---

<small>
Inspired by:

* https://github.com/electron/electron/blob/main/CONTRIBUTING.md
* https://github.com/medusajs/medusa/blob/master/CONTRIBUTING.md
</small>
