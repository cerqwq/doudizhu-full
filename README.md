# 🃏 斗地主 - 完整版

Web版斗地主游戏，包含完整前后端。

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/Flask-Web-green?logo=flask" />
  <img src="https://img.shields.io/badge/WebSocket-实时-purple" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## ✨ 特性

- 🎮 完整斗地主规则实现
- 🤖 AI对手（智能出牌策略）
- 🌐 Web界面，支持多人在线
- 🔌 WebSocket实时通信
- 💾 SQLite数据库存储战绩
- 📱 响应式设计，支持移动端

## 📁 项目结构

```
doudizhu-full/
├── backend/           # 后端（Flask + WebSocket）
│   ├── app.py         # Flask应用入口
│   ├── game_engine.py # 游戏引擎（牌型判断、AI策略）
│   ├── doudizhu_db.py # 数据库操作
│   ├── routes.py      # 路由定义
│   ├── ws_handlers.py # WebSocket处理
│   └── requirements.txt
└── frontend/          # 前端（HTML + CSS + JS）
    ├── index.html     # 游戏界面
    ├── script.js      # 游戏逻辑
    ├── style.css      # 样式
    └── assets/        # 资源文件
```

## 🚀 快速开始

```bash
# 1. 安装依赖
cd backend
pip install -r requirements.txt

# 2. 启动服务器
python app.py

# 3. 打开浏览器
# 访问 http://localhost:5000
```

## 🎮 游戏规则

- 一副54张牌（含大小王）
- 3个玩家，1个地主 + 2个农民
- 地主先出牌，先出完者获胜
- 支持：单张、对子、三带一、顺子、炸弹、火箭等

## 🔧 技术栈

- **后端**: Python + Flask + Flask-SocketIO
- **前端**: HTML5 + CSS3 + JavaScript
- **数据库**: SQLite
- **通信**: WebSocket

## 📄 许可证

MIT License
