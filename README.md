# PyTorchTutorial

PyTorchの機能を使って、色々やってみる。
- まずは[PyTorch開発入門][](杜世橋著)に従って、PyTorchの使い方を学習する。
- その後はPyTorch関連で各種アルゴリズムの実装にも手を出したい。

## PyTorch開発入門について

#### 作業環境

環境はpython 3.8.10を基準とする。コマンドは環境を構築するときは、以下のようにやっている。
```python
$ python3.8 -m venv .py38env
$ source .py38env/bin/activate
$ python -m pip install --upgrade pip 
$ pip install numpy pandas matplotlib torch jupyter
```
本の方にはminicondaを使って管理するように書いてあるが、仕事ではanacondaを利用できない状態なので、あくまでcondaには依存しない方向で進める。

#### プログラム

```notebook/entry_ch*.ipynb```に各chapterでのnotebookをまとめていくことにする。


[PyTorch開発入門]: https://www.amazon.co.jp/現場で使える！PyTorch開発入門-深層学習モデルの作成とアプリケーションへの実装-杜-世橋-ebook/dp/B07FTJPL31/ref=tmm_kin_swatch_0?_encoding=UTF8&qid=&sr=
