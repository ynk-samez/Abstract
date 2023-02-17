# 卒業研究抄録用のgitリポジトリ

```
git clone https://github.com/ynk-samez/Abstract.git 
```

## Purpose of this Research
Federated Lerning has been proposed as a machine learning method for edge computing.
Federated Lerning has been proposed as a machine learning method for edge computing. In federated learning
learning is performed at each node in the network without aggregating the learning data
and only the resulting parameter differences are communicated to each node in the network.
the learned model is constructed by communicating only the resulting parameter differences, and the privacy
The training data, including privacy data, is protected. Expectations for Machine Learning and the Global
and the global trend toward privacy protection, federative learning is expected to become an important part of the information society in the future.
In the future, federated learning is expected to occupy an important position in the information society due to the expectation of machine learning and the global trend toward privacy protection.
On the other hand, in the practical application of federated learning, the models that have been
on the other hand, the practical application of federated learning will require models that have been running in data centers to be deployed in edge environments with scarce computational resources.
In the practical application of federated learning, however, at least the following two issues need to be considered
The first is the reduction of learning parameters. The first is to reduce the weight of the model by reducing training parameters.
The second is to maximize the effective use of heterogeneous computational resources in the edge environment.
The first is to reduce the weight of the model by reducing the training parameters. For the former, pruning and neural architecture search can be used.
architecture search for the former, and agent-oriented architecture for the latter.
distributed processing systems based on agent-oriented architectures and large-scale
distributed processing systems using agent-oriented architectures and large-scale distributed computation
There have been a variety of precedents and studies to date. If we can construct a model that satisfies both of these requirements, it will be possible to
large scale neural network to the edge environment, and
and maximize the utilization of computational resources in the environment.
However, as far as the author knows, there is no research on a model that satisfies both of these requirements.
However, as far as the author knows, there is no research on a model that satisfies both of these requirements.
In this study, we propose an edge computing architecture that is expected to be deployed in the future, and a model that can be used to maximize the utilization of computational resources in the environment.
architecture that is expected to be deployed in the future, and a corresponding machine learning method called federative learning.
and the corresponding machine learning method, coalition learning, which is expected to be deployed in the future.
We propose a parameter reduction method for autonomous distributed neural networks for edge computing architectures, which are expected to be introduced in the future, and for the corresponding machine learning method
---------
エッジコンピューティングでの機械学習手法として連合
学習 (Federareted Lerning) が提案されている. 連合学習で
は, 学習データを集約せずネットワーク中の各ノードで学習
し, その結果得たパラメータ差分のみを通信することによっ
て大規模な学習済みモデルを構築するため, プライバシーを
含んだ学習データは保護される. 機械学習への期待と世界
的な個人情報保護の動きの高まりから, 将来的に連合学習は
情報社会において重要な位置を占めることが予測される.
一方, 連合学習の実用化に際しては, 従来, データセンター
で動いていたモデルを計算資源に乏しいエッジ環境に投入
する必要があることから少なくとも以下 2 点の課題が考え
られる. 1 つ目は学習パラメータ削減によるモデルの軽量
化, 2 つ目は, エッジ環境内の不均一計算資源の最大限の有
効利用である. 前者については刈り込みや, ニューラルアー
キテクチャ探索, 後者についてはエージェント志向アーキテ
クチャによる分散処理システムや遊休計算資源を用いた大
規模分散計算等があり, 今日までに多様な先行事例・研究が
成されている. 両者を満たしたモデルを構築できれば, 大規
模なニューラルネットワークのエッジ環境への投入を可能
にし, かつ環境内の計算資源の利用率を最大化することが期
待できるが, 両者を満たしたモデルに関する研究は著者の知
る限り存在しない.
そこで本研究では, 将来的に導入が予測されるエッジコン
ピューティングアーキテクチャ及び, それに対応した機械学
習手法である連合学習に向けて, 自律分散性を持ったニュー
ラルネットワークのパラメータ削減を提案する
