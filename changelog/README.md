# CHANGELOG

A Changelog is a curated, chronologically ordered list of notable changes made to a project. While a git history provides a raw technical record, the Changelog translates those commits into a readable summary for users, contributors, and/or stakeholders.

> [!NOTE]
> The structure of a Changelog is often opinionated, with different teams prioritizing different details. We encourage you to study various formats, and adapt your own style as you continue to refine your release process.

## Examples

> [!NOTE]
> The examples *we* provided are opinionated and intended as guidance. We encourage you to explore other approaches, adapt them to your workflow, and expand upon them to fit the specific needs of your project.

- [CHANGELOG.md](/changelog/CHANGELOG.md)

## Resources

- [Wiki: Changelog](https://en.wikipedia.org/wiki/Changelog)
  > This entry provides a broad overview of the history and evolution of the changelog format.
- [Keep a Changelog](https://keepachangelog.com/en/1.1.0/)
  > Presents a widely adopted and highly opinionated framework for maintaining human-readable logs. While it is considered a modern standard, we encourage you to treat it as a blueprint rather than a rigid rulebook—build off these conventions, adapt them to your project’s unique scale, and continue to learn from how different communities bridge the gap between code and communication.
- [Change Logs (GNU Coding Standards)](https://www.gnu.org/prep/standards/html_node/Change-Logs.html)
  > This resource outlines the GNU approach to CHANGELOG files, which is historically significant but highly opinionated. While these standards provide a rigorous foundation for tracking development, we encourage you to build off this logic and explore modern alternatives to see which style best fits your project's evolution.

## OSS Project Changelog Examples

- [React (Meta)](https://github.com/facebook/react/blob/main/CHANGELOG.md)
  > A dedicated CHANGELOG.md file within the root of the repository.
- [Visual Studio Code (Microsoft)](https://code.visualstudio.com/updates/v1_108)
  > While they have a raw log, their primary changelog is a web-based document full of GIFs, screenshots, and feature highlights.
- [Typescript](https://github.com/microsoft/TypeScript/releases)
  > Instead of a single CHANGELOG.md file, TypeScript utilizes the GitHub Releases tab. Each version is clearly tagged with a summary of new language features and bug fixes.
- [Curl](https://curl.se/changes.html)
  > Curl maintains an incredibly precise and long-running changelog. It lists every single bug fix, contributor, and security patch dating back decades.

## Tools

These tools are used to automate the creation and management of changesets and changelogs. They help ensure release notes are accurate, consistent, and easy to generate as part of the release workflow, reducing manual effort and mistakes.

> [!NOTE]
> These tools are intentionally opinionated and reflect a curated set of preferences rather than an exhaustive list.  
> If you feel a useful tool is missing or have a strong alternative to suggest, please open a Pull Request — contributions and improvements are encouraged.

### [Changesets](https://github.com/changesets/changesets?tab=readme-ov-file#documentation)

Changesets is a highly popular tool, especially in the JavaScript/TypeScript ecosystem and monorepos. Instead of parsing messy commit histories, it requires developers to include a small Markdown file (a "changeset") with every Pull Request.

> If you choose to use changesets, we recommend to configure the
> [Changeset Bot](https://github.com/apps/changeset-bot).  
> The bot helps enforce the presence of changesets in pull requests, keeping
> changelogs accurate and ensuring releases remain consistent and automated.

### [Release-it](https://github.com/release-it/release-it)

Release-it is a versatile CLI tool that automates the entire release bit: bumping versions, committing, tagging, and pushing to npm/GitHub.
