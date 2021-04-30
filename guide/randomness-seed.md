# Randomness seed

When using Faker for unit testing, you will often want to generate the same data set. The library provides a Faker.seed method that initializes the shared random number generator. Calling the same methods with the same version of faker and seed produces the same results.

```rust
Faker.seed(83)

Faker.first_name()
"Vern"

Faker.first_name()
"Francis"

Faker.seed(83)

Faker.first_name()
"Vern"

Faker.first_name()
"Francis"
```

{% hint style="warning" %}
Please note that as Faker is updated, results are not guaranteed to be consistent across versions. If you code your test results, be sure to pin the Faker version.
{% endhint %}



