# Air Conditioner

云空调，便携小空调，为你的夏日带去清凉！


- 裸机：<http://ac.58dazhe.com>

## Features

### 优势

- 随时随地打开空调
- 便携
- 低功耗（使用 HTML CSS 而非 Canvas 绘制）
- 静音
- 操作简单
- 安装便捷

### 劣势

- 没有风

## 安装

### iframe

```html
<iframe width="100%" height="740" src="http://ac.58dazhe.com"></iframe>
```

您可以快速为您的网站安装空调。


## 自行部署

### Docker

部署时可使用以下环境变量进行配置自定义：

- `AC_NGINX_DOMAIN` 指定域名
- `AC_NGINX_PORT` 指定监听端口

### 腾讯云

基于腾讯开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) [![star](https://img.shields.io/github/stars/Tencent/cloudbase-framework?style=social)](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署

[![腾讯云｜部署到云开发](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FYunYouJun%2Fair-conditioner%2F&branch=master)

## Dev

```bash
# yarn dev
yarn install
yarn start
# http://localhost:3000/

yarn build
# ./build
```

### 环境变量

```bash
cp .env.example .env
```

```bash
# 关闭广告
REACT_APP_DISABLE_ADSENSE=true
```

## Todo

- [x] 空调
  - [x] 能耗标签
  - [x] 温度范围（16-31˚C）
  - [x] 风 css
  - [x] 音效
    - [x] 按钮
    - [x] 工作声
    - [ ] 接入 [喜马拉雅](https://m.ximalaya.com/sleepaudio/6?mixedTrackIds=331526646&utm_source=smxkt) 更多音效
- [x] 适应系统的亮暗模式

## Ref

- 数字字体: [Digital 7](https://www.dafont.com/digital-7.font)，Free for personal use
- 空调工作声: [Air Extractor Fan | freesound](https://freesound.org/people/InspectorJ/sounds/403664/)
