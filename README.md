# 灰港行动

第一人称搜索、交火、撤离小游戏（OP · GRAYPORT）。整备干员和装备后部署，适合 iPad 触屏或键鼠游玩。

## 在线体验

GitHub Pages: `https://yefei404.github.io/grayport/`

## 功能特性

- **整备**：选择地图、干员、主武器、护甲、背包和战术装备后部署
- **战术道具**：干员带有多件可切换的战术技能，各有独立冷却
- **战斗**：搜索容器、交火、治疗、投掷，成功撤离才能把物资带回去
- **仓库**：带出的物资先入库，需要资金时再出售；仓库可扩容
- **大红收藏室**：成功带出的红色物品自动陈列，集齐一套有额外奖励
- **安全箱**：箱内物品阵亡也保留
- **键鼠 / 触屏**：支持鼠标锁定操作，也支持 iPad 虚拟摇杆
- **存档**：资金和仓库保存在本浏览器 localStorage
- **iPad 桌面图标**：Safari「添加到主屏幕」显示灰港图标

## 项目结构

```
grayport/
├── index.html      # 单文件应用（HTML + CSS + JS）
├── three.min.js    # Three.js（本地，避免依赖外网 CDN）
├── icon.png        # iPad 主屏幕图标
└── README.md
```

## 本地运行

```bash
open index.html
# 或使用静态服务器
npx serve .
```

## 部署

1. 在 GitHub 创建仓库 `yefei404/grayport`（Public）
2. push 到 `main` 分支
3. Settings → Pages → Source 选 `main` 分支、根目录 `/`

## License

MIT
