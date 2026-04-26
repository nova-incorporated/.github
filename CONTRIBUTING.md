# Contributing Guidelines

We highly value all contributions made towards our project. This document was created to make it easier to take in and respond to input. It outlines the requirements that must be met before contributions can be considered.

## Scope of Contributions

We currently accept the following contributions:

- Bug reports
- Documentation issue reports
- Feature requests
- Performance improvements
- Code refactors
- Code reviews
- Workflow and automation changes

## Security Vulnerabilities

Please read [SECURITY.md](SECURITY.md) for details on how to report vulnerabilities.

## Discussions

[GitHub Discussions](https://docs.github.com/discussions/collaborating-with-your-community-using-discussions/about-discussions) should be used to share ideas, ask and answer questions, gather community input, and more. Planning and open-ended discussion should most commonly take place in them.

The aim of discussions is to provide an area where casual talk about subjects can be encouraged.

## Issues

You can use [GitHub Issues](https://docs.github.com/issues/tracking-your-work-with-issues/learning-about-issues/about-issues) to suggest _what_ enhancements need to be made to the project and _why_, including contextual references within. They should present ideas and information that have been thought out **before** having being opened. All the types of issues you can currently open—including [bug reports](#bug-reports) and [feature requests](#feature-requests)—are documented below.

> [!TIP]
> It is advised that you create or contribute to discussions before opening issues, to gather insight on where the rest of the community wants to take the project—considering and tailoring contributions to fit the needs of others generally increases the chance those contributions will meet approval.

Issues should individually focus on something **specific** that needs doing; they should not contain unrelated information. When external topics need to be brought up, you can link to other previously-created issues, discussions, or other contextual references briefly, without impeding the main flow of conversation.

Pre-made form templates should be used at all times before opening issues: they ensure that all the necessary details are provided so the maintainers can understand what's trying to be communicated.

In comparison to discussions (which are casual and open-ended spaces for conversation), issues should focus on promoting quick completion of tasks; therefore, in practice, they should be comprised of pre-planned information that can be easily conveyed.

If you have already made complete changes to the project elsewhere, and would like to request the addition of said changes, please create a [pull request](#pull-requests) instead.

### Bug Reports

You can report problems with code functionality.

> [!CAUTION]
> Do not report security vulnerabilities through here; see [SECURITY.md](SECURITY.md) for where to go instead.

### Feature Requests

Feature requests can be created to suggest enhancements to functionality and usability.

### Documentation Issue Reports

You can report typos, missing information, or other deprived areas of documentation.

## Pull Requests

[GitHub Pull Requests](https://docs.github.com/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) can be used to propose self-made code changes be merged into production.

## Commits

Commits can be made to submit changes that have been made to a project.

All commits must follow the [Conventional Commits specification](https://www.conventionalcommits.org) and [GitHub Flow](https://docs.github.com/get-started/using-github/github-flow). We have a few more rules built on top of Conventional Commits that also must be followed, mainly to tighten areas of the original specification that are too easygoing. See [below](#commits-specification) for those rules.

### Commits Specification

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](https://tools.ietf.org/html/rfc2119).

1. Commits messages MUST adopt sentence-case capitalization. For example, instead of `feat: add spanish translation`, the correct case conversion would be `Feat: Add Spanish translation`.

2. Commit messages MUST NOT contain terminal punctuation (i.e.full stops); however, commit descriptions MUST.
