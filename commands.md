# Commands

+ At NULL database level
  - Show All DataBases
    ```mysql
    SHOW databases ;
    ```
  - Create Database
    ```mysql
    CREATE DATABASE database_name ;
    ```
  - Show Currunt Database
    ```mysql
    SELECT dataBase() ;
    ```
  - Create Table
    ```mysql
    CREATE TABLE database_name . table_name (
      column_name data_type(size) CONSTANTS 
      /*
       * specify multiple columns
       * sheparate columns using ‘,’ 
       *
       */
    ) ;
    ```
