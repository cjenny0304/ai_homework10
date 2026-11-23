# Gui 等｜PSAGrasp

High–performance grasp pose detection via point cloud serialization attention

- **研究問題**：如何從點雲估計夾爪的六自由度抓取姿態？
- **方法**：以空間填充曲線排列點雲，透過注意力擷取特徵，再用 GPD-Net 與對向抓取約束產生候選姿態。
- **結果與限制**：作者在 GraspNet-1Billion 上報告偵測表現改善。小物件與背景點雲混在一起時仍難以偵測。
- **查核位置**：§4.8、§5。

[概念頁](../concepts/grasp.md) · [索引](../index.md) · [DOI／arXiv](https://doi.org/10.1016/j.patcog.2025.112099)
