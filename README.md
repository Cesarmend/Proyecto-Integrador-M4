# Proyecto-Integrador-M4

# Part 1) HDFS

The document docker-compose-v1.yml was run and it brought all the CSV files onto the Docker container in a Hadoop environment right after cloning the repository
![image](https://github.com/user-attachments/assets/aaa0ed44-0d24-45c1-b810-f93f33986d98)

All the CSV files were successfully copied into the HDFS
![image](https://github.com/user-attachments/assets/aa6212a8-6e61-4f0b-9a96-80e5fd748f39)


# Part 2) Hive

The docker-compose-v2.yml environment was used and we entered into the hive -bash command setup
![image](https://github.com/user-attachments/assets/c08eacd5-60e8-4867-8b41-0e1ac475081c)

Then the file Paso02.hql was copied into the hdfs environment and subsequently executed with the following command:

    hive -f /opt/Paso02.hql

![image](https://github.com/user-attachments/assets/33f5b76e-0527-4925-bc92-701edc79ea65)

Later, some SQL queries were tested to verify if it recognized the tables in the Paso02.hql file
![image](https://github.com/user-attachments/assets/ccbdb256-2cab-4bf9-941f-c1d8933c52ed)


# Part 3) Parquet format
A test table named cliente_parquet was created to try out the new format on the hive environment 
![image](https://github.com/user-attachments/assets/178abe6d-afac-4880-89f0-69c2883035f8)
