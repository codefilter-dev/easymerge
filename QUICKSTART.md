# Quickstart

Use this guide to connect a repository and receive your first EasyMerge review.

## Before you begin

- You need a GitHub account.
- To install EasyMerge for an organization, you must be an organization owner
  or request approval from one.
- You need a non-draft pull request in a repository available to the app.

## 1. Sign in

After receiving access to EasyMerge, choose **Continue with GitHub**. Signing in
identifies your account; it does not grant repository access.

## 2. Install the GitHub App

Choose a personal account or organization, then grant access to all repositories
or select specific repositories. EasyMerge asks for read access to repository
contents and write access for pull-request reviews, comments, and check runs. It
does not request write access to source code.

See the complete [GitHub permissions](https://easymerge.dev/docs/getting-started/install-github-app#permissions-requested)
before installing.

## 3. Open a pull request

Create a pull request against the repository's default branch. EasyMerge starts
a review when a non-draft pull request is opened and whenever you push a new
commit. Draft pull requests wait until they are marked ready for review.

## 4. Follow the review

Open the pull request on GitHub and find the **EasyMerge Review** check. It moves
from queued to in progress, then reports the result on the head commit. You can
also follow progress in the EasyMerge dashboard.

## 5. Act on the findings

Read the recommendation and summary, then inspect each inline finding. Apply a
suggested change when appropriate, discuss the finding with your team, or
resolve the conversation according to your normal review process. Push a new
commit to trigger a fresh review of the updated diff.

EasyMerge does not approve, block, or merge the pull request. Your existing
reviewers, CI checks, and branch protection rules remain in control.

## If a review does not start

Confirm that the pull request is not a draft and that the repository is included
in the GitHub App installation. Then check the
[troubleshooting guide](https://easymerge.dev/docs/reference/troubleshooting).

For detailed installation and configuration instructions, see the [EasyMerge documentation](https://easymerge.dev/docs/getting-started/quickstart).
