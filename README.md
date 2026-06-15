# Docker Command Tool

本地可视化 Docker 命令生成器。填写镜像、容器、registry、tag、端口、volume、network、compose service 等字段后，选择分类和命令按钮，即可生成可复制运行的完整命令。

## 启动

直接双击打开：

```text
index.html
```

也可以在浏览器打开：

```text
/Users/yangjinbin/workspace/workspace/docker-command-tool/index.html
```

## 功能

- 按 Docker 官方 CLI reference 组织常用分类：镜像、容器运行、日志/调试、Registry 发布、构建/Buildx、Compose、网络/卷、系统清理、安全/元数据。
- 支持 119 条 `docker image/container/debug/buildx/compose/network/volume/system/scout/manifest/context` 等常用命令。
- 每个命令包含完整解释、真实命令行参数说明、页面输入字段说明、排查提示和官方文档链接。
- 命令按钮可拖拽排序，排序保存在浏览器 `localStorage`。
- 内置拉取工具镜像调试、构建并推送镜像、tag 发布、容器日志排查、网络连通性、磁盘清理、Compose 本地联调等排查流程。

## 文档来源

主要依据 Docker 官方 CLI reference：

https://docs.docker.com/reference/cli/docker/
