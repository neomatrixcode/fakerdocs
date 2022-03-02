# Person

{% hint style="info" %}
All parameters are optional.&#x20;
{% endhint %}

```rust
Faker.first_name()
=> Maynard


Faker.first_name("M")     
=> Clair


Faker.first_name("F")     
=> Margert


Faker.female_first_name() 
=> Gregory


Faker.male_first_name()   
=> Corey


Faker.last_name()
=> Botsford


Faker.prefixe()
=> Mr.


Faker.blood_type()
=> A+


Faker.job()
=> Scientist, forensic


Faker.profile(
	"username"
	,"name"
	,"sex"
	,"address"
	,"mail"
	,"birthdate"
	,"job"
	,"company"
	,"residence"
	,"current_location"
	,"blood_group"
	,"website"
)
=> Dict{Any,Any}("username" => "Jessenia.Terry","sex" => "M","address" => "670 Witting Vista Nienowburgh NY 36645-7370","name" => "Sarah","job" => "Buyer, industrial","mail" => "Dannielle.Krajcik@gmail.com","birthdate" => "1989-1-8","current_location" => (7.50390625, 1.009765625),"blood_group" => "AB+","residence" => "714 Orval Springs South Isidrobury IN 92106-4791","company" => "Wiza and Sons","website" => "http://mo.org/")


Faker.simple_profile(
	"username"
	,"name"
	,"sex"
	,"address"
	,"mail"
	,"birthdate"
)
=> Dict{Any,Any}("name" => "Billie","mail" => "NBruen@yahoo.com","username" => "Warren.Heidenreich","birthdate" => "2020-5-19","sex" => "M","address" => "9405 Kyle Ford Cierratown TX 35045-0682")


Faker.user_profile(
	(Faker.user_name()
	,Faker.first_name()
	,rand(["M","F"])
	,Faker.address()
	,Faker.free_email()
	,Faker.date()
	,Faker.job()
	,Faker.company()
	,Faker.address()
	,string(Faker.latitude(),Faker.longitude())
	,Faker.blood_type()
	,Faker.url())
)
=> yKeeling, Luke, F, 982 Mitchell Meadows Lake Earnest IN 47743, White.Yong@yahoo.com, 2035-8-20, Engineer, maintenance, Sauer, Gleichner and Nolan, 829 Dicki Station South Terinaview SC 05927, 6.003906258.0078125, B+, http://www.rr.org/
```
