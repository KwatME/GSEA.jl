## Install

```sh
julia
```

```julia
using Pkg: add

add(; url="https://github.com/KwatME/FeatureSetEnrichment.jl")
```

Test

```sh
julia --eval 'using FeatureSetEnrichment; score_set(["a", "b"], [-1., 1.], ["b"])'
```

## Use

See [examples](notebook/example.ipynb).

---

Check out the [python version](https://github.com/KwatME/FeatureSetEnrichment.py) and the [desktop application](https://github.com/KwatME/GSEA.web).
