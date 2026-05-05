# 工作计划

一个简洁美观的工作计划待办清单网页，支持昼夜主题切换。

## 功能

- ✅ 添加/删除/标记完成任务
- 🔄 拖拽排序
- 🏷️ 优先级标记（高/中/低）
- 🌓 白天/黑夜主题切换（自动保存偏好）
- 💾 数据保存在浏览器本地
- 📱 响应式设计，手机电脑均可使用

## 部署到 GitHub Pages（全球可访问）

### 方式一：GitHub 网页端（无需安装 Git）

1. 在浏览器中登录 [GitHub](https://github.com)
2. 点击右上角 `+` → **New repository**
3. 仓库名填 `work-plan`，选择 **Public**，点击 **Create repository**
4. 在仓库页面，点击 **Add file** → **Upload files**
5. 将 `index.html` 文件拖拽上传
6. 点击 **Commit changes**
7. 进入 **Settings** → **Pages**
8. 在 **Branch** 下拉选择 `main`，根目录选 `/ (root)`，点击 **Save**
9. 等待 1-2 分钟，你的页面就会出现在 `https://你的用户名.github.io/work-plan/`

### 方式二：使用 Git 命令行

```bash
# 安装 Git 后运行：
cd C:\Users\hhsun\work-plan
git init
git add index.html
git commit -m "Initial commit"
git remote add origin https://github.com/你的用户名/work-plan.git
git push -u origin main
```

然后在 GitHub 仓库的 **Settings** → **Pages** 中启用即可。

## 本地使用

直接用浏览器打开 `index.html` 即可使用，无需任何服务端。
