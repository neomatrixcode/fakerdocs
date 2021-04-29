# Internet

Faker.pixels\(\) =&gt; 545 Faker.email\(\) =&gt; Ezequiel.Greenholt@hotmail.com Faker.free\_email\(\(Faker.user\_name\(\),"@",Faker.free\_email\_domain\(\)\)\)=&gt; Reinger.Cyril@gmail.com Faker.safe\_email\(\(Faker.user\_name\(\),"@example.", Faker.domain\_suffix\(\)\)\)=&gt; Julia.Jenkins@example.name Faker.user\_name\(\) =&gt; Ward.Gregorio Faker.domain\_name\(\(Faker.domain\_word\(\),".",Faker.domain\_suffix\(\)\)\)=&gt; wh.net Faker.domain\_word\(\) =&gt; sdac Faker.domain\_suffix\(\) =&gt; name Faker.ipv4\(\) =&gt; 214.67.140.84 Faker.ipv6\(\) =&gt; 4f5a:b849:a51f:44fe:1c8e:81dd:17c7:a567 Faker.uri\(\) =&gt; [http://ks.net/main.php](http://ks.net/main.php) Faker.url\(\) =&gt; [http://www.bj.us/](http://www.bj.us/) Faker.image\_url\(\) =&gt; [http://placehold.it/1022x352](http://placehold.it/1022x352) Faker.uri\_extension\(\) =&gt; .php Faker.uri\_path\(deep=0\) =&gt; blog/list Faker.uri\_page\(\) =&gt; about Faker.mac\_address\(\) =&gt; c8:fe:1c:0b:9a:05 Faker.company\_email\(\(Faker.user\_name\(\),"@",Faker.domain\_name\(\)\)\)=&gt; Parker.Marty@msaw.name

```haskell
Faker.pixels()                                                 => 545
Faker.email()                                                  => Ezequiel.Greenholt@hotmail.com
Faker.free_email((Faker.user_name(),"@",Faker.free_email_domain()))=> Reinger.Cyril@gmail.com
Faker.safe_email((Faker.user_name(),"@example.", Faker.domain_suffix()))=> Julia.Jenkins@example.name
Faker.user_name()                                              => Ward.Gregorio
Faker.domain_name((Faker.domain_word(),".",Faker.domain_suffix()))=> wh.net
Faker.domain_word()                                            => sdac
Faker.domain_suffix()                                          => name
Faker.ipv4()                                                   => 214.67.140.84
Faker.ipv6()                                                   => 4f5a:b849:a51f:44fe:1c8e:81dd:17c7:a567
Faker.uri()                                                    => http://ks.net/main.php
Faker.url()                                                    => http://www.bj.us/
Faker.image_url()                                              => http://placehold.it/1022x352
Faker.uri_extension()                                          => .php
Faker.uri_path(deep=0)                                         => blog/list
Faker.uri_page()                                               => about
Faker.mac_address()                                            => c8:fe:1c:0b:9a:05
Faker.company_email((Faker.user_name(),"@",Faker.domain_name()))=> Parker.Marty@msaw.name
```

