# Zhong 等｜2DGS-SLAM

Globally Consistent RGB-D SLAM with 2D Gaussian Splatting

- **研究問題**：如何估計相機軌跡並減少長時間掃描的地圖漂移？
- **方法**：用 2D Gaussian splatting 表示地圖，並透過回環偵測與地圖更新整合重訪區域。
- **結果與限制**：Table X 的三段自錄序列平均絕對軌跡誤差為 5.0 cm。走廊序列中 LoopSplat 為 2.1 cm，2DGS-SLAM 為 3.4 cm。
- **查核位置**：摘要、Fig. 1、Table X。

[概念頁](../concepts/mapping.md) · [索引](../index.md) · [DOI／arXiv](https://arxiv.org/abs/2506.00970v1)
