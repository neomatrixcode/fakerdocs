# Generator



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
	, separator=Faker.string
)
=> Cira.BalistreriSadieThielbury00743Johnson.Marci@mas.name
```



## Separator custom

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

