# write-delicate-letters

一个用于创作、改写和打磨中文私人书信的 Codex skill。它把零散回忆、语音式素材和粗糙初稿，整理成具体、克制、有余韵，同时保留收信人自由的原创书信。

## 能做什么

- 为情书、感谢信、道歉信、告别信、安慰信和纪念信提取真实细节。
- 在风格未定时提供三条与场景匹配的 A/B/C 路线。
- 支持赤诚直给、含蓄映照、深情思辨三大风格族与九个原创变体。
- 支持 grounded、hybrid、lyrical 三种文学密度。
- 通过“郑重成章”把高度口语化的日记或语音素材改成看得出认真准备过的信。
- 避免套话、作者模仿、虚构共同经历和以温柔施压。

## 安装

把本仓库复制到 Codex skills 目录：

```bash
git clone https://github.com/kevinguo0351/write-delicate-letters.git ~/.codex/skills/write-delicate-letters
```

然后在 Codex 中调用：

```text
$write-delicate-letters
```

## 使用示例

```text
用 $write-delicate-letters 把下面的语音素材写成一封真诚但不口语化的信。
先给我三条路线；我选择后再写全文。
```

如果已经确定风格，可以直接指定：

```text
用“清醒自白 × 山水留白 × 郑重成章”直接写。
```

## 隐私与原创性

本仓库只包含通用写作规则和原创示例，不包含用于分析该 skill 的私人信件、OCR 原文或个人关系材料。对在世创作者只提炼高层写作机制，不提供风格克隆。

## 结构

- `SKILL.md`：触发条件与核心工作流。
- `agents/openai.yaml`：Codex 展示元数据。
- `references/style-library.md`：三大风格族与九个变体。
- `references/style-patterns.md`：细腻写作与 anti-AI 修订 rubric。
- `references/prepared-sincerity.md`：“郑重成章”转换规则。
- `references/examples.md`：原创 few-shot 示例。
