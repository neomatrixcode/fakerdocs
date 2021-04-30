# Generator

Faker allows you to create data collections with all the available functions of the library, this function is called generator. The generator function receives a tuple of functions called `items` and the name of a function called `separator`, which will be in charge of joining the result of the execution of the functions and adding a character between them.

```rust
Faker.generator(
	items=(
		Faker.user_name()
		,Faker.first_name()
		,Faker.city()
		,Faker.postcode()
		,string(Faker.user_name(),"@",Faker.domain_name())
	)
	, separator=Faker.string
)
=> Cira.BalistreriSadieThielbury00743Johnson.Marci@mas.name
```

```rust
Faker.generator(
	items=(
		Faker.user_name()
		,Faker.first_name()
		,Faker.city()
		,Faker.postcode()
		,string(Faker.user_name(),"@",Faker.domain_name())
	)
	, separator=Faker.stringWithSpaces
)
=> SKris Leota New Joe 35420-2738 UPadberg@ngac.com

```

```rust
Faker.generator(
	items=(
		Faker.user_name()
		,Faker.first_name()
		,Faker.city()
		,Faker.postcode()
		,string(Faker.user_name(),"@",Faker.domain_name())
	)
	, separator=Faker.stringWithComa
)
=> Dean12, Eugene, Port Palmer, 74355, zStokes@ji.info

```



## Separator custom

It is possible to create a custom function that defines our own separator character.

```rust
stringCustom(a::String,b::String)::String = string(a," - ",b)

Faker.generator(
	items=(
		Faker.user_name()
		,Faker.first_name()
		,Faker.city()
		,Faker.postcode()
		,string(Faker.user_name(),"@",Faker.domain_name())
	)
	, separator=stringCustom
)

=> lStamm - Judith - West Fernanda - 87842 - Bergstrom.Althea@klah.org

```

