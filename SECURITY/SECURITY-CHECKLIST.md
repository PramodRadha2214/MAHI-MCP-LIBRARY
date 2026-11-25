# MCP Server Security Checklist

Complete this checklist before recommending or integrating an MCP server.

## Source and supply chain

- [ ] Repository is the official project source or clearly linked by its maintainer.
- [ ] License is identified and compatible with intended use.
- [ ] Release history and maintenance activity are checked.
- [ ] Dependencies and install scripts are inspected.
- [ ] Version or commit is pinned where practical.

## Permissions and isolation

- [ ] Filesystem access is limited to required directories.
- [ ] Network access and remote endpoints are documented.
- [ ] Browser/account access is isolated where practical.
- [ ] Database access uses least-privilege credentials.
- [ ] Server runs without unnecessary administrator/root privileges.
- [ ] Destructive actions have approval gates and backups.

## Secrets and privacy

- [ ] No secrets are stored in the repository.
- [ ] Credentials are supplied through environment variables or a secret manager.
- [ ] Logs do not expose credentials or sensitive personal data.
- [ ] Data transmitted to external services is documented.
- [ ] Credential rotation and revocation steps are known.

## Runtime behavior

- [ ] Tool names and input schemas are understood.
- [ ] Tool outputs are treated as untrusted data.
- [ ] Prompt-injection and indirect instruction risks are considered.
- [ ] Timeouts, rate limits, and error handling are understood.
- [ ] A safe test environment and rollback path exist.

## Approval

- Reviewer:
- Review date:
- Version/commit reviewed:
- Outcome: Unreviewed / Approved for testing / Approved for limited use / Rejected
- Notes:
