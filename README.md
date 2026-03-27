# 使用教程

## 环境要求

在开始之前，请确保你的 Linux 服务器已安装以下软件：

- [Docker](https://www.docker.com/)
- Docker Compose

## 部署步骤

### 1. 克隆项目代码

```bash
git clone https://github.com/xxy5503/dnsconfigui.git
````

### 2. 进入项目目录并启动服务

```bash
cd dnsconfigui && docker compose up -d
```

## 访问系统

服务启动完成后，在浏览器中打开以下地址：

```text
http://$hostip
```

其中 `$hostip` 为当前服务器的 IP 地址。

## 配置说明

进入页面后，即可根据实际需求进行相关配置。
`
