# Meme 生成器 - 项目方案

## 概念

一个简洁的表情包生成器网站，用户选择模板 → 输入文字 → 生成图片并下载。主要靠 AdSense 变现。

## 方案选择

考虑到免费托管（Netlify），纯前端方案：
- **前端**：HTML + CSS + JS（单页面）
- **API**：Imgflip API（免费，无需服务器）
- **托管**：Netlify（免费）

## 功能

1. **模板展示**：网格展示热门表情包模板
2. **文字输入**：选中模板后输入对应文字
3. **预览+下载**：实时预览，下载图片
4. **广告位**：顶部/底部 AdSense

## 核心模板（首批）

- Drake（二选一）
- Two Buttons（选择困难）
- Distracted Boyfriend（三人关系）
- Bernie Asking（重复请求）
- Gru's Plan（计划翻车）
- UNO Draw 25（反抗指令）
- Always Has Been（反转）
- Epic Handshake（两组共识）

## 技术栈

- 纯静态 HTML + CSS + JS
- Imgflip API（`https://api.imgflip.com/get_memes` 获取模板，`caption_image` 生成）
- 无需后端，Netlify 免费托管

## 页面结构

```
/
├── index.html          # 主页面
├── style.css           # 样式
├── app.js              # 交互逻辑
└── README.md           # 说明
```

## 待确认

- [ ] Imgflip 账号（免费注册）
- [ ] AdSense 申请（需网站有一定流量）