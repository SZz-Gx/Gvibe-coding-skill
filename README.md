# Gvibe Coding Skill

> 外包级项目快速交付引擎 — 需求拆解 → GitHub模板匹配 → 拉取初始化 → 定制开发 → 交付验证。融合 Ponytail 七级极简阶梯 + 五步调试闭环，全程自动排错。

## 触发词

`做项目` `解决代码问题` `帮我做一个XX系统`

## 支持的平台

| 平台 | 目录 | 安装路径 |
|------|------|----------|
| **Claude Code** | `claude-code/SKILL.md` | `.claude/skills/vbcoding/SKILL.md` |
| **Codex CLI** | `codex/SKILL.md` | `.codex/skills/vbcoding/SKILL.md` |
| **Reasonix Code** | `reasonix/vbcoding.md` | `.reasonix/skills/vbcoding.md` |

## 安装

### Claude Code

```bash
mkdir -p .claude/skills/vbcoding
cp claude-code/SKILL.md .claude/skills/vbcoding/SKILL.md
```

或全局安装：

```bash
mkdir -p ~/.claude/skills/vbcoding
cp claude-code/SKILL.md ~/.claude/skills/vbcoding/SKILL.md
```

### Codex CLI

```bash
mkdir -p .codex/skills/vbcoding
cp codex/SKILL.md .codex/skills/vbcoding/SKILL.md
```

### Reasonix Code

```bash
mkdir -p .reasonix/skills
cp reasonix/vbcoding.md .reasonix/skills/vbcoding.md
```

## 六阶段工作流

```
📋 Stage 1 → 需求拆解，生成功能清单让用户确认
📋 Stage 2 → GitHub 检索，筛选 5+ 候选模板
📋 Stage 3 → 四维评分，选出最优模板
📋 Stage 4 → git clone + 环境初始化 + 自动排错
📋 Stage 5 → 定制化二次开发（七级极简阶梯 + 五步调试闭环）
📋 Stage 6 → 交付 README_CUSTOM.md + 一键启动
```

## 核心特性

- 🔍 自动解析自然语言需求，推荐最优技术栈
- 📦 GitHub 智能搜索模板（star≥500、MIT/Apache 2.0、近6月活跃）
- 🚀 全自动 git clone + 依赖安装 + 环境配置
- 🪜 **七级极简阶梯**（来自 Ponytail）：YAGNI → 复用现有 → 标准库 → 原生平台 → 已安装依赖 → 一行搞定 → 最少代码
- 🔧 内嵌五步调试闭环：复现→定位根因（grep全部调用方）→修复→验证→防回归
- 🎚️ 三级强度控制：lite（默认）/ full / ultra
- 🇨🇳 国内网络自动 ghproxy 镜像加速
- 📋 标准化交付文档 README_CUSTOM.md

## License

MIT
