# Black Cat Witch Illustrations

一个用于中文 AI、设计和创作者教程配图的 Codex skill。

它把一个清晰的内容观点转成 16:9 讲解插图，保留稳定的个人 IP：像素化黑猫女巫、灰蓝粉配色，以及清晰的手绘墨线／马克笔环境。

## 适用场景

- 给 Markdown 口播稿、文章或教程拆分配图
- 为 AI 工作流、模型使用、提示词方法生成讲解图
- 生成带有小黑猫女巫 IP 的系列化内容视觉
- 把抽象概念转成一个读者能快速看懂的画面机制

## 在 Codex 中使用

安装到本地 skill 目录后，在对话中调用：

```text
$black-cat-witch-illustrations

请读取我上传的 Markdown 文件，按文章内容拆分 16:9 配图，使用小黑猫女巫的视觉系统生成图片，并返回每张图的用途和保存路径。
```

也可以直接把 Markdown 文件拖进对话，并说明希望生成几张图。

## 安装

```bash
mkdir -p ~/.codex/skills
cp -R black-cat-witch-illustrations ~/.codex/skills/
```

安装后重启 Codex，或重新打开一个对话，让 skill 出现在可用技能中。

## 视觉基准

- 角色：圆润、紧凑的像素黑猫女巫
- 环境：清晰手绘墨线／马克笔线稿，平涂色块，轻微有机变化
- 主色：灰色、深蓝、浅蓝、浅粉、灰粉、深墨色
- 画幅：默认 16:9
- 原则：一张图只讲一个核心观点和一个视觉机制
- 默认不生成图片文字，中文标签留给后期排版

`assets/approved-style-reference.png` 是当前确认的主风格参考。`assets/black-cat-witch-reference.png` 主要用于角色轮廓参考；它是早期版本，不能照搬其中的黄眼睛和暖色调。

## 文件结构

```text
black-cat-witch-illustrations/
├── SKILL.md
├── agents/openai.yaml
├── assets/
│   ├── approved-style-reference.png
│   ├── black-cat-witch-reference.png
│   └── brand-reference.png
└── references/
    ├── black-cat-witch-ip.md
    ├── brand-dna.md
    ├── composition-patterns.md
    ├── prompt-template.md
    └── qa-checklist.md
```

## 许可证

skill 的说明文档和参考文档采用 MIT License。小黑猫个人 IP 和仓库中的视觉素材仅供该 skill 的生成参考，除非另有书面授权，不授予独立使用、再发布或商业改编权。
