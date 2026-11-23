# Li 等｜PG-SLAM

PG-SLAM: Photo-realistic and Geometry-aware RGB-D SLAM in Dynamic Environments

- **研究問題**：當相機和場景前景都會動時，如何定位相機與重建場景？
- **方法**：分別建模動態前景與靜態背景，並利用兩者的資訊定位相機。
- **結果與限制**：作者在 TUM 與 NeuMan 等資料上測試。Table V 比較局部地圖最佳化，文中指出相鄰局部地圖重疊較少時，此策略效果會下降。
- **查核位置**：摘要、Tables II、III、V 及 Table V 旁的討論。

[概念頁](../concepts/mapping.md) · [索引](../index.md) · [DOI／arXiv](https://arxiv.org/abs/2411.15800v1)
