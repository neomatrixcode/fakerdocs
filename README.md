# Quick start

## Install

First [download](https://julialang.org/downloads/#current_stable_release) and install Julia `1.5` or higher.                                                                                                                        To do the installation use any of the following commands:

```
$ (@v1.5) pkg> add Faker
```

```bash
using Pkg
Pkg.add("Faker")
```

## Use

To execute the functions included in the Faker package it is necessary to refer to them with the prefix Faker.

```julia
using Faker

Faker.email() # => "kirsten.greenholt@corkeryfisher.info"
```



