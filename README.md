# 🃏 德州扑克 Texas Hold'em

一个精美的网页版德州扑克游戏，纯前端实现，无需后端。

![Texas Hold'em](https://img.shields.io/badge/Game-Texas%20Hold'em-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🎮 在线演示

**GitHub Pages**: [https://longerian.github.io/texas-holdem/](https://longerian.github.io/texas-holdem/)

直接在浏览器中打开即可开始游戏，无需下载和安装！

## 🚀 快速开始

### 方式一：在线访问（推荐）
直接访问 GitHub Pages 地址：[https://longerian.github.io/texas-holdem/](https://longerian.github.io/texas-holdem/)

### 方式二：本地运行
```bash
# 克隆仓库
git clone https://github.com/longerian/texas-holdem.git

# 进入目录
cd texas-holdem

# 用浏览器打开 index.html
# 或者使用本地服务器
python3 -m http.server 8000
# 然后访问 http://localhost:8000
```

## 🎮 游戏特色

✨ **完整的德州扑克规则**
- 翻牌前 (Preflop)
- 翻牌 (Flop) - 3张公共牌
- 转牌 (Turn) - 第4张公共牌
- 河牌 (River) - 第5张公共牌
- 摊牌 (Showdown)

🎨 **精美的界面设计**
- 逼真的扑克桌设计
- 流畅的卡牌动画
- 响应式布局（支持手机/平板/电脑）
- 深色主题，护眼舒适

🎯 **完整的游戏功能**
- 跟注 (Call)、加注 (Raise)、过牌 (Check)、弃牌 (Fold)
- 实时显示手牌等级（一对、两对、三条、顺子、同花、葫芦、四条、同花顺）
- 与 5 个 AI 电脑对战
- 筹码管理系统
- 自动判断胜负

## 🤖 职业级 AI 系统

游戏内置 **5 种职业级 AI 对手**，每种都有独特的打牌风格：

| 类型 | 风格 | 特点 |
|------|------|------|
| TAG-Pro | 紧凶型 | 职业选手标准风格，稳健激进 |
| 岩石型 | 超紧型 | 只打最强牌，极少诈唬 |
| LAG-Pro | 松凶型 | 入池较宽，持续施压 |
| 超凶型 | 极度激进 | 高频诈唬，持续下注 |
| 混合型 | 平衡型 | GTO 风格，难以被剥削 |

### AI 核心功能

🎯 **范围思维**
- 根据对手行动估算其牌力范围
- 动态计算胜率 vs 对手范围

🔀 **GTO 混合策略**
- 同一情况下使用随机化频率
- AA 有 20% 慢打、QQ 有 40% 跟注
- 让对手无法预测和剥削

🎭 **诈唬检测系统**
- 追踪对手诈唬历史
- 分析下注模式判断诈唬概率
- 在合适时机抓诈唬

📊 **精细牌力评估**
- 区分顶对好踢脚 / 顶对弱踢脚
- 识别强听牌 vs 弱听牌
- 精确计算听牌成功率

🗓️ **多街规划**
- 提前规划转牌和河牌策略
- 根据牌面湿干调整下注大小
- SPR（筹码底池比）影响决策

📍 **位置意识**
- 庄家位优势最大
- 前位打得紧，后位打得宽
- 偷盲、3-bet 策略随位置变化

## 📄 许可证

MIT License

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 👨‍💻 作者

Created by OpenClaw AI Assistant 🦞

---

**享受游戏！如果有任何问题或建议，欢迎反馈。**
