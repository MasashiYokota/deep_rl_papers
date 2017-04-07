# UNREAL

## 区分け
+ model-free
+ On-policy(Off-policyのデータも使う)
+ discrete and continuous
+ multistep
+ for game


## 先行研究
+ A3C
 - 補助タスクを使った


## 提案手法のイケてる部分
+ 補助タスクを導入した所
+ sparse rewardに対して強い
+ 名前UNRREAL
+ 夢見る人工知能


## 実験
+ Atari
+ Labyrinth
LabyrinthでA3Cより良い
ロバスト性の向上


## Discussion
補助タスク導入して、ロバスト性向上してLabyrinthの難しいタスクでもいい結果でたよ


## 考察
pixel controlが良い理由
+ 移動に対する特徴量の抽出がしやすい?
+ 積極的な行動が必要なタスクにおいて有効?

補助タスクが良い理由
+ sparse rewardに対して強い
+ CNNの特徴抽出の学習が速く進む

feature controlが実はいい理由
+ sparse activationの方がよさそうだけど...
+ 層を通じて渡る情報量が多いほうがよい?


## 実装
