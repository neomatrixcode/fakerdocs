# Datetime

{% hint style="info" %}
All parameters are optional.
{% endhint %}

```rust
Faker.months()
=> 4


Faker.am_pm()
=> PM


Faker.iso8601()
=> 2067-06-10T02:28:01


Faker.date_time("Y-m-d HH:MM:SS")
=> 2058-6-18 23:34:00


Faker.month_name()
=> February


Faker.day_of_week()
=> Monday


Faker.day_of_month()
=> 13


Faker.date_time_between("-30y", "now","Y-m-d HH:MM:SS")
=> 2014-10-3 19:43:40


Faker.time("H:M:S")
=> 17:43:42


Faker.unix_time()
=> 1075658593


Faker.timezone()
=> Europe/Stockholm


Faker.century()
=> IV


Faker.date("Y-m-d")
=> 2048-12-30


Faker.year()
=> 1962


Faker.date_time_this_century(before_now=true, after_now=false, pattern="Y-m-d HH:MM:SS")
=> 2012-4-1 00:00:00


Faker.date_time_this_decade(before_now=true, after_now=false, pattern="Y-m-d HH:MM:SS")
=> 2021-1-18 00:00:00


Faker.date_time_this_year(before_now=true, after_now=false, pattern="Y-m-d HH:MM:SS")
=> 2021-1-15 00:00:00


Faker.date_time_this_month(before_now=true, after_now=false, pattern="Y-m-d HH:MM:SS")
=> 2021-4-8 19:43:40
```

