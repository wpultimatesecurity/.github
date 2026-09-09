# Security policy

## Report privately

Do not report security vulnerabilities through public GitHub issues, pull
requests, discussions, or support forums. This includes exploitable problems in
software, unsafe security examples, and exposed credentials.

Follow the affected repository's own security policy when one exists.

## What this policy covers

- The Ultimate Security plugin published on
  [WordPress.org](https://wordpress.org/plugins/ultimate-security/).
- The public repositories in the
  [WP Ultimate Security organization](https://github.com/wpultimatesecurity).

Reports about sites that merely run the plugin belong with those site owners,
not with us.

## How to report

Use GitHub's private vulnerability reporting where the affected code lives on
GitHub: open the repository's **Security** tab and choose **Report a
vulnerability**. The report stays private, and the discussion and any advisory
stay attached to the project.

For the plugin itself, whose source is not published on GitHub, or if you
cannot use GitHub, email
[support@wpultimatesecurity.com](mailto:support@wpultimatesecurity.com).
Use a subject such as "Security report: project name" to help us route it.

## Information to include in a private report

- Affected project, version or revision, and relevant files or components.
- Required access, configuration, and WordPress/PHP versions where applicable.
- Steps to reproduce the issue or a small proof of concept using test data.
- Expected behavior, observed behavior, and potential impact.
- Logs or screenshots with sensitive information removed, and a suggested fix if you have one.

Do not send production credentials, unrelated personal data, or full database
exports. Share only what is needed to understand and reproduce the issue.

## Safe testing and disclosure

Test only systems you own or have explicit permission to assess. Use an
isolated environment with test data wherever possible. Avoid destructive testing, service
disruption, accessing unrelated user data, or retaining data encountered by
accident. Stop testing if it could harm other users or systems.

Coordinate publication of vulnerability details with the maintainers so they
can investigate and prepare a correction. This policy does not promise a response
time, remediation deadline, bounty, or other compensation, and does not authorize
testing of third-party systems.

For ordinary bugs and product questions, see
[support guidance](https://github.com/wpultimatesecurity/.github/blob/dev/SUPPORT.md).
