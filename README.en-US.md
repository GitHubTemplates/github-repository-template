# Github Repository Template

[![Github Actions][github-action-image]][github-repo-url]
[![license][license-image]](LICENSE)
[![Github Star][github-repo-star-image]][github-repo-url]
[![standard-readme compliant][standard-readme-image]](standard-readme-url)
[![ViewCount](http://hits.dwyl.com/GitHubTemplates/github-repository-template.svg)][github-repo-url]

[Background](#background) | [Introduction](#introduction) | [Usage](#usage) | [Examples](#examples) | [Related Efforts](#related-efforts) | [Maintainers](#maintainers) | [Contributing](#contributing) | [License](#license) | [中文](README.md)

## Background

You can generate a new repository with the same directory structure and files as an existing repository. If you have some idea, welcome to [discussion](https://github.com/GithubTemplate/github-repository-template/discussions).

[GitHub Template Docs](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template)

## Introduction

```
github-repository-template
├── .github
│   ├── COMMIT_CONVENTION.md
│   ├── ISSUE_TEMPLATE
│   │   ├── bug_report.md
│   │   ├── custom.md
│   │   └── feature_request.md
│   ├── PULL_REQUEST_TEMPLATE.md
│   └── workflows
│       └── main.yml
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── README.md
├── README.zh-CN.md
```

### 详细介绍

1. [README.md](README.md)

    > A text file containing information about the files in a repository that is typically the first file a visitor to your repository will see. A README file, along with a repository license, contribution guidelines, and a code of conduct, helps you share expectations and manage contributions to your project.

2. [README.en-US.md](README.en-US.md)

    > README use English.

3. [LICENSE](LICENSE)

    > A document that you can include with your project to let people know what they can and can't do with your source code.

4. [.gitignore](.gitignore)

    > A gitignore file specifies intentionally untracked files that Git should ignore. Files already tracked by Git are not affected; see the [NOTES](https://git-scm.com/docs/gitignore).

5. [CHANGELOG.md](CHANGELOG.md)

    > Every time a new version is released, record the changed features of the new version, as well as the modified bug and other information.

6. [CONTRIBUTING.md](CONTRIBUTING.md)

    > Contribution specifications, such as code writing specifications, if you ask questions, raise bugs, raise requirements, how to write documents, etc.

7. [.github/COMMIT_CONVERTION.md](.github/COMMIT_CONVERTION.md)

    > git commit information specification.

8. [.github/PULL_REQUEST_TEMPLATE.md](.github/PULL_REQUEST_TEMPLATE.md)

    > the template of `pull request`.

9. [.github/ISSUE_TEMPLATE/bug_report.md](.github/ISSUE_TEMPLATE/bug_report.md)

    > the template of raise bug in issue.

10. [.github/ISSUE_TEMPLATE/custom.md](.github.com/ISSUE_TEMPLATE/custom.md)

    > custom issue template.

11. [.github/ISSUE_TEMPLATE/feature_request.md](.github/ISSUE_TEMPLATE/feature_request.md)

    > the template of raise requirement in issue.

12. [.github/workflows/main.yml](.github.com/workflows/main.yml)

    > GitHub Action profile.

## Usage

click[![use this template][use-this-template]][generate]button，create a standard github repository quickly。

or use GitHub cli `gh`

```
gh repo create myRepository -p GithubTemplate/github-repository-template
```

## Examples

Generally, the open source repository need to have some examples or codes for users' reference.

## Related Efforts

- [standard-readme](https://github.com/RichardLitt/standard-readme) — A standard style for README files.
- [Angular.js](https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md) — The CONTRIBUTING of Angular.js.

## Maintainers

[@BruceMaa](https://github.com/BruceMaa)。

## Contributing

Feel free to dive in![Open an Issue](https://github.com/GithubTemplate/github-repository-template/issues/new) or submit PRs。

Github-Repository-Template follows the [Contributing](CONTRIBUTING.md) specification。

Github-Repository-Template follows the [Contributor Covenant](http://contributor-covenant.org/version/1/3/0/) Code of Conduct。

## License

[MIT © Bruce Maa.](LICENSE)

[github-action-image]: https://github.com/GithubTemplate/github-repository-template/workflows/GithubRepositoryTemplate/badge.svg
[github-repo-url]: https://github.com/GithubTemplate/github-repository-template
[license-image]: https://img.shields.io/badge/license-MIT-green.svg
[github-repo-star-image]: https://img.shields.io/github/stars/GithubTemplate/github-repository-template.svg?style=social
[use-this-template]: https://img.shields.io/badge/-use%20this%20template-brightgreen.svg
[generate]: https://github.com/GithubTemplate/github-repository-template/generate
[standard-readme-image]: https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square
[standard-readme-url]: https://github.com/RichardLitt/standard-readme