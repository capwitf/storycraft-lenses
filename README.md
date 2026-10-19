# 创作透镜 | Writing Lenses

[简体中文](#简体中文) | [English](#english)

面向 AI 辅助小说创作的两个 Codex skills：一个负责商业连载节奏，一个提供写作表达分析透镜。

Two Codex skills for AI-assisted fiction writing: one focuses on commercial serial pacing, and the other provides an analytical writing lens.

## 简体中文

### 包含内容

- [商业连载透镜](商业连载透镜-skill/SKILL.md)：围绕期待线、阶段兑现、冲突代价与章节钩子组织连载节奏。
- [余华创作透镜](余华创作透镜-skill/SKILL.md)：以研究整理出的表达规则辅助分析和创作，并明确禁止复现原句、专有装置及整套作品元素。

两个透镜分层运行：商业连载透镜提供节奏底盘，表达透镜提供可选的表达建议；建议不写回为已确认的故事事实。

### 安装与使用

将需要的 skill 文件夹复制到 Codex skills 目录：

```text
商业连载透镜-skill/
余华创作透镜-skill/
```

在 Codex 中引用对应的 `SKILL.md`，或按你的创作工作流集成其 `runtime.manifest.json`。具体运行时集成方式取决于宿主项目。

### 许可

本仓库采用 [MIT License](LICENSE)。

## English

### What's Included

- [Commercial Serial Lens](商业连载透镜-skill/SKILL.md): structures serial pacing around reader expectations, payoffs, conflict costs, and chapter hooks.
- [Yu Hua Writing Lens](余华创作透镜-skill/SKILL.md): applies analytical writing principles and explicitly prohibits reproducing original sentences, signature devices, or complete work elements.

The lenses operate in layers: the commercial lens provides pacing rules, while the expression lens offers optional guidance. Suggestions are not written back as confirmed story facts.

### Installation and Usage

Copy the skill folders you need into your Codex skills directory:

```text
商业连载透镜-skill/
余华创作透镜-skill/
```

Reference the corresponding `SKILL.md` in Codex, or integrate its `runtime.manifest.json` into your writing workflow. Runtime integration depends on the host project.

### License

This repository is licensed under the [MIT License](LICENSE).
