# PULL REQUEST

Request ID: HD-0001

## Summary

TBD

## Canonical Artifacts

- Request: .asdlm/requests/HD-0001/REQUEST.md
- Specification: .asdlm/requests/HD-0001/SPEC.md
- Impact analysis: .asdlm/requests/HD-0001/IMPACT.md
- Implementation plan: .asdlm/requests/HD-0001/PLAN.md
- Implementation notes: .asdlm/requests/HD-0001/IMPLEMENTATION.md
- QA report: .asdlm/requests/HD-0001/QA.md

## Review Checklist

- [ ] Canonical artifacts are up to date
- [ ] QA verdict is passed
- [ ] ADRs added or changed are listed
- [ ] Documentation and release-note impacts are listed

## External SCM

- Provider: github
- Branch: feat/hd-github-pr-adapter-demo
- Pull/Merge request URL: https://github.com/Dan-M/demo-wf/pull/1
- Status: updated existing GitHub pull request

## Changed Files

- No local git changes detected

## Manual Review Commands

- git status --short
- git diff --stat
- git diff

## SCM Commands Run

- gh auth status
- git push -u origin HEAD
- gh pr view --json url --jq .url
- gh pr edit --title <title> --body <body>
- gh pr checks --json name,state,bucket,link

## GitHub Checks

- GitGuardian Security Checks: SUCCESS (pass) - https://dashboard.gitguardian.com
