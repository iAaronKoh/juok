# 剧OK - Vercel 部署版

## 部署步骤

### 1. 安装 Vercel CLI
```bash
npm install -g vercel
```

### 2. 登录 Vercel
```bash
vercel login
```

### 3. 部署
```bash
cd juok-vercel
vercel --prod
```

### 4. 或推送到 GitHub 自动部署
1. 在 GitHub 创建仓库
2. 推送代码
3. Vercel 导入 GitHub 仓库
4. 一键部署

## 接口

- `GET /api/parse?url=xxx&line=S` - 代理解析视频

## 技术栈

- 前端: 纯 HTML/CSS/JS
- 后端: Vercel Serverless Functions (Node.js)
