# Contributing to openfisca-aotearoa-betterules

This repository currently contains repository security workflow configuration. Contributions should reflect the actual source present and establish proposed project scope explicitly before introducing application or policy content.

## Before you start

Inspect the current default branch and existing issues and pull requests before starting. There is presently no application README, dependency manifest or documented runtime to use as an installation contract. Describe the intended problem, source ownership and relationship to other OpenFisca or rule repositories before adding substantial implementation.

For bugs, provide the affected version or commit, environment, minimal reproduction, expected result and observed result. For a substantial proposal, describe the use case and compatibility impact before expanding implementation scope. Use existing issue templates when offered.

## Development and validation

Review the current [workflow configuration](.github/workflows) and any proposed files directly. For documentation-only changes, check links, file paths, consistency and sensitive information. For workflow changes, validate the affected YAML and preserve existing permissions and security checks.

No application test command is currently documented here. Do not describe an absent test suite as passing. If introducing executable code, include its supported runtime, reproducible setup, appropriate tests and a clear explanation of what those tests establish in the same focused change. Use independently expected synthetic cases where policy or numerical behaviour is involved.

Keep external jurisdiction rules and data source identities explicit. A repository name does not establish policy validity, source rights or a release commitment. Explain compatibility with any proposed consumers and preserve unknown or unresolved requirements. Do not import a large codebase, change repository visibility or publish a package as an incidental part of a small contribution.

## Pull requests

Create a focused branch from the current `main` branch and submit a pull request to this repository. Link the relevant issue or existing project task, explain the resulting behaviour, and update affected examples and documentation. Keep unrelated changes in separate pull requests.

Report executed commands, outcomes and the commit they validate. Identify unavailable checks and remaining limitations explicitly. Follow the repository's existing review and automated-check requirements; retain required gates and current ownership. Address findings and verify the final head before integration. Repository changes do not themselves authorise a release or external operational action.

## Security, rights and conduct

Follow the [security policy](https://github.com/edithatogo/.github/blob/main/SECURITY.md). Use private vulnerability reporting if available; otherwise request a private contact without publishing vulnerability details. Keep credentials, personal information and restricted source material out of issues, fixtures, logs and artifacts.

Preserve existing attribution and third-party terms. This guide does not grant a licence; clarify any unclear redistribution rights before contributing external material. Follow the [code of conduct](https://github.com/edithatogo/.github/blob/main/CODE_OF_CONDUCT.md) and keep technical discussions respectful.

## Basis for this guide

This guide follows [GitHub's contribution-guideline guidance](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors) and the contribution-process and testing principles in [OpenSSF Best Practices](https://www.bestpractices.dev/en/criteria). It does not assert certification.
