# Security policy

This is the default policy for the repositories of the Shipwick organization.
[shipwick/shipwick](https://github.com/shipwick/shipwick/blob/main/SECURITY.md)
has its own, with what counts as a vulnerability in the agent, the CLI and the
dashboard, and what does not.

## Reporting a vulnerability

**Please do not open a public issue.** Report privately, either way:

- Email **security@shipwick.com**
- On GitHub, the *Report a vulnerability* button on the repository's
  **Security** tab (private; only maintainers see it)

This includes the parts of the installation chain that live outside the main
repository: the Homebrew formula and how it is generated, and
`get.shipwick.com`, which decides what `curl -fsSL https://get.shipwick.com | sh`
downloads.

You can expect an acknowledgement within 3 days and an assessment within 10. A
fix is released before details are published, and you are credited in the
release notes unless you prefer otherwise. There is no bug bounty.
