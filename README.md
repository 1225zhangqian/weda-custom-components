# 微搭低代码自定义组件示例

- [项目介绍](#项目介绍)
- [组件列表](#组件列表)
- [使用指南](#使用指南)
- [贡献指南](#贡献指南)

## 项目介绍

[腾讯云微搭低代码]平台支持自定义组件的方式来开发应用，支持引入第三方开源组件、集成已有代码等。

本项目是腾讯云微搭低代码平台的自定义组件示例仓库，帮助开发者了解如何开发自定义组件，从而更好地搭建更加丰富的低代码应用。

## 组件列表

| 组件   | 介绍                            |
| ------ | ------------------------------- |
| Button | 支持小程序和 web 的多端组件示例 |

## 使用指南

### 前置依赖

1.  确保拥有腾讯云账号、开通微搭低代码；
2.  确保本地安装  [Node.js](https://nodejs.org/en/)
3.  在微搭平台中[新建一个组件库](https://docs.cloudbase.net/lowcode/custom-components/quick-start/comps) ，组件库标识使用`weda_custom_components`

### 快速开始

下载代码并进入项目根目录，执行以下命令

```bash
npm install
npm install -g @cloudbase/cli
tcb login
tcb lowcode debug
```

### 开发工作流

#### 调试

```bash
tcb lowcode debug
```

打开微搭编辑器调试本地组件

#### 检查

```bash
npm run lint
```

代码风格检查

#### 发布

```bash
tcb lowcode publish
```

上传组件代码到账号下,上传完毕后，可以在微搭平台发布组件库，即可在应用中使用

## 贡献指南

如果您想要为这个项目做出贡献，可以参考以下步骤：

1. Fork 这个仓库
2. 创建一个新的分支
3. 提交您的更改
4. 创建一个 Pull Request

## 许可证

开源协议文档请参阅  [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)