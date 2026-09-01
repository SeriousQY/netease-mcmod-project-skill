# netease-mcmod-project

网易 Minecraft 中国版 ModSDK / MCMod 项目开发规范 skill。

## 内容

- 自动识别行为包与资源包项目结构
- 规范新增脚本、item 与资源文件的目录隔离
- 统一 `qyMMDD` 中文代码块注释标记
- 检查两个 `pack_manifest.json` 的 `format_version: 2`
- 清理 `.pyc` 与 `__pycache__` 残留
- 隔离目录外的必要修改必须先获得用户批准

## 安装

将 `SKILL.md` 和 `agents/openai.yaml` 放入 Codex skills 目录下的 `netease-mcmod-project` 文件夹。

Windows 默认路径：

```text
%USERPROFILE%\\.codex\\skills\\netease-mcmod-project
```

Linux/macOS 默认路径：

```text
~/.codex/skills/netease-mcmod-project
```

## 说明

本 skill 面向网易 MCMod 双包项目，不适用于普通 Minecraft 项目。严格 JSON 不添加非法注释或字段；网易 API、事件名和资源标识符保持原始大小写。
