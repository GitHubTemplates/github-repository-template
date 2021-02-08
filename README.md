# Github 仓库模板

[![Github Actions][github-action-image]][github-repo-url]
[![license][license-image]](LICENSE)
[![Github Star][github-repo-star-image]][github-repo-url]
[![standard-readme compliant][standard-readme-image]](standard-readme-url)
[![ViewCount](http://hits.dwyl.com/GitHubTemplates/github-repository-template.svg)][github-repo-url]

[背景](#背景) | [介绍](#介绍) | [使用](#使用) | [示例](#示例) | [相关仓库](#相关仓库) | [维护者](#维护者) | [如何贡献](#如何贡献) | [协议](#协议) | [English](README.en-US.md)

## 背景

您可以生成具有与现有仓库相同的目录结构和文件的新仓库。如果有什么想法，欢迎来[讨论](https://github.com/GithubTemplate/github-repository-template/discussions)。

[GitHub 说明地址](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template)

## 介绍

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
├── README.en-US.md
```

### 详细介绍

1. [README.md](README.md)

    > 自诉文件，包含仓库中文件相关信息的文本文件，通常是仓库访问者看到的第一个文件。自述文件连同仓库许可证、参与指南以及行为准则，帮助您交流要求和管理项目的参与。

2. [README.en-US.md](README.en-US.md)

    > 自诉文件英文版。

3. [LICENSE](LICENSE)

    > 许可，一种可随附于项目的文档，告知们能够对您的源代码执行哪些操作，不能执行哪些操作。

4. [.gitignore](.gitignore)

    > gitignore文件指定Git应该忽略的故意未跟踪的文件。 Git已经跟踪的文件不受影响； 有关详细信息，请参见[链接](https://git-scm.com/docs/gitignore)。

5. [CHANGELOG.md](CHANGELOG.md)

    > 每次发布新版本时，记录新版本变化的特性，以及修改的bug等信息。

6. [CONTRIBUTING.md](CONTRIBUTING.md)

    > 贡献规范，比如代码编写规范，如果提问题、提bug、提需求，如何编写文档等。

7. [.github/COMMIT_CONVERTION.md](.github/COMMIT_CONVERTION.md)

    > git提交信息规范。

8. [.github/PULL_REQUEST_TEMPLATE.md](.github/PULL_REQUEST_TEMPLATE.md)

    > 提交`pull request`模版。

9. [.github/ISSUE_TEMPLATE/bug_report.md](.github/ISSUE_TEMPLATE/bug_report.md)

    > 在`issue`中提bug的模版。

10. [.github/ISSUE_TEMPLATE/custom.md](.github.com/ISSUE_TEMPLATE/custom.md)

    > 自定义`issue`模版。

11. [.github/ISSUE_TEMPLATE/feature_request.md](.github/ISSUE_TEMPLATE/feature_request.md)

    > 在`issue`中提需求的模版。

12. [.github/workflows/main.yml](.github.com/workflows/main.yml)

    > GitHub Action配置文件，可以配置仓库的CI/CD。

## 使用

点击[![使用这个模板][use-this-template]][generate]按钮，一键生成标准GitHub仓库。

或者使用`gh`命令行创建项目

```
gh repo create myRepository -p GithubTemplate/github-repository-template
```

## 示例

一般开源项目的仓库，都需要有一些示例说明或者代码，供使用者参考。

## 相关仓库

- [standard-readme](https://github.com/RichardLitt/standard-readme) — 一个标准README样式建议的仓库。
- [Angular.js](https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md) — Angular.js仓库贡献的编写规范

## 维护者

[@BruceMaa](https://github.com/BruceMaa)。

## 如何贡献

非常欢迎你的加入！[提一个 Issue](https://github.com/GithubTemplate/github-repository-template/issues/new) 或者提交一个 Pull Request。

Github-Repository-Template 遵循 [Contributing](CONTRIBUTING.md) 编写规范。

Github-Repository-Template 遵循 [Contributor Covenant](http://contributor-covenant.org/version/1/3/0/) 行为规范。

## 协议

[MIT © Bruce Maa.](LICENSE)

[github-action-image]: https://github.com/GithubTemplate/github-repository-template/workflows/GithubRepositoryTemplate/badge.svg
[github-repo-url]: https://github.com/GithubTemplate/github-repository-template
[license-image]: https://img.shields.io/badge/license-MIT-green.svg
[github-repo-star-image]: https://img.shields.io/github/stars/GithubTemplate/github-repository-template.svg?style=social
[use-this-template]: https://img.shields.io/badge/-use%20this%20template-brightgreen.svg
[generate]: https://github.com/GithubTemplate/github-repository-template/generate
[standard-readme-image]: https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square
[standard-readme-url]: https://github.com/RichardLitt/standard-readme