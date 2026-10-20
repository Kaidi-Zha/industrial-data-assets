# 工业数据资源与样本库

[浏览网页](https://kaidi-zha.github.io/industrial-data-assets/)

298项登记资源，分为工业软件和结果数据、工业软件工作流数据、现场数据、文本类／代码类数据。目录记录208项可预览资源和2,005条预览，其中136项、1,289条已内置于页面；其余预览按需连接公开接口，可能受网络、跨域与发布方权限影响。90项仅提供来源和获取条件。

预览包含窗口、切片、视图及关联转换版本，不等于独立案例，不代表完整数据或质量验收。来源关系、取样范围与许可线索保留在对应资源中；数据的权利和使用条件以原发布方为准。本仓库未对第三方数据重新授予许可。

审核意见仅保存于访问者当前浏览器，可自行导出，不会提交到GitHub或其他服务。

## 发布与维护

GitHub Pages从main分支的docs目录发布。index.html为完整独立页面，内嵌轻量真实样本；preview-audit.html和preview-audit.csv为可检索、可下载的资源目录。无需构建或安装依赖。源码核查日期：2026-10-18；部署日期：2026-10-20。

页面由本地研究工作区的scripts/build-local.mjs生成，经validate-local.mjs、verify-data-visuals.mjs及validate-snapshots.mjs检查后，由scripts/prepare-github-pages.py导出。本仓库仅保存发布产物，更新时应先修改并验证本地源文件，再同步docs目录。
