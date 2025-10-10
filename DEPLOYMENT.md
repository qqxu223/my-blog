# 部署指南

## 一键部署

1. 点击 README 中的 "Deploy to Cloudflare Workers" 按钮
2. 登录您的 Cloudflare 账户
3. 授权 GitHub 访问
4. 选择此仓库 (`qqxu223/my-website`)
5. 系统会自动配置并部署

## 环境变量（可选）

如需配置环境变量，在 Cloudflare Dashboard 中：
1. 进入 Workers & Pages
2. 选择您的 Worker
3. 进入 Settings > Variables
4. 添加所需变量

## 自定义域名

部署后可以绑定自定义域名：
1. 进入 Worker 设置
2. 选择 Triggers
3. 添加自定义域名