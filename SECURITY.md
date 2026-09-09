# Security policy

## Report privately

Do not report security vulnerabilities through public GitHub issues, pull
requests, discussions, or support forums. This includes exploitable problems in
software, unsafe security examples, and exposed credentials.

Follow the affected repository's own security policy when one exists.
Otherwise, the organization-wide private reporting destination is:

**`SECURITY_CONTACT_REQUIRED`**

This is an unresolved maintainer configuration item, not a working contact.
A dedicated security reporting destination has not been verified. Until it is
configured, you may email [product support](mailto:support@wpultimatesecurity.com)
to request a private security contact. Do not include exploit details or sensitive
data in that initial request. The support address is not a verified security inbox.

## Information to include in a private report

- Affected project, version or revision, and relevant files or components.
- Required access, configuration, and WordPress/PHP versions where applicable.
- Reproduction steps or a minimal proof of concept using synthetic data.
- Expected behavior, observed behavior, and potential impact.
- Sanitized evidence and a suggested fix, if available.

Do not send production credentials, unrelated personal data, or full database
exports. Share only what is needed to understand and reproduce the issue.

## Safe testing and disclosure

Test only systems you own or have explicit permission to assess. Prefer an
isolated environment with synthetic data. Avoid destructive testing, service
disruption, accessing unrelated user data, or retaining data encountered by
accident. Stop testing if it could harm other users or systems.

Coordinate publication of vulnerability details with the maintainers so they
can investigate and prepare a correction. This policy does not promise a response
time, remediation deadline, bounty, or other compensation, and does not authorize
testing of third-party systems.

For ordinary bugs and product questions, see
[support guidance](https://github.com/wpultimatesecurity/.github/blob/main/SUPPORT.md).
