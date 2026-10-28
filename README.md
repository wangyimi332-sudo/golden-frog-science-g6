# California Science G6

本地完整版；尚未发布到公网。全册 28 课开放，包含分类、证据判断、句子拼接、写作、亲子档案及间隔复习。

## 发布

1. 新建 GitHub 仓库，默认分支 main。
2. 将本目录内所有文件上传仓库根目录，包括隐藏目录 .github。不要只上传 ZIP 文件。
3. Settings → Pages → Source 选择 GitHub Actions。
4. 在 Actions 运行 Publish website，等待成功，再使用 Pages 显示的正式网址。
5. 用手机无痕窗口验证首页、课程、图片和音频，然后更新项目集文档。

本包已经编译，无需在 GitHub 安装 Node。仓库可见性与账户方案须支持 Pages。正式托管与本地电脑是否开机无关。

源码在项目的 site/src。学习数据只保存在当前浏览器和网址；换网址或设备前导出 JSON。开放写作由学习者自检，不提供自动评分。音频为 Kokoro Heart AI 配音；图像为 AI 情境示意，不作精确测量。

工作流参考：https://github.com/actions/starter-workflows/blob/main/pages/static.yml
