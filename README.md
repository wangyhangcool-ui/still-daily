# Still · 静

一个本地优先的每日记录 PWA，面向手机屏幕设计。

## 功能
- 每日状态：今天有 / 今天没有 / 跳过记录
- 心情、触发因素、做得不错的事、反思、给明天的话
- 按日期查看、编辑日历记录
- 记录天数统计、最近反思
- JSON 备份导出与导入
- LocalStorage 本地保存；不主动上传记录
- PWA manifest 与 Service Worker，部署到 HTTPS 后可添加到主屏幕

## 部署
这是静态网页。将本目录文件提交到 GitHub 仓库根目录，然后在仓库 Settings → Pages 选择从 `main` 分支的 `/ (root)` 部署。等待 GitHub Pages 给出站点地址后，在 iPhone Safari 打开站点，点分享按钮 → 添加到主屏幕。

## 隐私与限制
记录存在当前浏览器的 LocalStorage。清除浏览器网站数据、换设备或使用不同浏览器可能无法访问原记录。请定期导出 JSON 备份。Service Worker 只缓存静态页面，不会上传个人记录。

## 当前状态
此压缩包已生成，但当前 ChatGPT GitHub 集成对仓库写入请求返回 403，因此尚未自动提交到 `wangyhangcool-ui/still-daily`，也尚未发布到公网。
