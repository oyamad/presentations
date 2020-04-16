# ゲーム理論 (2020年4月16日)

ナッシュ均衡の計算の実演

## Notebooks

* [`quantecon.game_theory` を使ってみる](https://nbviewer.jupyter.org/github/oyamad/presentations/blob/master/game20/game20_py.ipynb)
* [`Games.jl` を使ってみる](https://nbviewer.jupyter.org/github/oyamad/presentations/blob/master/game20/game20_jl.ipynb)

## 実行環境構築

例えば[ここ](https://github.com/OyamaZemi/Settingup)参照

### Python

[`QuantEcon.py`](https://github.com/QuantEcon/QuantEcon.py) をインストールする:

Jupyter notebook (Python) で

```
!pip install quantecon
```

あるいは，ターミナルで

```
pip install quantecon
```

### Julia

[`Games.jl`](https://github.com/QuantEcon/Games.jl) をインストールする:

Jupyter notebook (Julia) で

```
using Pkg; Pkg.add("https://github.com/QuantEcon/Games.jl")
```

あるいは Julia アプリケーションのコンソール (`REPL`) で，`]` を押してパッケージ・モードに入ってから

```
add https://github.com/QuantEcon/Games.jl
```

## さらなる学習のために

* [game-theory-notebooks](https://github.com/QuantEcon/game-theory-notebooks)
* QuantEcon レクチャー
  * [Python 版](https://python.quantecon.org)
  * [Julia 版](https://julia.quantecon.org)
