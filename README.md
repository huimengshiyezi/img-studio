# 生图工作台（img-studio）

> 单文件、纯本地的 AI 生图工作台：左边写提示词 + 放参考图，右边画布即时预览，自带资产库。

![license](https://img.shields.io/badge/license-MIT-blue) ![single file](https://img.shields.io/badge/single--file-yes-brightgreen) ![dependencies](https://img.shields.io/badge/dependencies-0-brightgreen)

## 它是什么

一个 HTML 文件 —— 双击就能用：不需要安装、不需要构建、**不上传任何文件**。

- **左侧**：提示词区（可写长文，一眼看到整段）＋ 参考图区（选文件 / 拖进来 / Ctrl+V 粘贴）＋ 一排参数（模型 ｜ 比例·分辨率·数量 ｜ 生成键）
- **右侧**：画布。图再大也整张完整可见，不裁切
- **顶栏 `📚 资产`**：全屏资产库 —— 每张图带提示词、模型、像素尺寸、尺寸写法、张数、参考图缩略图、耗时、用量、存到哪；支持模型筛选 / 关键词搜索 / 排序 / 按日期分组 / 扫描文件夹重建索引

## 怎么用

1. 用 Chrome 或 Edge 打开 `生图工作台.html`（双击即可）
2. 在配置里填**你自己的**接口地址与 API Key（只存在本机浏览器中，不会上传）
   —— 页面**不预置任何网关/站点**，也不含任何示例域名；填一次后会按你填的地址记住
3. 选一个保存文件夹 → 写提示词 → 点生成

## 隐私

- 纯前端：没有后端、没有统计、没有埋点，图片与提示词都不出本机
- API Key 仅保存在本机浏览器存储里；**本仓库不含任何密钥**
- 生成的图与同名 `.json` 说明只写到你选定的本地文件夹

## 浏览器要求

Chrome / Edge 等 Chromium 内核浏览器（使用 File System Access API 与 IndexedDB）

## 关于本仓库

只含工具本体（`生图工作台.html`）。回归测试脚本、诊断报告等内部产物不在仓库内。

## 许可

MIT © huimengshiyezi (AI绘梦师葉子)
