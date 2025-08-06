# Contribution Guide

I'm really excited that you're interested in contributing. This is a general contribution guide for most of my projects. Before submitting your contribution, please make sure to take a moment and read through the following guide:

## 👨‍💻 Repository Setup

I use [`npm`](https://npmjs.com) for most of the projects, and maybe a few with [`pnpm`](https://pnpm.io/), which I prefer. 

## Sending Pull Requests

### Discuss First

Before you start work on a pull request, open a feature request issue first to discuss with me and/or other maintainers. This does two things:

1. Tells you if we want the feature BEFORE you've spent time on it.
2. If we want it, it allows us to discuss feature design 

For typo fixes, if you have more than one, please batch them so the commit history is cleaner.

### Commit Convention

I try to use [Conventional Commits](https://www.conventionalcommits.org/) for commit messages, which allows the changelog to be auto-generated based on the commits. Please read the guide through if you aren't familiar with it already.

Only `fix:` and `feat:` will be presented in the changelog.

Note that `fix:` and `feat:` are for **actual code changes** (that might affect logic).
For typo or document changes, use `docs:` or `chore:` instead:

- ~~`fix: typo`~~ -> `docs: fix typo`

### Pull Request

If you don't know how to send a Pull Request, I recommend reading [the guide](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

When sending a pull request, make sure your PR's title also follows the [Commit Convention](#commit-conventions).

If your PR fixes or resolves an existing issue, please add the following line in your PR description (replace `123` with a real issue number):

```markdown
<!-- resolving one issue -->
fixes #123

<!-- resolving multiple issues -->
fixes #1, fixes #5, fixes #893
```

This lets GitHub know the issues are linked, and will automatically close them when the PR is merged. Learn more at [the guide](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword).

It's ok to have multiple commits in a single PR! You don't need to rebase or force push, as I/we will usually use `Squash and Merge` to squash the commits into one when merging.

### Other

If you have a question that isn't covered by this guide, please reach out to [Michael Monaghan](mailto:michael@monaghan.nyc) with your questions. 