# Ruoling Qi · Personal Homepage

这是一个纯 HTML / CSS / JavaScript 的个人主页，适合直接部署到 GitHub Pages。页面内容根据 [@hiahei](https://github.com/hiahei) 的公开 GitHub 资料整理。

## 本地预览

直接双击 `index.html` 即可预览，也可以在项目目录运行：

```bash
python -m http.server 8000
```

然后打开 <http://localhost:8000>。

## 部署到 GitHub Pages

1. 在 GitHub 创建名为 `hiahei.github.io` 的仓库。
2. 将这几个文件推送到仓库的 `main` 分支：

   ```bash
   git init
   git add .
   git commit -m "build personal homepage"
   git branch -M main
   git remote add origin https://github.com/hiahei/hiahei.github.io.git
   git push -u origin main
   ```

3. 打开仓库的 **Settings → Pages**，选择 `Deploy from a branch`、`main` 和 `/ (root)`，保存。
4. 等待 GitHub Actions 完成后访问 <https://hiahei.github.io>。

页面里的简介、项目链接、头像和邮箱都可以直接在 `index.html` 中修改。

