# WP Ultimate Security GitHub configuration

This repository holds the WP Ultimate Security organization profile and the
shared contribution, security, and support guidance for our public projects.

The profile in `profile/README.md` is what visitors see at
[github.com/wpultimatesecurity](https://github.com/wpultimatesecurity).

| File | Purpose |
| --- | --- |
| [profile/README.md](profile/README.md) | Public profile shown on the organization page. |
| [CONTRIBUTING.md](CONTRIBUTING.md) | General contribution guidance. |
| [SECURITY.md](SECURITY.md) | Private vulnerability reporting and safe testing guidance. |
| [SUPPORT.md](SUPPORT.md) | Product support and repository issue routing. |
| [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) | Community expectations and conduct reporting. |
| [Issue forms](.github/ISSUE_TEMPLATE/) | Bug reports, feature requests, and support links. |
| [Pull request template](.github/PULL_REQUEST_TEMPLATE.md) | Change summary and review checklist. |

## How GitHub uses these files

GitHub applies a community file from this repository to any repository in the
organization that does not have its own. Repository-specific files always win.
A repository with its own issue templates or template configuration does not
inherit this issue-template directory at all, so the forms here apply only to
repositories that ship none of their own.

See [GitHub's default community file documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

Our current public repositories define their own issue and pull request
templates, so the copies here are the fallback for future repositories. When
you change one, check whether the per-repository versions should change too.

## Branch convention

`dev` is the default branch and the branch the organization profile is read
from. Every image in `profile/README.md` is an absolute
`raw.githubusercontent.com/.../dev/...` URL, because organization profiles are
rendered outside repository context and relative paths do not resolve there.

Renaming or replacing `dev` breaks every image on the public profile at once.
If the branch ever changes, update the image URLs in the same commit.

## Reporting contacts

Vulnerability reports and code-of-conduct reports both go to
[support@wpultimatesecurity.com](mailto:support@wpultimatesecurity.com).
Public repositories also accept vulnerability reports privately through
GitHub, which is the preferred route because it keeps the report, the
discussion, and any advisory in one place.

## Media maintenance

The profile uses a small official brand mark, an always-visible dashboard
illustration, and a linked screenshot gallery, followed by official video
links and a social footer.
See [media sources](profile/assets/SOURCES.md) for provenance and retrieval dates.

When the interface or official channels change, review the screenshots, video
links, and social destinations. Keep images recognizable and unaltered, inspect
them for sensitive data, and update the source record when replacing an asset.
Check narrow layouts and both light and dark themes. Preserve descriptive alt
text and the full-size screenshot link.

## License

Text and configuration in this repository are available under the
[MIT License](LICENSE). The brand mark and product screenshots remain the
property of their owners and are not relicensed; see
[media sources](profile/assets/SOURCES.md).
