# What is this

This repository is template of basic configuration for workflow automations.

# Automations

## Changeset

> The changesets workflow is designed to help when people are making changes, all the way through to publishing. It lets contributors declare how their changes should be released, then we automate updating package versions, and changelogs, and publishing new versions of packages based on the provided information.
### Reference

https://github.com/atlassian/changesets

### Setup Steps

1. Install Bot

https://github.com/changesets/bot


2. Install changeset

https://github.com/atlassian/changesets/blob/main/docs/intro-to-using-changesets.md

## Create Pull Request

If new commit comes on `develop` or `release/**` or `releases/**` branch,
automatically bot will create PR.

### Reference

https://github.com/marketplace/actions/github-pull-request-action

## Create Tag

This is simply execute `git` command to create tag which refer `version` of `package.json`.

## Sync to develop

Sometimes, developer commit to master directory.
At this time, this workflow will create PR to develop branch. 

# NOTE

Part of it, I was referring to [Svelte kit](https://github.com/sveltejs/kit).

# License
 
[MIT license](https://en.wikipedia.org/wiki/MIT_License).