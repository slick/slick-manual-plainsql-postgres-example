# The PlainSQL example from the Slick Manual

```
$ sbt run
[info] running com.typesafe.slick.docs.PlainSQL
Coffees:
* Colombian	101	7.99	0	0
* French_Roast	49	8.99	0	0
* Espresso	150	9.99	0	0
* Colombian_Decaf	101	8.99	0	0
* French_Roast_Decaf	49	9.99	0	0
Parameterized StaticQuery:
* Colombian supplied by Acme, Inc.
* French_Roast supplied by Superior Coffee
* Colombian_Decaf supplied by Acme, Inc.
Supplier #49: Vector(Supplier(49,Superior Coffee,1 Party Place,Mendocino,CA,95460))
Coffee Colombian: Some(Coffee(Colombian,101,7.99,0,0))
Deleted 1 rows
Coffee Colombian: None
[success] Total time: 1 s, completed 3 Dec 2019, 12:30:21
```

