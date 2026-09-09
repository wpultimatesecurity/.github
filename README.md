# WP Ultimate Security GitHub configuration

This repository holds the WP Ultimate Security organization profile and shared
contribution, security, and support guidance. It is prepared locally for
publication as `wpultimatesecurity/.github`.

| File | Purpose |
| --- | --- |
| [profile/README.md](profile/README.md) | Public profile shown on the organization page. |
| [CONTRIBUTING.md](CONTRIBUTING.md) | General contribution guidance. |
| [SECURITY.md](SECURITY.md) | Private vulnerability reporting and safe testing guidance. |
| [SUPPORT.md](SUPPORT.md) | Product support and repository issue routing. |
| [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) | Community expectations and conduct reporting. |
| [Issue forms](.github/ISSUE_TEMPLATE/) | Bug reports, feature requests, and support links. |
| [Pull request template](.github/PULL_REQUEST_TEMPLATE.md) | Change summary and review checklist. |

GitHub uses supported community files as defaults where a repository has no
corresponding file. Repository-specific guidance takes precedence. A repository
with its own issue templates or template configuration does not inherit this
issue-template directory. See [GitHub's default community file documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

## Before publication

- Replace `SECURITY_CONTACT_REQUIRED` in the security policy with a verified
  private vulnerability reporting destination.
- Replace `CONDUCT_CONTACT_REQUIRED` in the code of conduct with a designated
  private reporting destination and confirm who will handle reports.
- Review these policies before adopting them organization-wide.

Profile and shared-policy links target `wpultimatesecurity/.github` on `dev`.
They will become live only after these files are manually published there.
Local links above can be used for review in the meantime.

## Branch convention

`dev` is the working branch and intended GitHub default branch for this
repository. After manual publication, select `dev` as the repository default
on GitHub so the organization profile and community defaults use this branch.
Renaming the local branch does not change GitHub settings.

This checkout has no Git remote. No publication automation is included.

## Media maintenance

The profile uses a small official brand mark and a dashboard illustration in a
collapsed product preview, followed by official video links and a social footer.
See [media sources](profile/assets/SOURCES.md) for provenance and retrieval dates.

When the interface or official channels change, review the screenshot, video
links, and social destinations. Keep images recognizable and unaltered, inspect
them for sensitive data, and update the source record when replacing an asset.
Check narrow layouts and both light and dark themes. Preserve descriptive alt
text and the full-size screenshot link.

Image URLs target the future repository on `dev`, so they become live only
after manual publication. For local review, open the PNG files in `profile/assets`.
