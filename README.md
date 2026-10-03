# 海岸行动隐私政策

Android 游戏《海岸行动》（包名 `com.beach.operations`）的中文隐私政策网页。

- 开发者 / 运营者：himawalqam（个人开发者）
- 联系邮箱：kmhuixing@163.com
- 页面文件：根目录 `index.html`，UTF-8 编码，兼容手机浏览，无外部样式、字体或统计脚本。
- 内容依据：当前 Beach-Tank Android 游戏代码、构建权限及 TapADN 5.3.0.1 的官方隐私说明。

## 开启 GitHub Pages

1. 打开仓库 **Settings → Pages**。
2. **Source** 选择 **Deploy from a branch**。
3. **Branch** 选择 **main**，目录选择 **/(root)**，点击 **Save**。
4. 等待部署完成（GitHub 文档说明可能需要约 10 分钟），用手机打开：
   <https://himawalqam.github.io/beach-tank-privacy/>
5. 确认显示的是《海岸行动》隐私政策，邮箱与开发者名称正确，SDK 政策链接可打开。

官方操作说明：<https://docs.github.com/zh/pages/quickstart>。

网页部署成功并可通过 HTTPS 访问后，才将该 URL 填入 Unity 的
`Assets/Resources/BeachAds.asset` 的 `privacyPolicyUrl`，并按测试流程启用 Android 激励视频。
仓库地址、GitHub 源代码文件页面和未部署成功的链接不能替代实际隐私页面。

## 维护说明

新增联网功能、账号、第三方 SDK 或修改权限、广告授权方式后，请同步更新正文和日期。
当前广告仅在玩家主动选择并同意后请求，包含“支持作者”和符合条件的“额外救援”，不包含开屏广告。
当前广告同意仅在会话中保存；页面如实说明了会话内尚无单独撤回开关，以及退出重启后拒绝的方法。
不在此公开仓库保存广告媒体密钥、签名文件、SDK 配置资产或任何玩家数据。

参考文档：

- [TapADN 隐私政策](https://ssp.dirichlet.cn/docs/agreement/)
- [TapADN 合规使用说明](https://ssp.dirichlet.cn/docs/compliance/)
- [GitHub 隐私声明](https://docs.github.com/zh/site-policy/privacy-policies/github-general-privacy-statement)
