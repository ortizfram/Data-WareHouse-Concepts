# Data-WareHouse-Concepts
==============================================
# *️⃣What's Data WareHouse?
`Relational` Data-base designed for `analytical needs`

location where `multiple databases are stored`, & works on the **OLAP** bases (online,anlytical, processing)

![image](https://user-images.githubusercontent.com/51888893/185953581-01fa05dd-6848-440a-a64b-aa3a39924779.png)

# *️⃣What's Data WareHousing?

## ㊗️StagingData through ETL, D.Marts

Act of `organizing & storing` data efficiently in a way that's avaible for peopple to get insights from them `data into info`

this procces of `stagging data` before uploadding to dataWarehouse it's done by `ETL` (extract transform load)

`Data Mart` `specific data from d.warehouse` with `limited access`

![image](https://user-images.githubusercontent.com/51888893/185955912-b0e1fd67-890c-415f-bbd2-ffbe51889d1b.png)

# *️⃣OLAP
❗ __online analytical processing__

flexible way to make complicated `analysis` of `multidimentional data`

- OLTP : data stored in form of 2 dimentional tables 

## ㊗️ advantages:
- new view of looking data

- supports filtering/sorting data

- data can be __refined__

![image](https://user-images.githubusercontent.com/51888893/185961322-1a3391a1-a6f6-4712-bce4-3fbf83376ef0.png)

## ㊗️ Types of OLAP cubes:
### 🟢 MOLAP
processes &  stores `directly into a multidimentional database`

- __ADVANTAGES__ :excelent performance, complex caculations can be performed

- __DISADVANTAGES__ : limited data can be handled
### 🟢 ROLAP
`Dynamic multidimentional analysis` of data stored in a relational DB than multidimentional DB

- __ADVANTAGES__ : greater ammount of data can be processed

- __DISADVANTAGES__ : more processing time/disk space
### 🟢 HOLAP
`Hybrid` of data stored in a relational DB than multidimentional DB

- __ADVANTAGES__ : drill-through from cube into underlying relational data
