# 色彩、深度與位置估計

RGB 描述外觀，深度描述表面與相機之間的距離。當兩件物品顏色近似而距離不同時，深度可提供額外區分線索。TABBTrack 融合兩種訊號。單相機輔具則從影像估算距離與手部座標，用 Kalman 濾波預測短期運動。比較時應交代距離資訊的取得方式。

- [TABBTrack](../papers/tabbtrack.md)
- [Barsalani 等｜單相機取物輔具](../papers/assist.md)
