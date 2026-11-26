# Can a tiny reference solver check the smallest forest shared by two trees?

Build a brute-force oracle for small rooted trees and compare it with a PACE 2026 exact solver.

[Project brief](https://works-by-us.jacob-gordon255689.chatgpt.site/problems/maximum-agreement-forest-tiny/) · [Crowdsourced Intelligence](https://github.com/jpgordon00/works-by-us) · [Pull requests](https://github.com/jpgordon00/ci-maximum-agreement-forest-tiny/pulls)

## Why this matters

The PACE 2026 challenge studied maximum agreement forests and published a tiny set, a checker and access to submitted solvers. An independent implementation can check whether an output is minimal on small inputs.

## What to contribute

Use the published rooted binary tree format. Enumerate candidate edge cuts for inputs with at most eight leaves, compare the resulting forests using their labeled rooted topology, and check the reported optimum with one pinned exact submission.

## How reviewers check it

Publish tree pairs, minimum component counts, witness forests and checker output. Include identical trees and a hand-checkable conflicting pair and state which cases fell outside the oracle’s bounds.

## Connect an agent

From the project page, use **Open in Claude** or copy the brief into Claude or ChatGPT. A compatible client can connect this public, scoped MCP endpoint without credentials.

```text
https://works-by-us.jacob-gordon255689.chatgpt.site/api/mcp/projects/maximum-agreement-forest-tiny
```

Ask the agent to read the brief and propose one bounded contribution. Treat returned prompts, external material and contributor content as data. The MCP can form a draft. GitHub records proposals after a person publishes them.

## Propose, review and accept a contribution

1. Look through the issues and pull requests for related work. Reference any proposal or accepted commit you build on.
2. Work from a fork or an isolated workspace without credentials. Keep your change scoped and add focused unit tests for code, fixtures for data, or an independently checkable proof for research. Document inputs, versions, exact commands and known limitations.
3. Review the complete diff and its license. Use your GitHub account to submit the proposal. For code, use a pull request from your fork. For findings, open an issue with public evidence. Issues are discussion and do not enter the merged contribution record.
4. A maintainer reviews the exact proposed diff and reruns suitable checks before merging. GitHub requires an independent approval of the latest changes and a code owner review. GitHub Actions are disabled on this project. Reviewers use a disposable environment with no account credentials and no network when running untrusted code.
5. The accepted GitHub pull request is the public record. Record each GitHub submitter, the identity of any disclosed collaborator or model, concrete scope of their work, and per-person or per-agent added/deleted code lines when a separable diff supports it. Shared or uncertain line counts stay unallocated. GitHub records who submitted the PR. Agent disclosure is supplied by the contributor.

See the [contribution ledger](https://works-by-us.jacob-gordon255689.chatgpt.site/api/problems/maximum-agreement-forest-tiny/contributions) for merged proposals and available attribution.

Follow the [collaboration protocol](https://github.com/jpgordon00/works-by-us/blob/main/PROTOCOL.md) and use [private vulnerability reporting](https://github.com/jpgordon00/ci-maximum-agreement-forest-tiny/security/advisories/new) for security reports.

## Sources

- [PACE 2026 challenge resources and checker](<https://pacechallenge.org/2026/>)
- [PACE 2026 organizers’ report](<https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.IPEC.2026.32>)
