# Agent 进化指南 · 部署说明

网站是**单文件**（`index.html`，零依赖、离线可用），任何静态托管平台都能直接部署。
下面 4 种方式任选其一，都免费。

---

## 方式一：Netlify Drop（最快，约 1 分钟，推荐）

1. 浏览器打开 https://app.netlify.com/drop
2. 用邮箱 / GitHub / Google 免费注册登录（首次需登录一次）
3. 把 `agent-guide` 文件夹**整个拖进页面**（或单独拖入 index.html）
4. 等待几秒，得到链接：`https://随机名称.netlify.app`
5. 把链接发给别人即可。之后可在 Netlify 后台改站点名称、绑域名。

## 方式二：GitHub Pages（永久免费、可绑定域名）

1. 注册 GitHub 账号（https://github.com/signup）
2. 新建仓库（New repository），名字随意，勾选 Public
3. 进入仓库 → Add file → Upload files → 把 `index.html` 拖进去 → Commit changes
4. 仓库 Settings → Pages → Source 选 `Deploy from a branch` → 分支选 `main` → Save
5. 等 1 分钟，访问 `https://你的用户名.github.io/仓库名/` 即可
   （若仓库名就是 `用户名.github.io`，则直接访问 `https://你的用户名.github.io/`）

## 方式三：tiiny.host（免注册，最省事）

1. 打开 https://tiiny.host
2. 把 `index.html` 拖进上传区，填个名字，点 Upload
3. 得到链接：`https://名字.tiiny.site`（免费版有浏览量限制，适合临时分享）

## 方式四：Vercel（开发者的最爱）

1. 打开 https://vercel.com/new 注册登录
2. 选 "Deploy" → 拖入 `agent-guide` 文件夹 → Deploy
3. 得到 `https://项目名.vercel.app`，支持自动 HTTPS 和自定义域名

---

## 小提示

- 所有平台都自动提供 HTTPS 证书，分享给微信/QQ/邮件里的朋友直接点开即可。
- 想改内容？直接用记事本/VSCode 编辑 `index.html`，改完重新上传覆盖即可。
- 本站为纯前端页面，不含后端，不采集数据，部署无任何配置要求。
