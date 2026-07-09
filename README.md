# Ecliptica Wiki 中文版

这是 EdgeOne Makers 部署用的静态站根目录。

部署配置：

- 构建命令：留空
- 输出目录：`.`
- 入口文件：`index.html`

更新流程：

1. 在主工程重新生成 `wiki_dump/ecliptica_zh/site`。
2. 将 `site` 目录内容同步到本目录根目录。
3. 提交并推送到 Git 仓库。
4. EdgeOne 关联 Git 后会自动重新部署。

版本时间戳见 `wiki_version_manifest.json`。
