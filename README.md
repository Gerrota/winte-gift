# 冬将至，我与你｜微信 H5

这是一个纯前端 H5 页面，适合部署到 GitHub Pages，并在微信内通过 HTTPS 链接打开。

## 当前版本包含
- 星空粒子与多层飘雪动画（包含旋转雪晶、细碎雪粒和缓慢飘落）
- 中央雪花点击开启
- 冰霜扩散转场
- 冬日祝福结果页
- 手机竖屏与安全区域适配

## 本地预览
直接用浏览器打开 `index.html` 即可预览。部分浏览器的本地音频行为可能不同。

## 发布到 GitHub Pages
1. 登录 GitHub，创建一个新的 **Public** 仓库，例如 `winter-gift`。
2. 将本项目中的 `index.html`、`assets` 文件夹、`.nojekyll` 和 `README.md` 上传到仓库根目录。
3. 进入仓库 `Settings` → `Pages`。
4. 在 **Build and deployment** 中选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/(root)`，点击 `Save`。
6. 等待 GitHub Pages 部署完成，访问页面上显示的地址，通常形如：
   `https://你的用户名.github.io/winter-gift/`

## 微信内测试
将 Pages 链接发到微信聊天中，用手机微信点击打开，检查：
- 页面是否正常加载
- 雪花按钮是否能进入结果页
- 定制内容是否正常
- 音乐是否在用户点击后播放

注意：GitHub Pages 的中国大陆访问速度和稳定性需要实际测试。若面向大量国内用户正式发布，后续可以迁移到国内 HTTPS 托管。

## 修改默认文案
在 `index.html` 中搜索：
- `冬将至，我与你`
- `立冬已至 平安喜乐 祝你祝我祝我们`
- `WINTER IS COMING ·· YOU AND ME`

也可以直接在页面底部点击“定制内容”进行修改。
