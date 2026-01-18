```markdown
# 在线记事本 (Simple Notepad)

这是一个纯前端的在线记事本项目，功能包括：
- 新建 / 编辑 / 删除笔记
- 自动保存到浏览器 localStorage
- 搜索笔记
- 导出 / 导入 JSON（便于备份和迁移）
- 键盘快捷键��Ctrl+S 保存、Ctrl+N 新建、Ctrl+F 搜索
- 支持深色模式

演示文件：`index.html`, `style.css`, `app.js` —— 无需构建步骤，可直接部署为静态站点。

## 本地使用
1. 将代码放到一个文件夹，例如 `notepad/`。
2. 在浏览器中打开 `index.html`（双击或通过浏览器打开本地文件）。
3. 也可以用任意静态站点服务器（如 `live-server`）运行。

## 部署到 GitHub Pages（自动化）
仓库内包含一个 GitHub Actions workflow（`.github/workflows/deploy.yml`），当你把代码 push 到 `main` 分支时，Actions 会自动把网站部署到 GitHub Pages（使用官方 actions 配置）。

如果要手动设置 Pages：进入仓库 Settings → Pages，选择 Branch: main / Folder: / (root)。

## 导出 / 导入
- 点击“导出”会下载一个 JSON文件，包含所有笔记。
- 点击“导入”并选择正确格式的导出文件，会把导入的笔记合并到当前笔记列表（不覆盖现有笔记）。

## 许可证
MIT
```
