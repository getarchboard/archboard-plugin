# Security policy

## Reporting a vulnerability

Email **hello@getarchboard.app** with a description of the issue and the steps to reproduce it. English and Turkish
are both fine. The same contact is published in
[security.txt](https://getarchboard.app/.well-known/security.txt) (RFC 9116).

Please do not open a public GitHub issue for a security problem, and do not include other people's data in a report.

## Scope

- The Archboard MCP server at `https://getarchboard.app/mcp`, its OAuth endpoints, and the Archboard web app at
  `https://getarchboard.app`.
- The files in this repository: manifests, the skill and images. They contain no code and no credentials.

## What happens next

Reports are answered by email from the same address. Fixes to the hosted service are deployed on Archboard's side; no update of this
repository is needed unless a manifest changes.
