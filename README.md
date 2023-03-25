https://github.com/SaiAshish9/ApacheCassandra

https://github.com/SaiAshish9/SpringData_ReactiveApacheCassandra

https://github.com/SaiAshish9/Hadoop

https://github.com/SaiAshish9/Apache-Spark

https://github.com/SaiAshish9/Spark_Hive

https://github.com/SaiAshish9/HBase

HBase Vs Cassandra Vs MongoDB:
https://logz.io/blog/nosql-database-comparison/

```
We'll use smart phones , but we never imagined how much data it 
generates in terms of text, email, photos, videos, searches and music.

Approximately 40 exabytes (x1e+9) of data gets generated by a
single smart phone user.

A database is an organized collection of data to access and manage data easily from permanent memory (files, HDD ,etc) . Relational database ( tables ) ( Mysql, Postgres ) (ACID (Atomicity Consistency Isolation Durability) property) and non-relational database ( json,xml files,etc ) ( MongoDB, Redis, Cassandra DB ) (BASE (Basically Available, Soft state, Eventually consistent) property) are it's types.

Data warehouse is the collection of data from various data sources which forms 
the main component of business.
It makes use of sql queries and application log files.
It is also used to perform queries on large amounts of data.
It involves the process of extraction, loading, and transformation
for providing the data for analysis. #collection

Data mining is considered as a process of extracting data from large 
data sets with the help of patterns. #extraction

Big Data basically refers to the data which is in large volume and
has complex data sets(Structured, semi-structured, or non-structured) 
which cannot be processed by traditional data processing software and
databases. Various operations like analysis, manipulation, changes, 
etc are performed on data and then it is used by companies for intelligent
decision making. e.g.Apache Hadoop.
```

<img width="1271" alt="Screenshot 2023-03-24 at 8 13 06 PM" src="https://user-images.githubusercontent.com/43849911/227556934-f92b1349-ac9e-48a6-bd41-2911786840d0.png">

```
Imagine this number multiplied by 5 billion smart phone users.

This amount is quite a lot for traditional computing systems to handle and this massivs of data is termed as big data.
```

<img width="1269" alt="Screenshot 2023-03-24 at 8 16 20 PM" src="https://user-images.githubusercontent.com/43849911/227557794-86c234b8-e2b9-46e3-adfb-89e600bbc802.png">

<img width="1231" alt="Screenshot 2023-03-24 at 8 19 04 PM" src="https://user-images.githubusercontent.com/43849911/227558539-f30ce481-864e-469d-bdd4-93850e541a48.png">

```
We can define any data as bigData with the concept of 5Vs:

1. Volume 
2. Velocity 
3. Variety 
4. Veracity
5. Value
```

<img width="1263" alt="Screenshot 2023-03-24 at 8 20 28 PM" src="https://user-images.githubusercontent.com/43849911/227558926-cafb1027-ffa5-4db4-a70d-9acfd4203602.png">

```
Let's understand this with the help of hospital industry.


2314 Exabytes (volume) of data in hostipals are collected in terms
of patients records and test results at a very high speed (velocity).

Variety refers to the various data types like structured (excel reports),
semi-structured (log files) and unstructured (x-ray images).
```

<img width="585" alt="Screenshot 2023-03-24 at 8 25 17 PM" src="https://user-images.githubusercontent.com/43849911/227560279-2fbd6be2-d9ac-4b21-92ab-2169a2fcfc75.png">

```
Accuracy and trustworthiness of generated data is termed as veracity.
Analysis this data will help the medical sector in terms of
disease detection, better treatment and reduced costs.
```

<img width="1256" alt="Screenshot 2023-03-24 at 8 27 13 PM" src="https://user-images.githubusercontent.com/43849911/227561119-ae0479d2-df36-44ab-9470-a859cecef0b3.png">

```
To do this we've various frameworks like cassandra, hadoop and spark.
```

<img width="806" alt="Screenshot 2023-03-24 at 8 28 28 PM" src="https://user-images.githubusercontent.com/43849911/227561524-d5d74630-918b-480d-b8a9-f9144b4fbdbb.png">

```
For example,

Hadoop uses a distributed file system known as hadoop distributed file system
to store big data.

If we have a huge file, it will be broken down into smaller chunks and 
will be stored at various machines.

Not only that when we break the file, we also make copies of it, which
will be present at various nodes. This way big data will be present in a
distributed way.

And makes sure even if one machine fails, data is safe on another. 
```

<img width="853" alt="Screenshot 2023-03-24 at 8 30 45 PM" src="https://user-images.githubusercontent.com/43849911/227562114-98de9a24-d065-46f1-89eb-5d65d6906605.png">

<img width="855" alt="Screenshot 2023-03-24 at 8 33 38 PM" src="https://user-images.githubusercontent.com/43849911/227562838-5f4b3f35-2073-4c2e-b3ea-a838136c7f6c.png">

<img width="873" alt="Screenshot 2023-03-24 at 8 34 32 PM" src="https://user-images.githubusercontent.com/43849911/227563060-4b8600b8-21c7-4ab9-b256-c1339bc09cf2.png">

```
mapReduce technique is used to process big data.

A task can be broken into smaller tasks and instead of one machine
three machines can take up smaller tasks. And can be completed in a parallel
fashion. And we can get results at the end. Because of this processing becomes
easy and fast. This is known as parallel processing.
```

<img width="1001" alt="Screenshot 2023-03-24 at 8 39 09 PM" src="https://user-images.githubusercontent.com/43849911/227564187-9e411308-9294-4469-9cb1-e3f5f2241e04.png">

<img width="656" alt="Screenshot 2023-03-24 at 8 42 24 PM" src="https://user-images.githubusercontent.com/43849911/227565460-f89dbfe4-e928-4c82-aa05-9ba1dfdf5673.png">

```
Now that we've stored and processed the big data. We can analyze this data in numerous applications.
```

<img width="972" alt="Screenshot 2023-03-24 at 8 43 40 PM" src="https://user-images.githubusercontent.com/43849911/227565783-6ab60f77-98f1-483b-b2de-33cf4cdc05fc.png">

```
In games like call of duty, designers analyze users data to understand
which stage most of the users pause , restart or quit. This can help them 
to rework on story mind behind the game and improve the UX which in turn reduces
the customer churn rate.
```

<img width="1168" alt="Screenshot 2023-03-24 at 8 46 56 PM" src="https://user-images.githubusercontent.com/43849911/227566604-5720d8a6-1495-426a-b047-e0c5ed4aa600.png">

<img width="1187" alt="Screenshot 2023-03-24 at 8 47 38 PM" src="https://user-images.githubusercontent.com/43849911/227566769-108a7eff-e89a-446e-b18c-30536c98dd28.png">

```
Similary big data can help in disaster management such as hurricane sandy which
came in 2012.

It's used to understand the storms on east cost of the USA.
And necessary measures were taken.

It could predict the hurricane's landfall five days in advance which wasn't  possible earlier.

Hence, big data is much valued once its processed and analyzed.

```

<img width="1212" alt="Screenshot 2023-03-24 at 8 50 00 PM" src="https://user-images.githubusercontent.com/43849911/227567382-9e18533a-8d20-4e10-b8ba-9e33bcb654cc.png">

<img width="1063" alt="Screenshot 2023-03-24 at 8 51 17 PM" src="https://user-images.githubusercontent.com/43849911/227567728-3a91d101-8ab8-45b8-b6ae-f07d80550127.png">

