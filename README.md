# jecon-sice-bst (jecon.bstの計測自動制御学会ジャーナル向け派生版, 非公式)
Modified jecon.bst for SICE Journals (Unofficial)

武田史郎先生による [jecon.bst](https://github.com/ShiroTakeda/jecon-bst) 
([ver. 6.5.1](https://github.com/ShiroTakeda/jecon-bst/releases/tag/6.5.1)がベース) の
派生版であり，計測自動制御学会(SICE)関連のジャーナルの参考文献書式の再現を目指しています．

学会から公認されたものではありません(i.e., 非公式版)．
自己責任でご使用ください．

# 使い方 および 設定
普段通り使えばOKですが，bibファイルの記入の流儀によって
設定が必要になるケースがあります．詳細は example.pdf をご確認ください．

# 本家 jecon.bst との違い
1. SICE関連誌に合わせてページ数が aaa/bbb とする処理を行っています．
1. 本家は natbib を使った \harvarditem による参照を行っていますが，
   通常の \cite で参照する形式にしています．

そのほか詳細は jecon.bst 本家も併せてご参照ください．

# 参考資料
1. [jecon.bst](https://github.com/ShiroTakeda/jecon-bst): このような便利なプログラムを
   公開されている武田先生に感謝いたします．
1. ["計測と制御"ウェブサイト](https://www.sice.jp/pub/journal/):
   SICE会誌の"計測と制御"の目次やバックナンバーが閲覧できます．テンプレートも配布されています．