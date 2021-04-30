# Randomness seed

When using Faker for unit testing, you will often want to generate the same data set. The library provides a Faker.seed method that initializes the shared random number generator. Calling the same methods with the same version of faker and seed produces the same results.

```rust
Faker.seed(83)
```

