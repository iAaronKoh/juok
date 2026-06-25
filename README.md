# 剧OK - Vercel 部署版

## 部署步骤

### 1. 安装 Vercel CLI
```bash
npm install -g vercel
```

### 2. 登录
```bash
vercel login
```

### 3. 部署
```bash
cd juok-vercel
vercel --prod
```

### 4. 或推送到 GitHub 自动部署
1. GitHub 创建仓库
2. 推送代码
3. Vercel 导入仓库，一键部署

## 接口

- `GET /api/parse?url=xxx&line=S` - 代理解析视频

## 注意

- `api/parse.js` 使用 CommonJS 格式，Vercel 默认支持
- 无需 `vercel.json` 中的 `functions` 字段
