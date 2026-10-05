# AgentDesk Docs

User documentation published at https://docs.agentdesk.team from the canonical
GitHub repository https://github.com/AgentDesk-team/docs.

## Maintain

For AgentDesk documentation work, inspect the current React frontend and
capability contracts in the Huy staging Linux devbox. Edit and validate the
docs in an owned branch under the workspace's Working-files area. Preserve
existing public page URLs when replacing outdated instructions.

Keep user-facing instructions distinct from implementation evidence. Put
private source audits and verification reports outside this publication tree.
Internal historical references remain excluded by .mintignore.

## Preview and validate

Use an LTS Node version supported by the Mintlify CLI:

```bash
mint dev
mint validate
mint broken-links
```

## Publish

Publish the reviewed commit through the canonical GitHub repository's configured
Mintlify branch. Verify the live index, navigation, and changed pages after
deployment. A local validation or Git push alone does not prove publication.

The 2026-10-05 guide covers the current React UI, including detailed workspace
and agent skill management and Agent Context. Wiki and Desktop stay high-level. Features remain subject to deployment,
plan, role, connection, and runtime availability.
