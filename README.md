I created a table for creating a database on drivers including their license numbers, state that they reside in as well as the make and model of their car. License number is listed as an int because it is a completely digit-based number, and the other variables are "varchar" because they include characters.

![](https://i.gyazo.com/80dbc8ae42bb075ce35e74ac69de9d4b.png)

![](https://i.gyazo.com/0854de26cf827dc79d9b70acbc0d28eb.png)

```
`Function` (

`License_Num` ,

`State` ,

`Car_Make`,

'Car_Model',

)

VALUES (

'1828922599', 'FL', 'Honda', 'Civic'

);
```

I did not have a problem creating the table and found it quite interesting how it builds the table and organizes it and is able to be sequenced. However I did not fully understand how to merge it with PHP and to display it on my website. I assume users can enter information on my website and it puts it into the sequel database but I could not get it to connect and display any information.
