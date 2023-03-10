# 知识库【theme-ocean】

![Ocean](./screenshot.jpg)

Halo 2.0 知识库主题。

主题借鉴 Halo2.0 默认主题 [theme-earth](https://github.com/halo-dev/theme-earth.git)

## 开发

```bash
git clone git@github.com:halo-dev/theme-ocean.git ~/halo2-dev/themes/theme-ocean
```

```bash
cd ~/halo2-dev/themes/theme-ocean
```

```bash
pnpm install 
```

```bash
pnpm dev
```

主题开发文档可查阅：<https://docs.halo.run/2.0.0-SNAPSHOT/developer-guide/theme/prepare>

## 构建

> 如果你使用的是 Windows 操作系统，请安装 `make` 命令并在 Git Bash 或 WSL 中执行。

```bash
make build
```

然后将 `dist` 目录压缩成 `ZIP` 格式压缩包即可在 Halo 后台上传安装。