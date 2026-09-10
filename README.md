# 从测绘重庆到数字重庆

这是一个课程作业展示网页：用 Leaflet 逐层展示重庆地图、遥感、摄影测量和地理信息内容。项目是纯静态 HTML/CSS/JavaScript，不需要 Node.js、npm、数据库或后端。

## 本地预览

直接打开 `index.html` 可以查看页面。若需要验证地图和外部数据请求，建议在项目目录启动一个本地静态服务器后访问 `index.html`。

## GitHub Pages 发布

仓库发布源应选择：`main` 分支，根目录 `/ (root)`。项目根目录已经包含 `index.html` 和 `leaflet/`，不需要构建命令；`.nojekyll` 用于让 GitHub Pages 按静态文件原样发布。

以后将修改提交并推送到 `main` 后，GitHub Pages 会自动重新发布。发布地址以 GitHub 仓库 Settings → Pages 页面显示的地址为准。

## 小组协作

- `main` 保持为老师可访问的正式版本。
- 较大的修改先从 `main` 创建个人分支，例如 `member-a/update-text`。
- 修改完成后创建 Pull Request，确认页面正常后合并到 `main`。
- 小的文字修改可以直接提交 `main`，但每次提交前应先本地预览。
- 每位成员使用自己的 GitHub 账号，不共享密码或令牌。

发生冲突时，先同步最新的 `main`，保留双方需要的内容，重新预览页面后再提交并更新 Pull Request。

## 重要说明

- 本次部署整理没有修改现有页面、地图逻辑、地图数据、Leaflet 文件或第三方地图地址。
- `index.html` 内含天地图访问 token。公开仓库会使它对所有人可见；如需更换 token，应由项目负责人另行确认后处理。
- 天地图和阿里云 DataV 属于大陆网络资源；Esri、NASA GIBS 等资源可能受跨境线路影响。海外静态托管平台均不能保证中国大陆裸连稳定。
