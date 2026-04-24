# Dylan · 上悦汇商业主题

Halo 2.0 的商业综合体企业官网主题（上悦汇定制版）。

![Dylan Mall Theme](./screenshot.jpg)

## 主题特性

- **商业定制**：专为上悦汇企业集团定制，适用于商业综合体、地产开发等企业官网。
- **响应式设计**：支持移动端和桌面端，适配各种设备。
- **多语言支持**：内置中文、英文、西班牙语、繁体中文等多语言翻译。
- **自定义页面**：支持四大业务板块详情页、新闻动态、关于我们、联系我们等专用模板。
- **SEO 优化**：内置 SEO 扩展字段，提升搜索引擎排名。
- **插件兼容**：支持 Halo 生态的友情链接、图库、瞬间等插件。

## 使用方式

1. 手动从以下地址下载主题包并在 Console 的主题管理界面安装，安装方式可参考：<https://docs.halo.run/user-guide/themes>

    - https://github.com/your-repo/theme-dylan-mall/releases

2. 如果安装了[应用市场](https://www.halo.run/store/apps/app-VYJbF)插件，可以直接在应用市场中搜索`Dylan Mall`并安装。

## 插件支持

Dylan · 上悦汇商业主题支持以下 Halo 插件：

- 友情链接（/links）：<https://www.halo.run/store/apps/app-hfbQg>
- 图库（/photos）：<https://www.halo.run/store/apps/app-BmQJW>
- 瞬间（/moments）：<https://www.halo.run/store/apps/app-SnwWD>

为了获得更好的体验，你还可以安装以下插件（如果需要）：

- Shiki 代码高亮：<https://www.halo.run/store/apps/app-kzloktzn>
- lightgallery.js 灯箱：<https://www.halo.run/store/apps/app-OoggD>

## 自定义模板

主题提供以下专用页面模板：

- **核心业务**：四大业务板块详情页
- **新闻动态**：文章列表，支持分类/标签/分页
- **关于我们**：集团简介、发展历程、大湾区布局
- **联系我们**：联系方式与合作咨询表单

## 开发

```bash
git clone git@github.com:your-repo/theme-dylan-mall.git ~/halo2-dev/themes/theme-dylan-mall
```

```bash
cd ~/halo2-dev/themes/theme-dylan-mall
```

```bash
pnpm install
```

```bash
pnpm dev
```

主题开发文档可查阅：<https://docs.halo.run/developer-guide/theme/prepare>

## 构建

```bash
pnpm build
```

然后将 `dist` 目录的 `ZIP` 格式压缩包在 Halo 后台上传安装即可。

## 版本要求

- Halo >= 2.22.0
- 主题版本：2.1.0

## 作者

Dylan - https://your-domain.com

## 许可证

GPL-3.0
