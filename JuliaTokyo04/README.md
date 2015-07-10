# JuliaTokyo \#4

[QuantEcon.jl](https://github.com/QuantEcon/QuantEcon.jl) の紹介
@[JuliaTokyo \#4](http://juliatokyo.connpass.com/event/16570/)

## インストール方法 (2015/7/9現在)

`Pkg.add("QuantEcon")` でインストールされる版はバグが残っているので，
開発版 (`markov` ブランチ) を

```julia
julia> Pkg.clone("QuantEcon")
julia> Pkg.checkout("QuantEcon", "markov")
```

でインストールしてください．

## Notebooks

* [マルコフ連鎖](http://nbviewer.ipython.org/github/oyamad/presentations/blob/master/JuliaTokyo04/markov_chain.ipynb)
* [最適成長理論](http://nbviewer.ipython.org/github/oyamad/presentations/blob/master/JuliaTokyo04/optimal_growth.ipynb)
