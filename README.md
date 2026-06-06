# Egg Egg 产品展示静态网站

这是完整的静态网站目录，可直接部署到 GitHub Pages、Netlify、Vercel 或任意静态服务器。

## 文件说明

- `index.html`：网站首页
- `ray_dash_final_clean_chinese_4col_assets/`：全部图片资源
- `robots.txt`：允许搜索引擎抓取
- `sitemap.xml`：站点地图模板
- `.nojekyll`：GitHub Pages 静态资源兼容文件

## 部署到 GitHub Pages

1. 新建公开 GitHub 仓库。
2. 上传本文件夹内的全部内容到仓库根目录。
3. 进入仓库 `Settings` -> `Pages`。
4. Source 选择 `Deploy from a branch`。
5. Branch 选择 `main`，Folder 选择 `/root`。
6. 保存后等待 GitHub Pages 生成网址。

## 让搜索引擎收录

1. 网站公开后，把 `sitemap.xml` 里的 `https://example.com/` 改成真实网址。
2. 在 `index.html` 中补充真实网址的 canonical 链接。
3. 到 Google Search Console 或 Bing Webmaster Tools 提交网站和 sitemap。

图片仅供参考，文字介绍均为 AI 生成，禁止私下交易。
