# 部署说明 · inSnap 作品集

这是一个**纯静态网站**，可直接部署。整个 `site/` 文件夹就是要发布的内容。

## 目录结构
- `index.html` — 站点主文件（已自包含，无外部依赖）
- `assets/` — 所有图片、动画放这里（已按模块归档）
  - `create/` — 「创建 Create」动效素材+图标（含 Catherine 切图）
  - `live/` — 「实时 Live」动效素材+图标（含 Catherine 切图）
  - `chat-unlock/` — 「聊天解锁」动效素材（bg/burst/stars/reward）
  - `brand/` — Momoso logo（Momoso_white / MOMOSO_icon）
  - `shared/` — 共用动画（loading-loop.webm）
  - `Paywall/` — wk04 付费墙轮播图 ×3（已就位 ✓）
  - `First round onboarding/01–05/` — 首轮引导五场景设计稿 + 站点用 webp（ob*-*.webp 为生成切片，勿删）
  - 根目录 — 内容图（momoso-cover / momoso-overview）+ 下方待补图直接丢根目录

## 待补图片（按文件名放进 assets/ 即可，名字别改）
共 23 张，放进去刷新就显示，没放的会自动隐藏占位框：

- contact-1.png
- contact-2.png
- contact-3.png
- contact-4.png
- contact-5.png
- contact-6.png
- momoso-create-01-left.png
- momoso-create-01-right.png
- momoso-create-02-left.png
- momoso-create-02-right.png
- momoso-create-03-left.png
- momoso-create-03-right.png
- momoso-key-4.png
- momoso-screen-1.png
- momoso-screen-2.png
- me.jpg
- skill-01.png
- skill-02.png
- skill-03.png
- skill-04.png
- skill-05.png
- testi-avatar.jpg

> 建议：图片用 jpg/png/webp，宽度 ≤ 2000px，单张 ≤ 500KB，加载更快。

## 部署（三选一，都免费、几分钟）
1. **Netlify Drop（最简单）**：浏览器打开 app.netlify.com/drop，把整个 `site` 文件夹拖进去 → 立即得到一个网址。
2. **Vercel**：vercel.com 新建项目，Framework 选 "Other"，发布目录指向 `site`。
3. **GitHub Pages**：把 `site` 内容推到仓库，Settings → Pages 选分支即可。

绑自定义域名 + HTTPS 这些平台都一键支持。

## 注意
- 不要把 `network.sketch`（591MB 源文件）或 `reference/` 参考截图放进 `site/`，它们不属于发布内容。
- inSnap 是 18+ 产品；作品集本身是专业中立的案例展示，一般没问题，公开发布时留意所选平台的内容条款。
