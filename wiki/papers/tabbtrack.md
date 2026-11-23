# TABBTrack

Ge Ying 等，〈Temporal adaptive bidirectional bridging for RGB-D tracking〉，Pattern Recognition 158 (2025)，111053。[DOI](https://doi.org/10.1016/j.patcog.2024.111053)

- **問題（§1）**：給定第一幀中的目標，在後續影格估計它的位置。色彩、深度的互補性是方法動機。
- **方法（Fig. 3，PDF 第 4–5 頁）**：使用交叉注意力，透過融合模板在 RGB 與深度搜尋區域之間傳遞資訊。模型同時利用首幀模板與線上模板。
- **評估（Tables 1–2）**：作者使用 ARKitTrack、DepthTrack、CDTB 與 VOT-RGBD2022；比較時須保留各資料集與指標。
- **證據待查（Tables 1、3）**：DepthTrack 的 TABBTrack F-score，在方法比較表為 0.618，在元件消融表為 0.619；兩表均列 Pr 0.622、Re 0.615。保留各表原值。
- **適用範圍（Table 1）**：在該表的 CDTB 比較中，STARK_RGBD 的 F-score 為 0.755，TABBTrack 為 0.721。效能說法須限定比較條件。

[概念頁](../concepts/fusion-and-update.md) · [索引](../index.md)

[色彩與深度](../concepts/signals.md) · [相機定位與建圖](../concepts/mapping.md)
