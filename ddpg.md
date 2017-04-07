# DDPG

## 区分け
+ model-free
+ Off-policy
+ continuous
+ single step
+ for real


## 先行研究
+ DQN
 - actor-critic
 - continuousになった
 - targetのsoftなupdate
+ DPG
 - Deepに適用した
 - experience replay
 - target network


## 提案手法のイケてる部分
+ 実験がちゃんとしてる


## どんな実験をしているか
+ Mujoco
+ Torcs
いい感じ
target networkが大事


## Discussionのまとめ
DQNとDPGを合わせてcontinuousで入力が画像(高次元)のタスクを学習し、実験的に安定した結果を得た。
Atariを解くDQNよりも少ないstepで学習できるようになった(2.5million)
まだまだ必要サンプル数が多い

## 次の論文


## 実装上のテクニック
+ 最終層の初期値を小さい値にする
