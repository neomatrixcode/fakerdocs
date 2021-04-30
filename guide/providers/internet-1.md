# Internet

{% hint style="info" %}
All parameters are optional.
{% endhint %}

```rust
Faker.pixels()
=> 545


Faker.email()
=> Ezequiel.Greenholt@hotmail.com


Faker.free_email((Faker.user_name(),"@",Faker.free_email_domain()))
=> Reinger.Cyril@gmail.com


Faker.safe_email((Faker.user_name(),"@example.", Faker.domain_suffix()))
=> Julia.Jenkins@example.name


Faker.user_name()
=> Ward.Gregorio


Faker.domain_name((Faker.domain_word(),".",Faker.domain_suffix()))
=> wh.net


Faker.domain_word()
=> sdac


Faker.domain_suffix()
=> name


Faker.ipv4()
=> 214.67.140.84


Faker.ipv6()
=> 4f5a:b849:a51f:44fe:1c8e:81dd:17c7:a567


Faker.uri()
=> http://ks.net/main.php


Faker.url()
=> http://www.bj.us/


Faker.image_url()
=> http://placehold.it/1022x352


Faker.uri_extension()
=> .php


Faker.uri_path(deep=0)
=> blog/list


Faker.uri_page()
=> about


Faker.mac_address()
=> fe:1c:0b:9a:05:91


Faker.company_email((Faker.user_name(),"@",Faker.domain_name()))
=> Parker.Marty@msaw.name
```

