# personalgame

在浏览器里直接玩的小游戏合集。

## 🎓 Campus Explorer（`campus/`）

一张可以放大、旋转、到处走的 3D 欧式城市校园地图，灵感来自 TUM Campus Heilbronn（Bildungscampus）、Bocconi Milano 和 University of Auckland。

- **布局**：按手绘地图重建。Neckar 河在西侧，四线铁路斜穿校园，校园内没有机动车道，原来的路都改成了共享步道 / 自行车道，东南角是 Albert-Park 和小溪
- **Mensa**：照 Auer Weber 设计的真实 Mensa（2020）重做：广场上升起两座可以走上去的草坡，大草坡东侧翘起薄边檐、下面是弧形玻璃立面，旁边有开放楼梯、椭圆玻璃采光井和玻璃电梯，餐厅在地下（室内暂未开放）
- **建筑**：Klinker 红砖柱和整面落地玻璃（Bildungscampus 风格），白色穿孔金属网的商学院，哥特复兴钟楼和回廊庭院，顶层泳池体育中心，六层的 LIV 图书馆，红砖研究塔顶部是 Selected 精英项目专属楼层
- **Campusbrücke**：全校唯一跨越铁路的人行桥，按 Google 地图上真实的 Heilbronn Campusbrücke 测量复刻：长度、弯道半径与转角、以及和铁轨的相对位置都按比例一致（以 4.25 m 轨道间距为比例尺；铁路为四条轨道）。北端是穿孔玻璃电梯塔（可以坐电梯上下），南端一段短楼梯
- **玩法**：WASD 或点地面移动（A* 自动寻路，过铁路会自动坐电梯走桥）；纯探索，没有计分：从地点列表或标签挑地方，看介绍、走过去或近看
- **功能**：昼夜切换、高画质（GTAO 环境光遮蔽）和流畅模式、小地图、钟楼登顶看全景，钟面显示真实时间

手绘总平面图：[`campus/campus-map.png`](campus/campus-map.png)

纯静态页面，Three.js 从 CDN 加载，不需要构建。本地预览：

```bash
python3 -m http.server
# 打开 http://localhost:8000/campus/
```



游戏入口页：https://ruoyaoyan.github.io/personalgame/
校园地图：https://ruoyaoyan.github.io/personalgame/campus/
