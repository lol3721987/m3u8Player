# M3U8视频播放器助手 - 多源版本

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)

一个功能强大的Tampermonkey用户脚本，提供M3U8视频播放和多源搜索功能。

## 功能特性

- 🎬 **多源视频搜索**：集成17+个视频源，支持聚合搜索和单一来源搜索
- ▶️ **M3U8视频播放**：基于HLS.js的播放器，支持多种CDN回退机制
- 🔍 **智能搜索**：支持关键词搜索、分页显示和结果过滤
- 🖱️ **便捷操作**：浮动搜索面板、拖拽界面、自动M3U8链接检测
- 📋 **剧集管理**：支持连续剧播放、选集列表和链接复制
- 💾 **状态保存**：用户偏好设置持久化存储
- 🌐 **跨域支持**：使用GM_xmlhttpRequest处理跨域请求

## 支持的视频源

- LZI资源
- 黑木耳资源
- 如意资源
- 暴风资源
- 天涯资源
- 非凡影视
- 360资源
- iqiyi资源
- 卧龙资源
- 极速资源
- 豆瓣资源
- 魔爪资源
- 魔都资源
- 最大资源
- 樱花资源
- 百度云资源
- 无尽资源
- iKun资源
- 更多资源...

## 安装方式

1. 安装[Tampermonkey](https://www.tampermonkey.net/)浏览器扩展
2. 点击[m3u8Player-tampermonkey.user.js](m3u8Player-tampermonkey.user.js)下载脚本
3. Tampermonkey会自动检测并提示安装
4. 点击"安装"按钮完成安装

或者直接访问以下链接安装：
```
https://github.com/lol3721987/m3u8Player/raw/main/m3u8Player-tampermonkey.user.js
```

## 使用说明

1. 安装完成后，访问任意网页
2. 点击浏览器右上角的Tampermonkey图标，选择"🎬 打开视频搜索"
3. 或者点击页面右下角的圆形播放器按钮
4. 在搜索框中输入视频名称进行搜索
5. 选择视频源（支持聚合搜索或单一来源）
6. 点击播放按钮观看视频

## 技术特点

- **模块化设计**：代码组织为9个独立模块，便于维护和扩展
- **错误处理**：完善的错误处理机制，包括网络错误、视频加载失败等
- **内存管理**：正确清理HLS.js实例、事件监听器和定时器
- **性能优化**：实现防抖、节流等优化技术
- **响应式UI**：提供加载状态、分页和用户反馈

## 开发者信息

- **作者**：zjb
- **版本**：1.0.0
- **许可证**：MIT

## 更新日志

### v1.0.0
- 初始版本发布
- 修复在iframe中重复执行的问题
- 清理调试日志输出
- 优化HLS.js加载机制

## 安全说明

该脚本使用Tampermonkey的安全API进行跨域请求和数据存储，确保用户数据安全。

## 贡献

欢迎提交Issue和Pull Request来帮助改进这个项目。

## 许可证

本项目采用MIT许可证，详情请见[LICENSE](LICENSE)文件。

## 致谢

- [LibreTV](https://github.com/LibreSpark/LibreTV) [MoonTV](https://github.com/senshinya/MoonTV) — 由此启发，站在巨人的肩膀上。
- [HLS.js](https://github.com/video-dev/hls.js) — 实现 HLS 流媒体在浏览器中的播放支持。