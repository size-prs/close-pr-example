# close-pr-example

This is a working example of how you could use [Size PRs](https://github.com/apps/size-prs).

## Scenario

You want to ensure everyone creates small Pull Requests.

So, you could create a Github workflow that will automatically close too large PRs.

## Setup

1. Install the Size PRs application.
1. Create [.github/workflows/close-pr.yaml](.github/workflows/close-pr.yaml) to automatically close Pull Requests.

This example closes `huge` Pull Requests, but you could change the conditions or use other labels for your workflow.

## Example Pull Request

[Pull Request #2](https://github.com/size-prs/close-pr-example/pull/2) shows what happens when a PR is labelled with `size/huge`.
