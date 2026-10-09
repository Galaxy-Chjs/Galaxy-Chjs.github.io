# Jinshuai Cheng · GitHub 个人主页

纯静态个人主页，无需安装依赖，可直接发布到 GitHub Pages。

## 本地预览

直接双击 `index.html` 即可预览。也可以在 VS Code 中安装 **Live Server** 扩展，然后右键 `index.html` → **Open with Live Server**。

## 内容维护

主要文字和链接位于 `index.html`：

- 研究与项目状态发生变化时，更新 `#projects` 区域。
- 教育、奖励和经历位于 `#experience` 区域。
- 个人照片为 `assets/profile.jpg`。
- 颜色和布局变量位于 `styles.css` 顶部的 `:root`。

> MRG-Router 当前标注为 ICLR 投稿 / under review。正式公开主页前，请根据匿名评审要求确认是否适合展示论文题目与作者身份。

## 发布到 GitHub Pages

1. 在 GitHub 新建公开仓库，仓库名为 `Galaxy-Chjs.github.io`。
2. 在本目录打开终端并执行：

```powershell
git init
git add .
git commit -m "Create personal website"
git branch -M main
git remote add origin https://github.com/Galaxy-Chjs/Galaxy-Chjs.github.io.git
git push -u origin main
```

3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**，分支选 `main`，目录选 `/ (root)`，保存。
5. 等待几分钟后访问 `https://galaxy-chjs.github.io/`。

以后每次更新后运行：

```powershell
git add .
git commit -m "Update website"
git push
```
