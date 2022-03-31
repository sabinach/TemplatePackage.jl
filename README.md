# TemplatePackage

## Installation Instructions

To install this package:
```julia
import Pkg
Pkg.add("MyPackage")
```

1. Install the package
2. Use it
3. Profit

## To Build Package

Make sure `TemplatePackage/` is in `~/.julia/dev/`, then run:
```julia
dev TemplatePackage
```

## To Test Package

```julia
test TemplatePackage
```

## To Generate UUID

```julia
using UUIDs
UUIDs.uuid4()
```

## Get UUID of Registered Packages

```
cat ~/.julia/environments/v1.7/Manifest.toml
```

## View Installed Packages

https://pkgdocs.julialang.org/v1/managing-packages/
```julia
st
```