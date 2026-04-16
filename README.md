# zhongshengji.vip

这是 `zhongshengji.vip` 的静态官网项目，适合直接部署到 GitHub 和 Vercel。

## 当前文件说明

- `index.html`：官网首页
- `robots.txt`：搜索引擎抓取规则
- `sitemap.xml`：站点地图
- `README.md`：项目说明

## GitHub 上传步骤

1. 登录 GitHub
2. 新建一个仓库，例如：`zhongshengji-vip`
3. 把当前目录内的全部文件上传到仓库根目录
4. 确认仓库里至少有 `index.html`、`robots.txt`、`sitemap.xml`

## Vercel 部署步骤

1. 登录 Vercel
2. 点击 `Add New` → `Project`
3. 导入你的 GitHub 仓库 `zhongshengji-vip`
4. Framework Preset 选择 `Other`
5. Root Directory 保持默认
6. Build Command 留空
7. Output Directory 留空
8. 点击 Deploy

## 绑定域名

1. 在 Vercel 项目后台进入 `Settings` → `Domains`
2. 添加域名：`zhongshengji.vip`
3. 如果需要，再添加 `www.zhongshengji.vip`
4. 按照 Vercel 提示回到 Cloudflare 设置 DNS

## Cloudflare 常见 DNS 做法

### 根域名

- 类型：A 或 CNAME（以 Vercel 指引为准）
- 名称：`@`
- 值：按 Vercel 后台显示填写

### www 子域名

- 类型：CNAME
- 名称：`www`
- 值：按 Vercel 后台显示填写

## 后续建议

下一阶段继续补：

- 什么是种生基（独立页面）
- 适合人群（独立页面）
- 完整流程（独立页面）
- 常见问题 FAQ（独立页面）

