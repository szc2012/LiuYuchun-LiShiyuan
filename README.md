# 💕 爱情树 LoveTree

<div align="center">

![LoveTree Demo](./index_files/love-tree.gif)

一个浪漫的网页应用，用动态爱心树来记录你们的美好时光 ✨

[![GitHub stars](https://img.shields.io/github/stars/AJLoveChina/LoveTree?style=social)](https://github.com/AJLoveChina/LoveTree)
[![GitHub forks](https://img.shields.io/github/forks/AJLoveChina/LoveTree?style=social)](https://github.com/AJLoveChina/LoveTree)

</div>

## 🌟 项目特色

- 💖 **浪漫动效**: 唯美的爱心树生长动画
- 🎵 **背景音乐**: 支持自定义背景音乐播放
- 📱 **响应式设计**: 完美适配手机、平板、桌面端
- ⚙️ **简单配置**: 仅需修改配置文件即可个性化定制
- 🌐 **兼容性强**: 支持微信、QQ等各种浏览器环境
- 🎨 **视觉效果**: 炫酷的Canvas动画和时间倒计时

## 🚀 快速开始

### 在线体验
直接打开 `index.html` 文件即可在浏览器中查看效果

### 个性化定制

1. **修改配置文件**
   编辑 `config.js` 文件来自定义你的爱情树：

```javascript
var config = {
    // 自定义文字内容（可以是任意句数）
    lines: [
        "亲爱的宝贝：",
        "遇见你是我最美的意外",
        "愿我们的爱情像这棵树一样",
        "在时光中慢慢生根发芽",
        "无论风雨都不会凋零",
        "因为有你，每天都是情人节",
        "我爱你，直到永远 💕",
    ],
    // 相爱的时间（重要：格式必须准确）
    // 格式：年-月-日T时:分:秒
    date: "2023-02-14T20:30:00",
    // 两人的名字
    names: ["小明", "小红"]
}
```

2. **更换背景音乐**
   - 将你喜欢的音乐文件重命名为 `music.mp3`
   - 替换 `index_files/music.mp3` 文件
   - 如不需要音乐，直接删除该文件即可

3. **调整样式**
   - 可修改 `index_files/default.css` 来调整页面样式
   - 支持自定义颜色、字体等视觉效果

## 📋 配置说明

### config.js 参数详解

| 参数 | 类型 | 说明 | 示例 |
|------|------|------|------|
| `lines` | Array | 显示的文字内容，每行一句 | `["第一句话", "第二句话"]` |
| `date` | String | 纪念日期，格式严格按照ISO标准 | `"2023-02-14T20:30:00"` |
| `names` | Array | 两个人的名字 | `["张三", "李四"]` |

### 时间格式重要提醒 ⚠️
- 必须使用 `YYYY-MM-DDTHH:mm:ss` 格式
- 时分秒必须是两位数字（如：`08:05:09`）
- 中间的 `T` 不能省略
- 错误的格式可能导致时间显示异常

## 🎯 功能特性

### 🎵 音乐播放
- 现代浏览器需要用户交互才能播放音频
- 点击页面上的爱心后音乐自动播放
- 右上角音乐按钮可控制播放/暂停
- 支持循环播放

### 📱 移动端优化
- 自适应不同屏幕尺寸
- 触摸友好的交互设计
- 优化的字体大小和布局
- 完美支持微信、QQ内置浏览器

### ⏰ 时间计算
- 实时显示相爱天数、小时、分钟、秒数
- 精确到秒的时间计算
- 动态更新显示

## 🛠️ 技术栈

- **前端**: HTML5, CSS3, JavaScript
- **动画**: Canvas 2D API
- **音频**: HTML5 Audio API  
- **异步处理**: Jscex 异步框架
- **样式**: 响应式CSS设计

## 📂 项目结构

```
LoveTree/
├── index.html          # 主页面文件
├── config.js          # 配置文件
├── README.md          # 项目说明
└── index_files/       # 资源文件夹
    ├── music.mp3      # 背景音乐
    ├── love-tree.gif  # 演示图片
    ├── *.js           # JavaScript库文件
    └── default.css    # 样式文件
```

## 🌍 浏览器支持

| 浏览器 | 版本要求 |
|--------|----------|
| Chrome | ≥ 50 |
| Firefox | ≥ 45 |
| Safari | ≥ 10 |
| Edge | ≥ 14 |
| 微信浏览器 | 支持 |
| QQ浏览器 | 支持 |

## 📖 使用教程

### 知乎详细教程
📝 [5分钟做一个免费的网页爱情树](https://zhuanlan.zhihu.com/p/72907840)

### 部署方式
1. **本地查看**: 直接双击 `index.html` 文件
2. **在线部署**: 上传到任意静态网站托管平台
3. **分享链接**: 可通过微信、QQ等社交平台分享

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

1. Fork 本项目
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的修改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个 Pull Request

## 📜 开源协议

本项目基于 MIT 协议开源，详见 [LICENSE](LICENSE) 文件。

## 💖 相关项目

霸都丶傲天的其他浪漫网页模板：

- 🌳 [第一期: 爱情树](https://github.com/AJLoveChina/LoveTree) - 将相爱的时刻永远珍藏
- 🎂 [第二期: 生日祝福](https://github.com/AJLoveChina/birthday) - 超具创意的网页生日祝福
- 🎈 [第三期: 告白气球](https://github.com/AJLoveChina/loveBalloon) - 塞纳河畔的浪漫告白

## 👨‍💻 原作者信息

**霸都丶傲天**
- 知乎: [@霸都丶傲天](https://www.zhihu.com/people/AJLoveChina)
- GitHub: [@AJLoveChina](https://github.com/ajlovechina)

---

<div align="center">

如果这个项目对你有帮助，请给一个 ⭐️ Star 支持一下！

**让爱情在代码中绽放** 💕

</div>
