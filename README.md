# ポアンカレエンベッディング

Euclid空間にエンベッディングするようなword2vecは意味の上下関係が明示的に記されません。(情報としたあったとしても僅かでしょう)  

ポアンカレボールという双曲幾何学空間に埋め込むことで、効率的に意味の上位関係をとらえることができるとのことです[1]

## 理解
　ポアンカレボールはこのような、外周部に行くほど密になる球みたいなものなのです。
<div align="center">
  <img width="200px" src="https://user-images.githubusercontent.com/4949982/35317172-d165049e-0118-11e8-8704-33fb389696c9.png">
</div>
<div align="center"> 図1. ハニカム構造のPincare Ball(Wikipediaより)</div>
ポアンカレボールでは外に行くほど情報が密になり、空間が広がっているともとらえます。
 
 数式で表現するとこのようになって、
<div align="center">
  <img width="200px" src="https://user-images.githubusercontent.com/4949982/35318593-5bd1d714-011f-11e8-9d2e-5091d9851035.png">
</div>
gEというユークリッド距離がxが1に近づけば無限に大きくなることがわかります。



## 実験

### データセット

### 評価

### 参考文献
- [1] [Poincaré Embeddings for Learning Hierarchical Representations](https://arxiv.org/abs/1705.08039)
