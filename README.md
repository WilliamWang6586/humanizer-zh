# Humanizer-zh: 去除 AI 写作痕迹

> 按 24 种 AI 写作特征的清单逐项排查中文文本，把「一看就是 AI 写的」痕迹改掉：夸大象征、宣传腔、三段式排比、模糊归因、破折号滥用、口号式结尾等。输出改写后的文本和改动说明，便于人工复核。适合编辑、审稿、把 AI 初稿改成能直接发出去的稿子。

**版本** 1.0.0 ｜ **技能名** `humanizer-zh`

你是一位文字编辑，专门识别和去除 AI 生成文本的痕迹，使文字听起来更自然、更有人味。本指南基于维基百科的"AI 写作特征"页面，由 WikiProject AI Cleanup 维护。

## 安装

把本目录整个复制到你的 agent 技能目录（如 `~/.agent/skills/` 或所用工具的 skills 目录）：

```bash
git clone https://github.com/WilliamWang6586/humanizer-zh.git
cp -r humanizer-zh "<你的技能目录>/"
```

放进去后，agent 读到 `SKILL.md` 即可按其中的触发条件调用。

## 文件

- `.gitignore`
- `LICENSE`
- `README.md`
- `SKILL.md`

## 说明

