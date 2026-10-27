# 合成大大的我

面向朋友分享的网页游戏。请勿加入导航网站或主动提交搜索引擎。

## GitHub Pages 发布

1. 登录 shinBinever，创建公开仓库，例如 big-me-play。
2. 上传本目录全部文件和 photos 文件夹，index.html 应位于仓库根目录。
3. Settings → Pages → Deploy from a branch → main / (root) → Save。
4. 等待部署成功，以 GitHub 返回的网址为准，再使用手机不开代理测试。

使用免费公开仓库时，照片和源码是公开的。noindex 和 robots.txt 只是搜索引擎约定，不是访问控制。

## 当前迁移范围

游戏、照片、昵称、两个模式和本机最高分已支持纯静态部署。全站排行榜的原服务使用 chatgpt.site，无法满足当前访问要求，因此该部署包明确显示“排行榜迁移中”，不会调用旧入口或显示伪造排名。待新服务验证后填写 config.js 的 BIGME_SCORE_API；服务必须正确限制来源和支持跨域请求。
