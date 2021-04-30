# Address

{% hint style="info" %}
All parameters are optional. The sample parameters are the default values used by each function.
{% endhint %}

```rust
Faker.state_abbr()
=> WY


Faker.latitude()
=> 8.0078125


Faker.street_name()
=> Orlando Rest


Faker.address((Faker.street_address(),Faker.city(),Faker.state_abbr(),Faker.postcode()))
=> 89911 Orville Divide Hoppemouth UT 92987


Faker.street_address()
=> 74600 Mindi Springs


Faker.postcode()
=> 29127


Faker.longitude()
=> 13.0078125


Faker.country()
=> Mozambique


Faker.geo_coordinate(center=0, radius=0.001)
=> 13.01


Faker.secondary_address()
=> Apt. 084


Faker.city_prefix()
=> East


Faker.city_suffix()
=> borough


Faker.building_number()
=> 08565


Faker.city()
=> Gradyside


Faker.state()
=> Alaska

```

