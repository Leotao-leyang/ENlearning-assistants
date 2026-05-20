# 贡献指南 | Contributing Guidelines

感谢你考虑为 **ENlearning Assistant** 项目做出贡献！本指南将帮助你了解如何有效地报告问题、提出建议或直接贡献代码与内容。

Thank you for considering contributing to the **ENlearning Assistant** project! This guide will help you understand how to effectively report issues, suggest new features, or contribute code and content directly.

---

## 📑 目录 | Table of Contents
- [行为准则 | Code of Conduct](#行为准则--code-of-conduct)
- [如何贡献 | How to Contribute](#如何贡献--how-to-contribute)
  - [报告 Bug | Reporting Bugs](#报告-bug--reporting-bugs)
  - [建议新功能 | Requesting Features](#建议新功能--requesting-features)
  - [贡献文档或代码 | Contributing Docs or Code](#贡献文档或代码--contributing-docs-or-code)
- [开发与提交规范 | Development & Commit Conventions](#开发与提交规范--development--commit-conventions)
  - [分支策略 | Branch Strategy](#分支策略--branch-strategy)
  - [提交信息规范 | Commit Message Convention](#提交信息规范--commit-message-convention)
- [Pull Request 流程 | Pull Request Process](#pull-request-流程--pull-request-process)
- [本地开发设置 | Local Development Setup](#本地开发设置--local-development-setup)

---

## 行为准则 | Code of Conduct

本项目所有参与者均需遵守友好、尊重、包容的交流原则。我们致力于提供一个无骚扰的协作环境。

All participants in this project are expected to adhere to the principles of friendly, respectful, and inclusive communication. We are committed to providing a harassment-free collaborative environment.

---

## 如何贡献 | How to Contribute

### 报告 Bug | Reporting Bugs
如果你发现了一个 Bug，请在 [Issues](https://github.com/Leotao-leyang/ENlearning-assistants/issues) 页面创建一个新的 Issue。

If you find a bug, please create a new Issue on the [Issues](https://github.com/Leotao-leyang/ENlearning-assistants/issues) page.

**请务必在 Issue 中提供以下信息，以便我们快速定位问题：**
**Please be sure to include the following information in the Issue for quick troubleshooting:**

*   **清晰的标题和问题描述 | Clear title and description of the problem.**
*   **复现步骤 | Steps to Reproduce:** 详细说明如何触发这个 Bug。Describe in detail how to trigger the bug.
*   **预期行为 vs 实际行为 | Expected vs Actual Behavior:** 你期望发生什么，实际发生了什么。What you expected to happen versus what actually happened.
*   **相关环境 | Relevant Environment:** 你使用的 AI 模型（如 Claude-3.5-Sonnet）、浏览器、操作系统等。The AI model you used (e.g., Claude-3.5-Sonnet), browser, OS, etc.
*   **截图或日志 | Screenshots or Logs**（如果有的话 | if available）。

### 建议新功能 | Requesting Features
我们欢迎一切能改进 ENlearning Assistant 的想法！在提交功能建议前，建议先查看现有的 Issue，避免重复。

We welcome all ideas to improve ENlearning Assistant! Before submitting a feature request, please check existing Issues to avoid duplicates.

**一个好的功能建议应包括：**
**A good feature request should include:**

*   你希望解决什么**问题**或满足什么**需求** | The **problem** you want to solve or the **need** you want to fulfill.
*   你设想的**解决方案**或功能描述 | Your proposed **solution** or description of the feature.
*   这个功能可能带来的**好处** | The potential **benefits** of this feature.

### 贡献文档或代码 | Contributing Docs or Code
1.  **Fork 本仓库**到你自己的 GitHub 账户。**Fork this repository** to your own GitHub account.
2.  **克隆仓库到本地**：`git clone https://github.com/你的用户名/ENlearning-assistants.git` **Clone the repository locally:** `git clone https://github.com/YOUR_USERNAME/ENlearning-assistants.git`
3.  **创建特性分支**：`git checkout -b feature/your-feature-name` (或 `docs/your-doc-fix`)**Create a feature branch:** `git checkout -b feature/your-feature-name` (or `docs/your-doc-fix`)
4.  **进行修改**，并确保你的更改是聚焦的（一次只解决一个问题）。**Make your changes**, and ensure they are focused (solving one problem at a time).
5.  **提交更改**：请遵循下面的[提交信息规范](#提交信息规范)。**Commit your changes:** Please follow the [Commit Message Convention](#提交信息规范--commit-message-convention) below.
6.  **推送分支**：`git push origin feature/your-feature-name`**Push the branch:** `git push origin feature/your-feature-name`
7.  **提交 Pull Request (PR)**：回到我们的仓库页面，你会看到创建 PR 的提示。请按照模板填写。**Submit a Pull Request (PR):** Return to our repository page, and you'll see a prompt to create a PR. Please fill it out according to the template.

---

## 开发与提交规范 | Development & Commit Conventions

### 分支策略 | Branch Strategy
*   `main` 分支：受保护分支，存放稳定、可发布的版本。`main` branch: The protected branch for stable, releasable versions.
*   `feature/*` 分支：用于开发新功能。`feature/*` branches: For developing new features.
*   `docs/*` 分支：用于文档改进。`docs/*` branches: For documentation improvements.
*   `fix/*` 分支：用于修复 Bug。`fix/*` branches: For bug fixes.

### 提交信息规范 | Commit Message Convention
请使用清晰、格式化的提交信息。我们推荐使用类似 [Conventional Commits](https://www.conventionalcommits.org/) 的格式：

Please use clear, formatted commit messages. We recommend a format similar to [Conventional Commits](https://www.conventionalcommits.org/):

```markdown
<类型>[可选 范围]: <描述>

[可选 正文]

[可选 脚注]
```
```markdown
<Type> (optional, range): <Description>

[optional body text]

[optional footnote]
```
**常见类型 | Common Types:**
*   `feat`: 新功能 | A new feature
*   `fix`: 修复 Bug | A bug fix
*   `docs`: 仅文档更改 | Documentation only changes
*   `style`: 不影响代码含义的更改（空格、格式等）| Changes that do not affect the meaning of the code (spaces, formatting, etc.)
*   `refactor`: 既非新功能也非 Bug 修复的代码重构 | Code refactoring that is neither a new feature nor a bug fix
*   `test`: 添加或修改测试 | Adding or modifying tests
*   `chore`: 对构建过程或辅助工具的更改 | Changes to the build process or auxiliary tools

**示例 | Examples:**
*   `docs: add contribution guidelines in Chinese and English`
*   `feat(prompt): add new module for vocabulary review scheduling`
*   `fix(lexile): correct calculation in dynamic adjustment formula`
*   `refactor(workflow): split monday dispatch into separate prompts`

---

## Pull Request 流程 | Pull Request Process
1.  **确保 PR 描述清晰**：说明了更改的内容、原因以及如何测试。**Ensure the PR description is clear**: It should explain what was changed, why, and how to test it.
2.  **关联 Issue**：如果此 PR 解决了某个 Issue，请在描述中使用 `Closes #123` 或 `Fixes #123` 的格式。**Link to an Issue**: If this PR resolves an issue, please use the format `Closes #123` or `Fixes #123` in the description.
3.  **通过评审**：项目维护者会对 PR 进行代码审查，可能会提出修改意见。请及时跟进讨论和修改。**Pass Review**: Project maintainers will review the PR and may request changes. Please follow up on the discussion and modifications promptly.
4.  **合并**：一旦通过审查，你的贡献将被合并到主分支。感谢你的付出！**Merge**: Once approved, your contribution will be merged into the main branch. Thank you for your contribution!

---

## 本地开发设置 | Local Development Setup
本项目主要包含提示词 (Prompts) 和文档。要参与开发，你可能需要：

This project primarily contains prompts and documentation. To participate in development, you may need:

*   一个文本编辑器（如 VS Code）。
*   Git 版本控制系统。
*   （可选）Python 环境，用于运行项目脚本（如 `scripts/assemble_prompt.py`）。安装依赖可运行：`pip install -r requirements.txt`（如果存在该文件）。

*A text editor (e.g., VS Code).*
*   Git version control system.
*   (Optional) A Python environment to run project scripts (e.g., `scripts/assemble_prompt.py`). Install dependencies with: `pip install -r requirements.txt` (if the file exists).

---

再次感谢你为 ENlearning Assistant 做出的贡献！ 🎉

Thank you again for contributing to ENlearning Assistant! 🎉
