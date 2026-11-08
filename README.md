# 你好，我是 Infy 😎

GIS / 遥感 / WebGIS 方向的开发者。喜欢把完整的方法链做成**可复现、有展示力**的开源项目：既写 Python 遥感算法链（变化检测 / 面向对象分割 / SAR 粒度反演），也把地理知识做成可玩、可看、可复现的网页——诗词地图、数字孪生、AI 涌现叙事、文明沙盘。

> 🌏 项目大多围绕同一个问题：**怎么让地理知识变得可玩、可看、可复现。**

Hi, I'm Infy — I build reproducible, demo-ready GIS & remote-sensing projects: self-written Python pipelines for change detection, OBIA segmentation and SAR inversion, alongside playable web pieces from poetry maps to civilization sandboxes.

## 📚 开源作品集

| 项目 | 一句话简介 | 技术亮点 |
|---|---|---|
| **[SAR 潮滩粒度反演](https://github.com/dingdjfjs-star/s1-grain-size-gpr)** ｜ [结果图库](https://dingdjfjs-star.github.io/s1-grain-size-gpr/) | Sentinel-1 时序相干 + 极化特征 GPR 反演潮滩粒径：输出均值 + 后验不确定度（test R² 0.911，优于 XGBoost 对照 0.874） | Lee Sigma 去斑自实现 · 时序相干 + Pauli + TWI 九维特征 · 误差来源与改进全留痕 |
| **[面向对象分割分类](https://github.com/dingdjfjs-star/obia-segmentation)** ｜ [结果图库](https://dingdjfjs-star.github.io/obia-segmentation/) | 手写多尺度区域生长的 OBIA 全流程（Baatz & Schäpe 异质性准则）：对象级椒盐率较像素级 ↓11 倍、边界贴合 +49% | 优先队列 + union-find 自实现 · 对象内 GLCM 纹理与形状指数 · 参数敏感性扫描含失效机制分析 |
| **[S2 时序变化检测](https://github.com/dingdjfjs-star/s2-cva-change-detection)** ｜ [结果图库](https://dingdjfjs-star.github.io/s2-cva-change-detection/) | Sentinel-2 时序土地覆被变化检测全自研流水线：CVA → Otsu → 伪变化过滤 → 转移矩阵，5 处植入事件召回 96.9~100% | 生长季 medoid 合成 + PIF 辐射归一化 · 自研连通域 / 形态学过滤规则 · F1 94.3%（带真值评估） |
| **[诗词地图](https://github.com/dingdjfjs-star/poetry-map)** ｜ [在线体验](https://dingdjfjs-star.github.io/poetry-map/) | 唐诗宋词里的山河（地名考据版）：137 首经典诗词 × 187 个古地名，点击点位看全诗 / 注释 / 诗人游历路线 | 古今地名考据库（别名 / 存疑全留痕）· Leaflet 离线水墨底图 · 数据流水线自动匹配 + 人工核查报告 |
| **[地貌猜地点](https://github.com/dingdjfjs-star/landform-guess)** ｜ [在线体验](https://dingdjfjs-star.github.io/landform-guess/) | AI 出题 + AI 裁判的全球地貌推理游戏：50 套题 × 11 类地貌，逐条放线索，揭晓附完整地理推理链 | 约 2.4 万项断言质检 · 易泄露词自动扫描 · 程序绘画 + 实景署名照 |
| **[海岸科考求生](https://github.com/dingdjfjs-star/coast-survival)** ｜ [在线体验](https://dingdjfjs-star.github.io/coast-survival/) | 潮汐 / 风暴潮 / 红树林题材的文字冒险：采样本、选观测站址、躲随机灾害、撤离结算，16 种结局 | 纯逻辑状态机（可序列化可回放）· DFS 25 万状态找死局 · 3000 局 fuzz 必终结 |
| **[青园巡记](https://github.com/dingdjfjs-star/qingyuan-xunji)** ｜ [在线体验](https://dingdjfjs-star.github.io/qingyuan-xunji/) | 涌现式校园叙事：六个 AI 角色（食堂阿姨 / 保安大爷 / 校园猫…）在真实校园生活七天，没有一个字出自人手 | 相遇对白互盲即兴 · 三关智能体逐句评审 · Google Earth 真实底图 · 单文件可断网运行 |
| **[轮叙四箴](https://github.com/dingdjfjs-star/lunxu-sizhen)** ｜ [在线体验](https://dingdjfjs-star.github.io/lunxu-sizhen/) | 赣南师范大学 GIS 数字孪生滚动叙事：以校训「博达毅卓」为轴，一次滚动滚过赣师四年 | 109 栋真实建筑轮廓程序化拉伸三维楼群 · 卫星影像六点标定对齐 · 多智能体集群生成与评审 |
| **[孤岛文明沙盘](https://github.com/dingdjfjs-star/island-civ-sandbox)** ｜ [在线体验](https://dingdjfjs-star.github.io/island-civ-sandbox/) | Perlin 孤岛上的部落演化沙盘：地形资源程序生成，部落采集扩张、相遇冲突或吞并，同一种子逐位复现同一段历史 | 纯逻辑核心（可序列化可回放）· 89 万项断言质检 · 零依赖单文件双击即玩 |
| **[Cesium 校园数字孪生](https://github.com/dingdjfjs-star/cesium-campus-twin)** | CesiumJS 卫星图数字化的真实校园三维场景：数据驱动，换学校只改一个文件 | Cesium 1.144 · 三大渲染停摆避坑手册 · ECharts 联动 · 12 课互动教程 |
| **[福鼎城镇演化](https://github.com/dingdjfjs-star/fuding-evolution)** ｜ [在线体验](https://dingdjfjs-star.github.io/fuding-evolution/) | 以真实市域轮廓 + SRTM 高程为约束的城镇演化沙盘：南宋渔村渡口 → 当代湾区 6 轮推演，政策可切 | SRTM 真实 DEM + OSM 真实河网 · Three.js 三维逐年回放 · 10 类逻辑矛盾自动校验（93 项断言） |
