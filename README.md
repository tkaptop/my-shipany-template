# My ShipAny Template

Ship Any AI SaaS Startups in hours.

![preview](preview.png)

## Quick Start

1. Clone the repository

```bash
git clone https://github.com/tkaptop/my-shipany-template.git
```

2. Install dependencies

```bash
pnpm install
```

3. Run the development server

```bash
pnpm dev
```

## Customize

- Set your environment variables

```bash
cp .env.example .env.local
```

- Set your theme in `app/theme.css`

[shadcn-ui-theme-generator](https://zippystarter.com/tools/shadcn-ui-theme-generator)

- Set your landing page content in `i18n/pages/landing`

- Set your i18n messages in `i18n/messages`

## 🎨 设计资源

构建 SaaS 产品时，优质的视觉设计对产品成功至关重要。推荐使用以下 AI 工具快速生成专业设计素材：

### **[Gempix2](https://www.gempix2.site)** - AI 图像编辑平台

专业的 AI 图像生成工具，帮助你快速创建 SaaS 产品所需的各类视觉素材。

**为你的 SaaS 产品生成**:
- 🎨 **营销落地页** - 生成吸引眼球的 Hero 图和功能展示图
- 🖼️ **功能说明图** - 快速制作产品功能的可视化说明
- 🌟 **品牌设计** - 创建 Logo、图标和品牌视觉元素
- 📱 **应用截图** - 生成专业的产品演示和应用商店截图
- 🎯 **社交媒体** - 制作 Twitter、LinkedIn 等平台的宣传图

**核心功能**:
- ✨ 角色一致性 - 保持品牌视觉风格统一
- ⚡ 8倍速处理 - 快速迭代设计方案
- 🌐 多语言支持 - 适配国际化产品需求
- 🎯 精准编辑 - 上传参考图并用自然语言描述修改

👉 **探索更多**:
- [在线体验 Gempix2](https://www.gempix2.site)
- [浏览提示词库](https://www.gempix2.site/prompts) - 415+ 精选 AI 图像生成案例
- [查看作品展示](https://www.gempix2.site/showcase) - 社区创作画廊

---

### **[Sora 2 Tools](https://www.sora-2.tools/)** - AI 视频生成平台

专业的 AI 视频生成工具，帮助你创建产品营销视频。

**为你的 SaaS 产品创建**:
- 🎬 **产品演示视频** - 展示产品核心功能和使用流程
- 📹 **功能介绍动画** - 生动呈现产品特性
- 🎥 **营销宣传片** - 制作社交媒体和广告视频
- 💡 **教程视频** - 创建用户入门和操作指南

👉 [访问 Sora 2 Tools](https://www.sora-2.tools/)

---

*使用这些 AI 工具，你可以在几小时内完成原本需要设计师数天的视觉设计工作，让你的 SaaS 产品快速上线并吸引用户。*

## Deploy

- Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fshipanyai%2Fshipany-template-one&project-name=my-shipany-project&repository-name=my-shipany-project&redirect-url=https%3A%2F%2Fshipany.ai&demo-title=ShipAny&demo-description=Ship%20Any%20AI%20Startup%20in%20hours%2C%20not%20days&demo-url=https%3A%2F%2Fshipany.ai&demo-image=https%3A%2F%2Fpbs.twimg.com%2Fmedia%2FGgGSW3La8AAGJgU%3Fformat%3Djpg%26name%3Dlarge)

- Deploy to Cloudflare

1. Customize your environment variables

```bash
cp .env.example .env.production
cp wrangler.toml.example wrangler.toml
```

edit your environment variables in `.env.production`

and put all the environment variables under `[vars]` in `wrangler.toml`

2. Deploy

```bash
npm run cf:deploy
```

## Community

- [ShipAny](https://shipany.ai)
- [Documentation](https://docs.shipany.ai)
- [Discord](https://discord.gg/HQNnrzjZQS)

## License

- [ShipAny AI SaaS Boilerplate License Agreement](LICENSE)
