# 贡献指南（CONTRIBUTING）

感谢你关注本书！无论是勘误、补充案例还是翻译，都欢迎参与。

## 📌 三种参与方式

### 1. 报错 / 勘误（最欢迎）
- 开 Issue，标题格式：`[勘误][第 N 章] 简述问题`
- 请附上：章节文件路径、原文片段、修改建议、出处依据（如有）

### 2. 内容贡献
适合较长内容（新案例、新小节、一线故事）：
1. Fork → 新建分支 `content/ch05-add-case`
2. 修改对应章节文件，遵守 [docs/writing-style.md](./docs/writing-style.md) 写作规范
3. 提交 PR，标题格式：`[第 N 章] 改动简述`
4. 请勿一次性改动多个章节，每个 PR 聚焦一个主题

### 3. 一线故事分享
欢迎在职 FDE / AI 交付工程师分享真实经历：
- 投稿格式：场景 → 冲突 → 处理 → 结果 → 一句话复盘
- 可选择匿名；涉及客户信息请先脱敏（公司名、数据、人名）
- 提交到 `chapters/*/stories/` 目录，命名为 `story-YYYYMMDD-主题.md`

## ✅ 写作规范要点（详见 docs/writing-style.md）

- 每章结构固定：开篇导读 → 正文 → 知识点卡 → 章末习题 → 参考资料
- 技术术语首次出现给英文原文，如"部署鸿沟（deployment gap）"
- 数据与案例必须注明公开出处，禁止编造
- 代码必须可运行：注明依赖版本与运行命令，示例放 `examples/`

## ⚠️ 版权注意

- 引用外部文章/书籍：单段引用 ≤ 200 字，注明来源与链接
- 引用开源代码：遵守其 LICENSE，注明来源
- 禁止搬运付费课程、内部培训材料内容

## 🗂️ 仓库结构

```
fde-book/
├── README.md            # 项目主页
├── SUMMARY.md           # 目录与进度
├── CONTRIBUTING.md      # 本文件
├── LICENSE              # 代码 MIT / 正文 CC BY-NC-SA 4.0
├── chapters/            # 正文（按篇分目录）
│   ├── part-01-cognition/    # 认知篇
│   ├── part-02-tech/        # 技术篇
│   ├── part-03-methodology/ # 方法论篇
│   ├── part-04-projects/    # 实战篇
│   └── part-05-growth/      # 成长篇
├── examples/            # 可运行代码示例（每章子目录）
├── assets/              # 图片等资源
└── docs/                # 写作规范等元文档
```
