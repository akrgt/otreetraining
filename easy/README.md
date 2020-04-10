# oTreeで簡単に実験を作ってみる

## oTreeをインストールする

* 最初にインストールしましょう．

```
pip install -U otree
```
* Powershellかコマンドプロンプト(Win)，ターミナル(Mac)で上記コードを入力します．
  - インストール作業は以上です．
  - 必要に応じて追加のプログラムもインストールされます．

## インストールがうまくいかない場合

1. Pythonのシステムパスは通っていますか？
   * [コチラ](https://www.javadrive.jp/python/install/index3.html)などを参考に確認してみてください．
2. Anacondaをインストールされている場合
   * インストール時に非推奨とされている「**Add Anaconda to the systemPATH environment variable**」にチェックを入れるとPowershellやコマンドプロンプト(Win)，ターミナル(Mac)でそのまま作業できます．
   * パスを通したくない場合**はAnaconda Navigator**を起動して，**Environment**へ，**base(root)**もしくは自身で用意しているならばそのEnvironmentの中にある**▶**をクリックします．そこで**Open Terminal**をクリックすると作業を進めていくことができます．

## プロジェクトを作る

* 今回はわかりやすいようにデスクトップでの作業を例とします．

* Windowsの場合
```
cd C:¥Users¥[ユーザ名]¥Desktop
```

* Macの場合
```
cd /Users/[ユーザ名]/Desktop
```

* 上記にてデスクトップに移動した後に，"otreetest"という名前のプロジェクトフォルダを作成します．
```
otree startproject otreetest
```
  - ここで様々な作業を行う感じです．


* Include sample games? (y or n)→ y
  - いきなり入れちゃうと面白くないけど，手っ取り早く実験をするために入れてみましょう．





## ディレクトリに移動する

* Windowsの場合

```
cd C:¥Users¥[ユーザ名]¥Desktop/otreetest
```

* Macの場合

```
cd /Users/[ユーザ名]/Desktop/otreetest
```

* ディレクトリに移動したら，以下のコードを走らせる

```
otree devserver
```

* これによってローカル内で起動する．

* その後，`http://localhost:8000/`にアクセスすると，oTreeの画面が見られる．

  



