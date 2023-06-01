# 本稿の目的  
本稿では、統計的因果推論の理論とRでの実装についてまとめる。統計的因果推論には大きく分けて潜在的結果変数の枠組みを用いる**Rubin流**(例えば、星野, 2009; 高橋, 2012)と**構造的因果モデル(SCM: Structual Causal Model)**と**因果ダイアグラム(もしくはグラフィカルモデル)**を用いる**Pearl流**に分けられる。本稿では、主に後者に焦点を当てて解説を行う。  

本文は[こちらから](https://tsubasayamaguchi-jinrui.github.io/Causal_Inference_bookdown/)。  

参考にした書籍やウェブサイトは、以下のものである。  

- Causal inference in statistics: A primer (邦訳「入門統計的因果推論」)(Pearl et al. 2016)  
  $\rightarrow$ 本稿のベース      

- The book of why: the new science of cause and effect. (邦訳「因果推論の科学」)(Pearl and Mackenzie 2018) 
  $\rightarrow$ 一般向け書籍。数式を用いない解説や事例が豊富。因果推論の科学ができるまでの歴史についても学べる。  

- 岩波データサイエンス vol. 3 因果推論ー実世界のデータから因果を読む (岩波データサイエンス慣行委員会, 2016)  
  $\rightarrow$ バックドア基準をはじめ因果推論のトピックに関する短くわかりやすい解説        

- 統計的因果推論―回帰分析の新しい枠組み― (宮川, 2004)  

- Take a Risk: 林岳彦の研究メモ [ウェブサイト](https://takehiko-i-hayashi.hatenablog.com/)  
