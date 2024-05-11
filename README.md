# ETL-Banksim-Artificial

![image](https://github.com/Aliviarahma/ETL-Banksim-Artificial/assets/71688560/83ec05f2-e547-409a-aca9-fd4ab340290e)

## Data Model
Data terdiri dari dua tabel dengan jumlah row yang sama (594643)  dan ada lebih dari dua kolom dengan value yang sama sehingga dapat diasumsikan bahwa kedua tabel tersebut saling terkait dengan isi value yang sama. Dalam hal ini kedua table dapat dilakukan merger data. Berikut adalah diagram table dari data banksim artificial.

![image](https://github.com/Aliviarahma/ETL-Banksim-Artificial/assets/71688560/7967f0d7-9188-4142-9bfe-de9e888b6ce0)

## Extract (csv file -> postgresql)
![image](https://github.com/Aliviarahma/ETL-Banksim-Artificial/assets/71688560/087698e5-7f7e-40fd-a2de-fcb020ccce5f)

## Load 
•	Load data from PostgreSQL Local to Cloud SQL(PostgreSQL)
Bigquery Link: https://storage.cloud.google.com/datafellowship12_testing/banksim_artificial.csv
![image](https://github.com/Aliviarahma/ETL-Banksim-Artificial/assets/71688560/87f0251b-7746-423b-8057-37e56a4615c7)
![image](https://github.com/Aliviarahma/ETL-Banksim-Artificial/assets/71688560/184cae6e-e70d-4b1c-9300-2b330348274f)

•	Load data from Cloud SQL to Bigquery
Bigquery Link: https://console.cloud.google.com/bigquery?ws=!1m5!1m4!4m3!1smy-test-project-401305!2sdatafellowship!3sbanksim_artificial
![image](https://github.com/Aliviarahma/ETL-Banksim-Artificial/assets/71688560/4dcbc13e-1376-41a3-80f6-baa881ee83b9)

