# Linux.do 自动浏览点赞脚本

这是一个用于 Linux.do 网站的自动化浏览和点赞脚本。该脚本可以自动浏览帖子并对高质量内容进行点赞。

## 功能特点

- 自动浏览帖子
- 智能点赞（仅点赞浏览量超过500的帖子）
- 模拟真实用户浏览行为
- 可配置浏览时间和数量
- 统计浏览和点赞数据
- 无感浏览模式
- 可配置日志输出

## 安装说明

1. 首先安装 Tampermonkey 浏览器扩展
2. 点击 [这里](https://greasyfork.org/zh-CN/scripts/524017-linuxdo%E4%BF%9D%E6%B4%BB) 安装脚本
3. 访问 [Linux.do](https://linux.do) 网站，点击页面顶部的火箭图标启动脚本

## 配置说明

脚本提供了以下可配置项：

### 浏览配置

- 滚动间隔：1500ms
- 滚动步长：500像素
- 点赞阈值：500浏览量
- 最大浏览数：100篇
- 浏览时间：30秒/篇
- 最大运行时间：30分钟

### iframe配置

- 宽度：330px
- 高度：500px
- 位置：顶部64px，左侧1px
- 层级：9999

### 日志配置

- 是否启用日志：可配置
- 日志级别：
  - 错误日志：默认开启
  - 信息日志：默认开启
  - 调试日志：默认关闭

## 使用注意

- 请合理使用，不要对服务器造成过大压力
- 建议适当调整配置参数，模拟真实用户行为
- 如遇到问题，请在 Issues 中反馈
- 可以通过配置日志级别来查看脚本运行状态

## 许可证

MIT License
