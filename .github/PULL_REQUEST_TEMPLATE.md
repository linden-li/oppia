<!--
  - Thanks for submitting code to Oppia! Please fill out the following as part of
  - your pull request so we can review your code more easily.
  -->

## Explanation
<!--
  - Explain what your PR does. If this PR fixes an existing bug, please include
  - "Fixes #bugnum:" in the explanation so that GitHub can auto-close the issue
  - when this PR is merged.
  -->

## Checklist
- [ ] The PR title starts with "Fix #bugnum: ", followed by a short, clear summary of the changes. (If this PR fixes part of an issue, prefix the title with "Fix part of #bugnum: ...".)
- [ ] The PR explanation includes the words "Fixes #bugnum: ..." (or "Fixes part of #bugnum" if the PR only partially fixes an issue).
- [ ] The linter/Karma presubmit checks have passed.
  - These should run automatically, but if not, you can manually trigger them locally using `python -m scripts.pre_commit_linter` and `python -m scripts.run_frontend_tests`.
- [ ] The PR is made from a branch that's **not** called "develop".
- [ ] The PR has an appropriate "PROJECT: ..." label (Please add this label for the first-pass review of the PR).
- [ ] The PR has an appropriate "CHANGELOG: ..." label (If you are unsure of which label to add, ask the reviewers for guidance).
- [ ] The PR follows the [style guide](https://github.com/oppia/oppia/wiki/Coding-style-guide).
- [ ] The PR addresses the points mentioned in the codeowner checks for the files/folders changed. (See the [codeowner's wiki page](https://github.com/oppia/oppia/wiki/Oppia%27s-code-owners-and-checks-to-be-carried-out-by-developers).)
- [ ] The PR is **assigned** to an appropriate reviewer.
  - If you're a new contributor, please ask on [Gitter](https://gitter.im/oppia/oppia-chat) for someone to assign a reviewer and don't tick this checkbox.
  - If you're not sure who the appropriate reviewer is, please assign to the issue's "owner" -- see the "talk-to" label on the issue. Do not only request the review but also add the reviewer as an assignee.
