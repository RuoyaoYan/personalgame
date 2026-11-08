# personalgame

在浏览器里直接玩的小游戏合集。

## 🎓 Campus Explorer（`campus/`）

一张可以放大、旋转、到处走的 3D 欧式城市校园地图，灵感来自 TUM Campus Heilbronn（Bildungscampus）、Bocconi Milano 和 University of Auckland。

- **建筑**：Klinker 红砖柱和整面落地玻璃（Bildungscampus 风格），SANAA 风格的白色环形商学院，哥特复兴钟楼
- **Campusbrücke**：横贯校园、跨越铁路的人行天桥。铁路把校园分成两半，桥是唯一的通道
- **玩法**：WASD 或点地面移动（会自动找楼梯上桥），碰到金色水晶领取 5 ECTS，一共 20 个地点、100 ECTS
- **功能**：昼夜切换、高画质（GTAO 环境光遮蔽）和流畅模式、小地图、钟楼登顶看全景，钟面显示真实时间

纯静态页面，Three.js 从 CDN 加载，不需要构建。本地预览：

```bash
python3 -m http.server
# 打开 http://localhost:8000/campus/
```
