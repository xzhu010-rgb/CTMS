# CTMS 中心启动流程全景

`index.html` 为可离线打开的交互式流程图，包含48个WBS工作项、32项Readiness核查及九项细则，不含具体医院及人员实例。

## 网页部署

1. 在仓库 **Settings → Pages → Build and deployment → Source** 选择 **GitHub Actions**。
2. 在 **Actions → Deploy CTMS to GitHub Pages → Run workflow** 中选择 `main` 并运行。
3. 部署成功后，通过工作流的 `github-pages` 环境链接访问网页。

预期地址：<https://xzhu010-rgb.github.io/CTMS/>。以成功部署输出为准。

后续向 `main` 推送修改会自动部署。工作流只发布 `index.html`，不上传原始Excel或其他仓库文件。

GitHub Pages默认提供网站访问，不等同于仓库访问权限；如需要限定访问者，应先确认账号计划及访问控制能力。
