# Quick start

Faker is a generator of false data for julia programming language.

Faker will be of use to you, whether you need to start your database, test the operation of its services or build documents automatically.

Faker is heavily inspired by  [Python Faker](https://github.com/joke2k/faker), and by [Ruby Faker](https://github.com/stympy/faker).

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



