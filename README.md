# 灵犀AI - 电商智能助理平台

这是一个现代化的单页前端项目，展示电商AI助理的核心功能。

## 快速部署到 GitHub Pages

### 1. 准备 GitHub 仓库
1. 访问 https://github.com/new
2. 仓库名填：`ecommerce-ai-frontend`（或任意名称）
3. 选择 **Public**（公开仓库，免费Pages）
4. 不要勾选 "Initialize this repository with a README"
5. 点击 "Create repository"

### 2. 上传文件
两种方式选其一：

#### 方式A：网页直接上传（推荐）
- 进入刚创建的仓库页面
- 点击绿色按钮 "Add file" → "Upload files"
- 拖拽整个 `E:\openclaw\ecommerce-ai-frontend\` 文件夹内容到浏览器
- 点击 "Commit changes"

#### 方式B：Git 命令行（适合有Git经验）
```bash
cd E:\openclaw\ecommerce-ai-frontend
git init
git remote add origin https://github.com/你的用户名/ecommerce-ai-frontend.git
git add .
git commit -m "Initial commit - 灵犀AI前端页面"
git branch -M main
git push -u origin main
```

### 3. 开启 GitHub Pages
1. 进入仓库 Settings
2. 左侧点击 "Pages"
3. Build and deployment 下方：
   - Source: 选择 `Deploy from a branch`
   - Branch: 选择 `main` 分支，文件夹 `/root` (或 `/ (root)`)
4. 点击 "Save"

### 4. 获取访问链接
稍等1-2分钟，页面会显示：
```
Your site is published at https://你的用户名.github.io/ecommerce-ai-frontend/
```
把这个链接发给朋友，在微信里直接打开即可！

## 更新页面
修改文件后重复步骤2上传，GitHub Pages会自动重新部署。

## 注意事项
- 必须使用 **Public** 仓库（Private仓库Pages需要付费）
- 微信内必须使用 **https** 链接
- 首次访问可能稍慢（GitHub CDN全球加速）

有问题随时找我！🐱
