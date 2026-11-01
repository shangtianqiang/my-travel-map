# 我的旅行地图 · My Travel Map

每去一个地方，就用一张网页把它收藏起来：行程、照片、攻略都在自己手里，点开链接就能重游。从上海出发，持续更新。

每个目的地都是一个**完整的 HTML 单文件**，移动端适配、可直接分享链接打开；照片全部来自 **Wikimedia Commons 真实图片，不使用 AI 生图**。

## 预览链接（GitHub Pages）

- 🌏 **总入口**：<https://shangtianqiang.github.io/my-travel-map/>

| 目的地 | 主题 | 预览链接 |
| --- | --- | --- |
| 青岛 | 红瓦绿树，碧海蓝天 · 老城与海岸线人文三日 | <https://shangtianqiang.github.io/my-travel-map/qingdao.html> |
| 舟山 | 海天佛国，渔都港城 · 朱家尖·普陀山·桃花岛 跳岛 | <https://shangtianqiang.github.io/my-travel-map/zhoushan.html> |
| 绍兴 | 桥多，酒香，书生多 · 上海虹桥往返一日（鲁迅故里·沈园·仓桥直街·八字桥） | <https://shangtianqiang.github.io/my-travel-map/shaoxing.html> |
| 南京 | 一眼六朝，半部民国 · 钟山·总统府·秦淮河 三天两晚（日期待定） | <https://shangtianqiang.github.io/my-travel-map/nanjing.html> |
| 杭州 | 淡妆浓抹总相宜 · 西湖·灵隐·运河 三天两晚（日期待定） | <https://shangtianqiang.github.io/my-travel-map/hangzhou.html> |
| 苏州 | 咫尺之内，再造乾坤 · 园林·平江路·山塘 三天两晚（日期待定） | <https://shangtianqiang.github.io/my-travel-map/suzhou.html> |
| 厦门 | 城在海上，海在城中 · 鼓浪屿·环岛路·八市 三天两晚（日期待定） | <https://shangtianqiang.github.io/my-travel-map/xiamen.html> |
| 成都 | 一座来了就不想走的城市 · 熊猫·慢生活·川渝味 三天两晚（日期待定） | <https://shangtianqiang.github.io/my-travel-map/chengdu.html> |
| 重庆 | 山即是城，城即是山 · 8D夜景·老街轻轨·火锅 三天两晚（日期待定） | <https://shangtianqiang.github.io/my-travel-map/chongqing.html> |

## 目录结构

```
my-travel-map/
├── index.html          # 总入口（目的地板）
├── qingdao.html        # 青岛攻略
├── zhoushan.html       # 舟山攻略
├── shaoxing.html       # 绍兴攻略（一日往返）
├── nanjing.html        # 南京攻略（三天两晚 · 日期待定）
├── hangzhou.html       # 杭州攻略（三天两晚 · 日期待定）
├── suzhou.html         # 苏州攻略（三天两晚 · 日期待定）
├── xiamen.html         # 厦门攻略（三天两晚 · 日期待定）
├── chengdu.html        # 成都攻略（三天两晚 · 日期待定）
├── chongqing.html      # 重庆攻略（三天两晚 · 日期待定）
├── PROMPTS.md          # 提示词复刻手册（每座城市的原始提示词）
└── assets/
    ├── *.jpg           # 青岛照片
    ├── zhoushan/       # 舟山照片
    ├── shaoxing/       # 绍兴照片
    ├── nanjing/        # 南京照片
    ├── hangzhou/       # 杭州照片
    ├── suzhou/         # 苏州照片
    ├── xiamen/         # 厦门照片
    ├── chengdu/        # 成都照片
    └── chongqing/      # 重庆照片
```

## 想复刻这个站？

全部**原始提示词与复刻步骤**已单独收存在 [PROMPTS.md](PROMPTS.md)——点开照着做，就能生成你自己的旅行地图。

## 说明

- 行程与价格整理自公开资料，出行前请以官方与预订平台为准。
- 照片版权归原作者所有，来源 Wikimedia Commons（各城市 `assets/<城市>/images.json` 内附作者与协议记录）。
