
# 模板介绍

| 项目信息       | 详情                                                                                  |
| -------------- | ------------------------------------------------------------------------------------- |
| 原始项目地址   | [ surjithctly/astroship](https://github.com/surjithctly/astroship)                                 |
| 原始项目Stars   | [![GitHub stars](https://img.shields.io/github/stars/surjithctly/astroship?style=social)](https://github.com/surjithctly/astroship/stargazers) |

> 以下是原始项目的 README 内容：

---

# Astroship - Astro SAAS 入门网站模板

Astroship 是一款免费的入门级 astro 网站模板，适用于 saas、初创公司、营销网站、登录页面和博客。使用 Astro 和 TailwindCSS 构建。

此免费模板由 [Web3Templates](https://web3templates.com) 赞助

## 现场演示

**[https://astroship.web3templates.com/](https://astroship.web3templates.com/)**

**[下载 Astroship 模板](https://web3templates.com/templates/astroship-starter-website-template-for-astro)**

## 升级到 Astroship Pro 版本

**[https://astroship-pro.web3templates.com/](https://astroship-pro.web3templates.com/)**

**[购买 Astroship Pro — $49](https://web3templates.com/templates/astroship-pro-astro-saas-website-template)**

<!-- prettier-ignore -->
| 功能 | 免费版本 | 专业版本 |
| --- | ------ | --- |
| Astro v3 | ✅ | ✅ |
|内容集合 | ✅ | ✅ |
| Tailwind CSS | ✅ | ✅ |
| 移动响应 | ✅ | ✅ |
| 工作联系页面 | ✅ | ✅ |
| 专业布局和功能 | ❌ | ✅ |
| 带分页的博客 | ❌ | ✅ |
| 查看转换 | ❌ | ✅ |
| 高级主页设计 | ❌ | ✅ |
| 功能页面 | ❌ | ✅ |
| 集成页面 | ❌ | ✅ |
| 优雅的 404 页面 | ❌ | ✅ |
| 6 个月支持| ❌ | ✅ |
| 免费更新 | ✅ | ✅ |
| 许可证 | GPL-2.0 | 商业 |
| &nbsp; | &nbsp;| &nbsp;|
| 定价| 免费|**49 美元**|
| &nbsp; | [部署免费]（https://vercel.com/new/surjithctly/clone?demo-description=Starter%20template%20for%20startups%2C%20marketing%20websites%20%26%20blogs%20built%20with%20Astro%20and%20TailwindCSS。&demo-image=%2F%2Fimages.ctfassets.net%2Fe5382hct74si%2F5dB0dDqBr1BfvIoNOmffVB%2F784984a8d3fe5e3 db123e7c655166046%2Fastroship_-_Tony_Sullivan.jpg&demo-title=Astroship&demo-url=https%3A%2F%2Fastroship.web3templates.com%2F&from=templates&project-name=Astroship&repository-name=astroship&repository-url=https%3A%2F%2Fgithub.com%2Fsurjithctly%2Fastroship&skippable-integrations=1) | [购买 Pro](https://web3templates.com/templates/astroship-pro-astro-saas-website-template) |

<a href="https://web3templates.com/templates/astroship-pro-astro-saas-website-template">
<img width="160" alt="升级到专业版" src="https://user-images.githubusercontent.com/1884712/199181300-37c2128e-d033-4145-a906-16fa5263a53b.png">
</a>

## 预览

![image](https://user-images.githubusercontent.com/1884712/200831799-10ef2456-a02e-4068-b580-4b5326f0b33b.png)

## 专业版预览

![预览](https://github.com/surjithctly/astroship/assets/1884712/25665c02-d2a7-43dc-89b2-34a8ae37ade9)

### Pagespeed 分数

[![pagespeed](https://user-images.githubusercontent.com/1884712/210250214-7aa98167-7993-4b90-8138-326b8fa0c223.png)](https://pagespeed.web.dev/report?url=https%3A%2F%2Fastroship.web3templates.com%2F)

## 安装

如果您在 github 上阅读此内容，您可以点击上方的“使用此模板”按钮从 astroship 为您的帐户创建一个新的存储库。然后，您可以执行 `git clone` 将其克隆到本地系统。

或者，您可以将项目直接从此存储库克隆到本地系统。

### 1. 克隆存储库

```bash
git clone https://github.com/surjithctly/astroship.git myProjectName
# 或
git clone https://github.com/surjithctly/astroship.git 。
```

`.` 会将其克隆到当前目录，因此请确保您首先位于项目文件夹中。

### 2. 安装依赖项

```bash
npm install
# 或
yarn install
# 或 (推荐)
pnpm install
```

### 3. 启动开发服务器

```bash
npm run dev
# 或
yarn dev
# 或 (推荐)
pnpm dev
```

### 预览和构建

```bash
npm run preview
npm run build
# 或
yarn preview
yarn build
# 或 (推荐)
pnpm preview
pnpm build
```

我们建议使用 [pnpm](https://pnpm.io/) 来节省计算机上的磁盘空间。

### 其他命令

```bash
pnpm astro ...
pnpm astro add
pnpm astro --help
```

## 项目结构

在您的 Astro 项目中，您将看到以下文件夹和文件：

```
/

═── public/
│ └── ...
═── src/
│ ═── components/
│ │ └── ...
│ ═── layouts/
│ │ └── ...
│ └── pages/
│ └── ...
└── package.json
```

Astro 在 `src/pages/` 目录中查找 `.astro` 或 `.md` 文件。每个页面都根据其文件名显示为路由。

任何静态资产（如图像）都可以放在 `public/` 目录中。

## TailwindCSS

TailwindCSS 已在此 repo 中配置，因此您无需任何安装即可开始使用它。

## 致谢

[英雄插图](https://www.figma.com/community/file/1108400791662599811) 作者：[Streamline](https://www.streamlinehq.com/)

## 👀 想了解更多？

欢迎查看 [Astro Docs](https://docs.astro.build) 或进入我们的 [Discord 聊天](https://web3templates.com/discord)。

[![使用 Astro 构建](https://astro.badg.es/v1/built-with-astro.svg)](https://astro.build)
