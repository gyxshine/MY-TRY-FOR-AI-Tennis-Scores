# 网球记分牌

一个专为业余网球玩家设计的记分牌工具，支持普通模式和发球局模式。

## 功能特点

- 🎾 双模式记分：普通模式（0-99）和发球局模式（0/15/30/40/AD/WIN）
- 📱 响应式设计：完美适配手机、iPad 和桌面设备
- 🔄 撤销功能：支持撤销上一步操作
- 🎯 手势操作：向上滑动即可加分
- 🖥️ 全屏模式：横屏全屏显示，比分更大更清晰

## 部署到 Vercel

### 方法一：通过 Vercel CLI

```bash
# 安装 Vercel CLI
npm i -g vercel

# 在项目目录中运行
vercel
```

### 方法二：通过 Vercel 网站

1. 访问 [vercel.com](https://vercel.com)
2. 使用 GitHub/GitLab/Bitbucket 账号登录
3. 点击 "New Project"
4. 导入你的 Git 仓库
5. Vercel 会自动检测并部署

### 方法三：直接拖拽部署

1. 访问 [vercel.com](https://vercel.com)
2. 登录后点击 "Add New..." → "Project"
3. 选择 "Deploy" → "Browse"
4. 选择包含 `index.html` 的文件夹
5. 点击 "Deploy"

## 文件说明

- `index.html` - 主应用文件（包含所有 HTML、CSS 和 JavaScript）
- `vercel.json` - Vercel 部署配置文件
- `preview.html` - 设备预览页面（可选）

## 使用说明

1. 打开网页后，选择"普通模式"或"发球局模式"
2. 点击按钮或向上滑动对应区域来加分
3. 点击"撤销"可以撤销上一步操作
4. 点击"清空"可以重置比分
5. 点击右上角全屏按钮进入全屏模式
