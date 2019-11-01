# npm-package-template

A template for npm packages built in TypeScript

## Setting Up the New Repo

1. Hit "Use This Template" to create the repository
2. Enable CircleCI
3. In Settings
4. Disable "Wikis"
5. Disable "Projects"
6. Disable "Allow merge commits"
7. Disable "Allow rebase merging"
8. Enable "Automatically delete head branches"
9. Create a new branch
10. Commit initial code to the branch (be sure to replace all refernces to npm-package-template, and remove these instructions from the README)
11. Push the new branch and create a PR
12. In Settings -> Branch Protection, create a new rule
13. Use "master" as the branch name pattern
14. Enable "Require status checks to pass before merging"
15. Select the unit tests as required
16. Enable "Include administrators"
17. Enable "Restrict who can push to matching branches"
18. Merge the PR

## Installation

```
yarn add @forbeslindesay/npm-pa ckage-template
```

## Usage

```ts
import add from '@forbeslindesay/npm-package-template';

const result = add(2, 3);
// => 5
```
