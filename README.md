# 重庆空瓶记化妆品有限公司官网

纯静态网站（HTML + CSS），无需构建。

## 部署到 GitHub Pages

1. 在 GitHub 新建仓库，例如 `kongpingji-site`。
2. 把本目录文件推送上去：
   ```bash
   git init && git add . && git commit -m "init site"
   git branch -M main
   git remote add origin https://github.com/<你的用户名>/kongpingji-site.git
   git push -u origin main
   ```
3. 仓库 Settings → Pages → Source 选 `Deploy from a branch`，分支选 `main` / `(root)`，保存。
4. 约一分钟后访问 `https://<你的用户名>.github.io/kongpingji-site/`。

## 自定义域名（可选）
在 Pages 设置里填入域名，并在域名服务商处添加 CNAME 记录指向 `<你的用户名>.github.io`。

## 上线前要改的地方
在 `index.html` 里搜索 `TODO`：备案号（如用国内域名）；并确认“合作品牌”已获品牌方同意公开。
