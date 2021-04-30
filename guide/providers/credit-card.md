# Credit card

{% hint style="info" %}
All parameters are optional. The sample parameters are the default values used by each function.
{% endhint %}

```rust
Faker.credit_card_security_code()
=> 607


Faker.credit_card_full()
=> JCB 16 digit Avril Sporer 3112592210219064 CVC 761


Faker.credit_card_full("amex")
=> American Express Denny Shanahan 379850328675328 CID 0011


Faker.credit_card_number()
=> 4846355085045639


Faker.credit_card_number("amex")
=> 379705418324270


Faker.credit_card_provider()
=> discover


Faker.generate_card_number()
=> 5205143464510379


Faker.generate_card_number("52",16)
=> 5273798972368375

```



The types of cards supported are: 

* `mastercard`-&gt; _Mastercard_ 
* `visa16` -&gt; _VISA 16 digit_
* `visa13`-&gt; _VISA 13 digit_
* `amex` -&gt; _American Express_
* `discover` -&gt; _Discover_
* `diners` -&gt; _Diners Club / Carte Blanche_
* `jcb15` -&gt; _JCB 15 digit_
* `jcb16` -&gt; _JCB 16 digit_
* `voyager` -&gt; _Voyager_

