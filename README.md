# HITMA 仓库建设与协作

这里维护哈尔滨工业大学航模协会的仓库规范、协作说明与通用模板。新建项目和接手已有项目时，从下面的入口开始。

## 使用入口

| 你要做什么 | 从哪里开始 |
| --- | --- |
| 新建或整理项目仓库 | [仓库建设与协作规范](docs/repository-standard.md) |
| 编写项目首页 | [README 范本](templates/README-template.md) |
| 提交代码、文档或硬件修改 | [贡献与协作说明](CONTRIBUTING.md) |
| 记录仿真、台架或实机验证 | [验证记录范本](templates/validation-record-template.md) |
| 查看协会介绍 | [组织简介](profile/README.md) |

## 新仓库的最低要求

- 名称和简介能说明项目用途。
- README 写明负责人、当前状态、适用范围和主要目录。
- 软件提供环境、依赖、构建、启动与检查结果的步骤；硬件和教程提供相应使用方法。
- 已验证内容能对应到提交或标签，未验证内容和已知问题如实说明。
- 提交必要源码、配置与资料来源，排除构建缓存、本地凭据和无关文件。

软件、硬件与教程项目可以采用不同目录结构，具体见完整规范。已有仓库在后续维护中逐步补齐，无需一次性重排历史内容。

## 这些文件如何生效

本仓库名为 `.github`，用于提供组织简介与默认协作文件。

| 文件 | 使用方式 |
| --- | --- |
| `profile/README.md` | 显示在组织首页 |
| `CONTRIBUTING.md` | 作为组织内缺少对应文件的仓库的默认贡献指南 |
| `.github/PULL_REQUEST_TEMPLATE.md` | 为没有自定义 PR 模板的仓库提供默认模板 |
| `.github/ISSUE_TEMPLATE/` | 为没有自定义 Issue 模板或配置的仓库提供默认问题表单 |
| `docs/`、`templates/` | 供成员查阅、按需复制和填写 |

仓库自身的对应协作文件优先。某仓库定义了有效的 Issue 模板或配置时，组织默认 Issue 模板目录会整体被覆盖。默认协作文件不会自动复制到各仓库的克隆中。

README 范本、许可证、`.gitignore`、`CODEOWNERS`、工作流和分支保护规则需要各仓库另行配置。本次提供的范本是可复制的文档，不是已配置为 GitHub Template Repository 的项目脚手架。

规则依据：[GitHub 默认社区文件说明](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)。

## 维护与反馈

本仓库由 HITMA2026 组织维护者维护。发现规范不清楚、范本不适用或链接失效时，请在[本仓库的 Issues](https://github.com/HITMA2026/.github/issues) 中提出，或提交 PR 说明修改建议。
