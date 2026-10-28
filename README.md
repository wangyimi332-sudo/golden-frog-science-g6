# California Science G6

California Science Grade 6 把科学英语学习推进到“阅读一份研究报道，再检验它的证据”。七章从生态系统与食物网出发，考察陆地和水域中的生物如何相互依存；随后研究热与波、太阳能怎样驱动地球表面过程、板块运动留下的地质证据，以及河流和海岸如何改变地貌，最后比较能源与材料的使用选择。孩子会面对有条件的模拟数据和不同立场：例如比较两次河流输沙试验，解释曲流、牛轭湖与三角洲的形成，再思考改变河道会影响哪些人和栖息地。课程要求把观察、数据、因果解释和模型局限连成英文论证，并在每章的人文阅读中讨论科学证据与公共选择的关系。

## 学习方式

全册28课开放。每课以英文阅读为主，中文小字辅助理解，包含可探索的主题图、科学词卡、分类操作、证据判断、句子拼接、主张—证据—推理写作和螺旋复习。每章另有原创科学与社会阅读，英文文章使用预录 AI 配音。孩子与家长各有独立本地档案，可导出备份。

## 当前状态

完整网站已上传到 GitHub 仓库：https://github.com/wangyimi332-sudo/golden-frog-science-g6 。GitHub Pages 尚需在仓库 Settings → Pages 中首次启用，课程网址启用前请勿作为正式入口。

## 发布

1. 新建 GitHub 仓库，默认分支 main。
2. 将本目录内所有文件上传仓库根目录，包括隐藏目录 .github。不要只上传 ZIP 文件。
3. Settings → Pages → Source 选择 GitHub Actions。
4. 在 Actions 运行 Publish website，等待成功，再使用 Pages 显示的正式网址。
5. 用手机无痕窗口验证首页、课程、图片和音频，然后更新项目集文档。

本包已经编译，无需在 GitHub 安装 Node。仓库可见性与账户方案须支持 Pages。正式托管与本地电脑是否开机无关。

源码在项目的 site/src。学习数据只保存在当前浏览器和网址；换网址或设备前导出 JSON。开放写作由学习者自检，不提供自动评分。音频为 Kokoro Heart AI 配音；图像为 AI 情境示意，不作精确测量。

工作流参考：https://github.com/actions/starter-workflows/blob/main/pages/static.yml

