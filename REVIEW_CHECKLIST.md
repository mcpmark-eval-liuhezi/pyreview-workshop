# REVIEW_CHECKLIST.md

A short checklist for reviewing Python pull requests, grounded in the official
GitHub documentation and the official Python documentation.

## Understanding the PR

- [ ] Read the PR description and any linked issue(s) or discussion(s).
- [ ] Confirm you understand the motivation behind the pull request.
- [ ] Check how this PR fits within linked projects or milestones.

## Reviewing the changes

- [ ] Review changes one file at a time.
- [ ] Examine each individual file changed in the pull request.
- [ ] Leave comments on specific changes.
- [ ] Mark each reviewed file as "Viewed" to collapse it and track your progress.
- [ ] Watch the progress bar in the pull request header to see how many files you've viewed.
- [ ] Review dependency changes (manifest/lock file) if present, and check for security vulnerabilities.

## Python-specific checks

- [ ] Code follows the style conventions of [PEP 8 – Style Guide for Python Code](https://peps.python.org/pep-0008/).
- [ ] Docstrings follow [PEP 257](https://peps.python.org/pep-0257/) conventions where applicable.
- [ ] New or changed code is covered by tests; `python -m doctest` or your test runner passes.
- [ ] Refer to the official Python documentation when in doubt about library behavior.
- [ ] No `print` debugging left behind; use the `logging` module where appropriate.

## Finishing the review

- [ ] Re-read your comments for tone: constructive, specific, and actionable.
- [ ] Finish and approve the pull request or request changes by submitting your review with a summary comment.
- [ ] Remember: pending comments are only visible to you until you submit your review.
