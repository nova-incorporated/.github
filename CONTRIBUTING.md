# Contributing Guidelines

We highly value all contributions made towards our project. This document was created to make it easier to take in and respond to input. It outlines the requirements that must be met before contributions can be considered.

## Scope of Contributions

We currently accept the following contributions:

- Bug reports
- Feature requests
- Suggestions
- Performance improvements
- Code refactors
- Code reviews
- Workflow and automation changes
- Documentation improvements

## Feature Usage Overview

We aim to use many of the features GitHub provides to ensure the expandability of the project in the long-term. To keep things organized, we outline below what each feature should be used for.

### Discussions

[GitHub Discussions](https://docs.github.com/discussions/collaborating-with-your-community-using-discussions/about-discussions) should be used to share ideas, ask and answer questions, gather community input, and more. Planning and open-ended discussion should most commonly take place in them.

The aim of discussions is to provide an area where casual talk about subjects can be encouraged.

### Issues

You can create [GitHub Issues](https://docs.github.com/issues/tracking-your-work-with-issues/learning-about-issues/about-issues) to suggest _what_ enhancements need to be made to the project and _why_, including contextual references within. They should present ideas and information that have been thought out **before** having being opened. It is advised to create or contribute to [discussions](#discussions) before opening issues, to gather ideas on where the community wants to take the project—considering the needs of other consumers generally increases the likelihood of contributions being approved.

> [!TIP]
> It is advised that you create or contribute to discussions before opening issues, to gather ideas on where the community wants to take the project—considering the needs of other consumers generally increases the likelihood of successful contributions.

Issues must individually be focussed on something specific and task-related; they should not contain unrelated information. When external topics need to be brought up, you can link to other previously-created issues, discussions, or other contextual references briefly to avoid the cluttering created issues.

To create issues, you can use one of the pre-made form templates: they ensure that all the necessary details are provided, so the maintainers can understand what is trying to be communicated.

In comparison to discussions (which are casual and open-ended spaces for conversation), issues should be created to support the quick completion of tasks; therefore, in practice, they should be comprised of pre-planned information that can be easily conveyed.

If you have already made complete changes to the project elsewhere, and would like to request the addition of said changes, please create a [pull request](#pull-requests) instead.

### Pull Requests

[GitHub Pull Requests](https://docs.github.com/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) can be made to propose self-made code changes be merged into production.

## Bug Reports

Problems with code functionality can be reported through [Issues](#issues).

> [!CAUTION]
> Do not report security vulnerabilities through here! See [Security](#security) for more information on why not to do this.

## Security

Please read [SECURITY.md](SECURITY.md) for details on how to report vulnerabilities.

## Feature Requests

Feature requests can be created through [Issues](#issues) to suggest enhancements to functionality and usability.

## Documentation Improvements

You can report typos, missing information, or other deprived areas of documentation through [Issues](#issues).

## Commits

Commits can be made to submit changes that have been made to a project.

Commits must follow the [Conventional Commits specification](https://www.conventionalcommits.org) and [GitHub Flow](https://docs.github.com/get-started/using-github/github-flow).

We have a few more rules on top of the Conventional Commits specification that also must be followed, mainly to enforce consistency in areas that are too easygoing. See below for those rules.

### Commits Specification

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](https://tools.ietf.org/html/rfc2119).

1. Commits messages MUST adopt sentence-case capitalization. For example, instead of `feat: add spanish translation`, the correct case conversion would be `Feat: Add Spanish translation`.

2. Commit messages MUST NOT contain terminal punctuation (i.e.full stops); however, commit descriptions MUST.
